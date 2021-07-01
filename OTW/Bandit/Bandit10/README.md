# Solution guide

The way to enter in Bandit10 is getting the flag on a txt file with a lot of characters unreadables, the command that i use to find the solution is:

> strings data.txt | grep "=="

with this command i filter all the unreadable characters and i make sure to get only the strings with the "=" character.
