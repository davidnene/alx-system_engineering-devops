Shell permissions project
0 su betty changes the user to betty
1 whoami prints the effective username of the current user
2 groups prints all the groups the current user is part of
3 chmod betty hello changes ownership of the file hello from current owner to betty
4 touch hello creates an empty file called hello
5 chmod u+x hello gives the owner of the file hello execute permissions
7 chmod +x hello adds execution permissions to owner, groups and others, to the file hello
8 chmod 007 hello restricts all permissions to owner and group and gives all permssions to others, to the file hello
