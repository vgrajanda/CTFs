# Solution guide

The way to enter to bandit6 is getting the file on bandit5 with this characteristics:

human-readable
1033 bytes
non-executable

and the command that I discover to solve this problem is:

find . -type f -size 1033c ! -executable
