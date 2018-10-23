# CIS_458_Lab_6
Author: Troy Madsen

THIS WAS CREATED FOR EDUCATIONAL PURPOSES ONLY

Compilation:
g++ -o malware.o -Wall malware.c

Operation:
This program functions by writing itself to the users login script. Once written to, the program will continually spawn off new processes to eat up system resources until the system crashes. Due to this being written to the login script, it will always run whenever the user logs in, effectively preventing computer use until program or script entry is removed.
