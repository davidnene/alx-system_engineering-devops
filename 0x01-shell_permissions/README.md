Shell permissions project
0 su betty changes the user to betty
1 whoami prints the effective username of the current user
2 groups prints all the groups the current user is part of
3 chmod betty hello changes ownership of the file hello from current owner to betty
4 touch hello creates an empty file called hello
5 chmod u+x hello gives the owner of the file hello execute permissions
7 chmod +x hello adds execution permissions to owner, groups and others, to the file hello
8 chmod 007 hello restricts all permissions to owner and group and gives all permssions to others, to the file hello
9 chmod 753 hello changes the file hello mode to -rwxr-x-wx


12 mkdir -m 751 my_dir creates a directory called my_dir with permissions 751 in the working directory
13 chown :school hello changes the group owner to school for the file hello

