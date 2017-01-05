# undelete
A program to recover previously deleted file on Minix developed as part of IIT's CS551 course

REQUIREMENTS:

1. Develop an undelete command for the MINIX file system. 

2. When it is invoked from a shell, it will attempt to recover any regular file that has been deleted (by the unlink() system call) in the current directory. 
   Alternatively, it will recover a specific file given its filename.

3. Since a recovery is not always possible, your command will try its best and report to the user if recovery is not possible. 
   In other words, you are not supposed to keep the deleted file around so that it can be undeleted. 

4. When the disk blocks allocated to the recoverable deleted file is needed they should return to the system, and then the file cannot be undeleted thereafter.

5. When the system requires disk blocks occupied by recoverable deleted files, implement a policy to determine which file to give up first. 

Project hosted privately at https://bitbucket.org/sashankbv/undelete

