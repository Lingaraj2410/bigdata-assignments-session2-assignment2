This assignment focusses on creating a CSV file, moving it into /hadoop directory and changing its access permissions.

chmod command is used to change or modify file access permissions

Example: chmod 777 sample_file.txt
Here, the user is trying to set all kinds of access permissions (read, write and execute permissions) on the file 'sample_file.txt' to User, Group and Others.

access permission          Assigned value or weight 
read                                4
write                               2
execute                             1

In the following command:
chmod 777 filename
The value, 7 that occurred for the first time indicates that User has been assigned read, write and execute permissions on given filename.
The subsequent value, 7 is for Group of users and the final value, 7 is assigned to Others.  
