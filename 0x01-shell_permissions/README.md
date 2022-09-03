This is a full list of Shell Permission scripts and their usage.
0.   su betty => chnages from the current user to betty
1.   id -u => prints the effective username of the current user
2.   groups => lists all the groups the current user is part of
3.   sudo chown betty hello => change the file owner of hello to betty
4.   touch hello => create an empty file called hello
5.   chmod 744 hello => add execute permission for only owner
6.   chmod 774 hello => add execute permissions for ownerand groups but only read for other users
