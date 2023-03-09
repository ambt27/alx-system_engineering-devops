Command 1 : Create a script that switches the current user to the user
whoami : Print the current username
groups : Prints all the groups the current user is part of
chown : Changes the owner of the file
touch : Create a new file
chmod u+x : Add execute permission to the owner of the file
chmod u+x, g+x, u+r : adds execute permission to the owner and the group owner, and read permission to other users,
chmod +111 hello : adds execution permission to the owner, the group owner and the other users
chmod 007 : sets the permission
chmod 753 : sets mode
chmod --reference =  :set mode to a list of file
chmod -R ugo+X : Sets the mode of the file
mkdir -m 751 my8dir : adds execute permission to all subdirectories
