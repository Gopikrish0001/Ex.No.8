# 19CS545-Ex8 - Create a user account in GitHub



# AIM:

To create a user with UID 1326 and username as alies.


# Procedure:
1. The first command is: useradd -u 1326 alies 
2. This command creates a new user account on the system. Here's a breakdown of the options 
used: 
1. useradd: This is the command used to create a new user account. 
2. -u 1326: This option specifies the user ID (UID) for the new user account. The UID is a 
unique identifier associated with each user account. In this case, the new user account 
will have a UID of 1326. 
3. alies: This option specifies the username for the new user account. The username is 
the name that the user will use to log in to the system. 
3. The second command is: cat /etc/passwd | grep "alies" 
4. This command is used to verify the information about the newly created user account. Here's a 
breakdown of the options used: 
1. This command is used to display the contents of a file. In this case, it's used to 
display the contents of the /etc/passwd file. 
2. /etc/passwd: This file contains information about all user accounts on the system. 
Each line in the file contains information about one user account in the following format: 
username:password:UID:GID:full name or comment:home directory:default shell 
3. grep "alies": This option pipes the output of the cat command to the grep
command. The grep command is used to search for a specific pattern in the input. In 
this case, it's used to search for lines that contain the username "alies". 
5. The third line in the image is a shell prompt, which indicates that the user is ready to enter 
another command. 
6. In summary, these commands create a new user account named "alies" with a UID of 1326 and 
then verify the information about the newly created user account.


# Output:

![image](https://github.com/user-attachments/assets/2c31cd67-3d94-400e-bb4d-09ac61e3915e)


# Result:

Thus a Repository has been created successfully.
