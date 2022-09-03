This is a full list of Shell Permission scripts and their usage.


su betty => chnages from the current user to betty
id -u => prints the effective username of the current user
groups => lists all the groups the current user is part of
sudo chown betty hello => change the file owner of hello to betty
touch hello => create an empty file called hello
chmod 744 hello => add execute permission for only owner
chmod 774 hello => add execute permissions for ownerand groups but only read for other users
chmod a+x hello => add execute permissions for all users, group and other users
chmod 007 hello => add no permission for owner and groups but all permissions for other users
chmod 753 hello => write a script that sets this mode -rwxr-x-wx
chmod --reference=olleh hello => mirror the file permissions for olleh to hello
chown a+x => create a script that adds execute rights for all subdir in the current directory for owneer, group and public
mkdir -m 751 my_dir => set 751 as permissio for a newly created dir
chgrp school hello => change the group ownership to hello
chown vincent:staff *
chown -h vincent:staff __hello => write a script that changes the owner and group of the symbolic link file called __hello
chown --from=guillame:betty hello => changes the owner of the file hello to betty
