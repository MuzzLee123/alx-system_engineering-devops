"su betty" Create a script that switches the current user to the user betty
"whoami" Write a script that prints the effective username of the current user
"groups" Write a script that prints all the groups the current user is part of.
"chown betty hello" Write a script that changes the owner 

of the file hello to the user betty
"touch hello" Write a script that creates an empty file called hello
"chmod 700 hello" Write a script that adds execute permission to the owner of the file hello
"chmod ug+x,o+r" Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
"chmod a+x hello" Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello
"chmod o+rwx hello" Write a script that sets the permission to the file hello as follows: Owner: no permission at all; Group: no permission at all; Other users: all the permissions
"chmod 753 hello" Write a script that sets the mode of the file hello to this:



-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
"chmod --reference=olleh hello" Write a script that sets the mode of the file hello the same as olleh’s mode
"chmod -r a+x" Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
"mkdir -m 751 my_dir" Create a script that creates a directory called my_dir with permissions 751 in the working directory.
"chgrp school hello" Write a script that changes the group owner to school for the file hello
