task 0: (command used =  su betty) used to switch user to betty
task 1: (command used = whoami) used to print the effective username of the current use
task 2: (command used = groups) used to print all the groups the current user is part
task 3: (command used = chown betty hello ) used to change the owner of the file hello
task 4: (command used = touch hello) used t create an empty file
task 5: (command used = chmod u+x hello) used to add execution permission to the file
task 6: (command used = chmod ug+x,o+r hello) adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
task 7: (command used = chmod a+x hello) adds execution permission to the owner, the group owner and the other users, to the file hello
task 8: (command used = chmod 007 hello) adds all permissions to other users and none to the owner and group
task 9: (command used = chmod 753 hello) set the mode of the file hello to 753
task 10: (command used = chmod --reference=olleh hello) mirror the permissions of the file olleh to hello
task 11: (command used =chmod a+X *) add execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
task 12: (command used = mkdir -m 751 my_dir) used to create a directory with permission 751 in the current working directory.
task 13: (command used = chgrp school hello) used to change the group owner of the file hello to school
task 14: (command used = chown vincent:staff *) changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

