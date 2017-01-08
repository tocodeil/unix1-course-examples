## General Instructions
In the following exercise you'll need to setup your own server, define users and install software on it. You can use a new virtual machine locally or install the server on any cloud service. We recommend to register with Digital Ocean as presented in the course. The following signup link will give you the first month for free:
https://m.do.co/c/aeaf5e4ea3ae

## Setting Up The Server

1. Create a new Ubuntu server and perform initial software upgrade. What commands did you use? What does each command do?

2. What system services are defined by default on the server? How did you find out?

3. How can you show a log of everything that happened in the system? Paste the last 10 lines from that log

## Users and Groups

1. Which file holds all user definitions on the machine? Which file holds all the group definitions?

2. Create a new user that can login and get a normal shell. What line was added to the users file?

3. Create a new user that can't login (used for running system services). What line was added to the users file?

4. What file holds all the passwords of all users on the system? How can you reset a user's password?

5. Create a new user that can install software by running sudo. Which files were modified in the process? What were the changes?

6. The file sshd_config defines which users can login via ssh and in what way. Define SSH keys for user root and modify sshd_config so user root can only login with her SSH keys. What files did you modify?

## Installing Software

1. Which software repositories are defined for your machine by default? In which file is the information saved?

2. What command will you use to install "ruby" programming language on the server?

3. What command will you use to search for "gcc" command in the repositories?

4. Try to search for command "g++" in the repositories. Did you also get irrelevant results? How can you modify the search to get only relevant results? (i.e. results that actually have the word "g++" in them).

5. Install apache2 and set up a simple web site. Browse to your IP address and verify you can see the page. If you've used a public cloud service (such as Digital Ocean) paste here the IP address so we can see it too.
