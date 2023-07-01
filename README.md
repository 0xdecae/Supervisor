# SUPERVISOR

## 2019 Development
Basic python script that will monitor a file for deletion or removal. If the file dissapears than the script will rewrite the file, compile it if needed, and execute it. 

In our test case I simply use a reverse shell backdoor program written in C. The script uses gcc to recompile the copy and execute. 

## 2023 Development
Guess who's back again. This time we're trying to do the thing in C, while also packing a compiled executable in a buffer within the supervisor executable. Goal here being to be able to copy/paste the executable from within the running supervisor process, onto disk, execute, then remove the executable so both instances are fileless[?]

