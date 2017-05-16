# Finger-User-Enumeration
Enumerate users using finger service

#### Usage
```sh
$ ./finger_enum_user.sh

Script takes a file with a list of users as argument
Usage:
./finger_enum_user.sh <filename.txt>
```

#### Sample Run
```
$ ./finger_enum_user.sh ../users.txt
User : user
Login: user           			Name: user
Directory: /home/user               	Shell: /bin/bash
Last login Tue May 16 01:47 (BST) on pts/0 from 192.168.1.34
No mail.
No Plan.

Login: dovenull       			Name: Dovecot login user
Directory: /nonexistent             	Shell: /bin/false
Never logged in.
No mail.
No Plan.
```
Check for the parameter <i>"Directory:"</i> in the output, if <i>/home/username</i> means that it is a valid user on the system.
