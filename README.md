# BankingSystem in C using system calls

./initilize => to reset all the data in files

./server => server has printf statements , so don't run it in background

./client => to run client

Steps to run program:

ADMIN:-
1. log into admin with password  'aditya'

2. create new user account. 
  a. account ID will be assigned.
    eg: P 1 for first user 
        S 1 for second user [if single user account then there will be no second user]
        by default the password for newly created account will be the user name.
 
USER-

1. log in with user id and password.
  eg:  userid: P 1 => here P indicates that he is primary user 


BUGS TO BE FIXED:-
1. When a single user account is converted into join user account by adding secondary user by admin then secondary user is not able to login. ✅
2. insted of scanf("%s"...); use scanf(" %[^\n]%".....);


  
 
