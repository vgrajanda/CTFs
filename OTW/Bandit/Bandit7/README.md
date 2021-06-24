# Solution guide

The way to get into Bandit7 is getting the password file on the Bandit6 system, you need to find the file on all the system and the command that i use to find the file is:

find / -group bandit6 -user bandit7 2>&1 | grep -v "Permission Denied"

With "2>&1" we avoid the error "Permission denied"
