# Auxilliary-Project



In this project a bash script is used automate creation of  user accounts on Linux. I have used this script on Ubuntu 20.04.
There are three files available:

onboarding user - main bash script to create the user.
newuser - list of users.

Before running the scripts you must provide permission to run the script:






Onboarding user

The script is aimed to read the newuser.csv file, print the user name and go throug ha automation process using for loops and if statements to create the user accounts, apply the appropriate permissions for the .ssh folders and the private and public keys which are required to ssh.

The following permission has been set for the relevant files and folders(Permission reference):

~/.ssh/ - 700

~/.ssh/authorized_keys - 600

The aim of the script is also to allow SSH access from localhost and also from my local machine.

The public key -authenticated_keys needs the local machine hostname added.


