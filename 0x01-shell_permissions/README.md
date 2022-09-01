0. su : switches between users
1. id -u -n : prints the effective username of the current user
2. groups : prints all the groups the current user is part of
3. chown betty hello : changes the owner of the file hello to the user betty
4. touch hello : creates an empty file called hello
5. chmod u+x hello : adds execute permission to the owner of the file hello
6. chmod u+x,g+x,o+r hello : adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
7. chmod ugo+x hello : adds execution permission to the owner, the group owner and the other users, to the file hello
8. chmod 007 hello : gives zero permission to both owner and group and gives all permission to others
9. chmod 753 hello : gives all permission to the user, write and execute permission to others and execute permission to thwe group
