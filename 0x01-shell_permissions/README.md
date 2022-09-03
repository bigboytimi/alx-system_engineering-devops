This is a full list of Shell Permission scripts and their usage.


0.   su betty => chnages from the current user to betty
1.   id -u => prints the effective username of the current user
2.   groups => lists all the groups the current user is part of
3.   sudo chown betty hello => change the file owner of hello to betty
4.   touch hello => create an empty file called hello
5.   chmod 744 hello => add execute permission for only owner
6.   chmod 774 hello => add execute permissions for ownerand groups but only read for other users
7.   chmod a+x hello => add execute permissions for all users, group and other users
8.   chmod 007 hello => add no permission for owner and groups but all permissions for other users
9.   chmod 753 hello => write a script that sets this mode -rwxr-x-wx
10.  chmod --reference=olleh hello => mirror the file permissions for olleh to hello
11.  chown a+x => create a script that adds execute rights for all subdir in the current directory for owneer, group and public
12. mkdir -m 751 my_dir => set 751 as permissio for a newly created dir
13. chgrp school hello => change the group ownership to hello
14. chown vincent:staff *
15. chown -h vincent:staff _hello => write a script that changes the owner and group of the symbolic link file called _hello
16. chown --from=guillame:betty hello => changes the owner of the file hello to betty
