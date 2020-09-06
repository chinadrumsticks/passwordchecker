This is a program for checking that your passwords are secure and have not been leaked.
If they have, the program will tell you how many matches were found in the the database.
The program uses a public API of pwnedpasswords.com to check against password hashes.

This script accepts one or more passwords as arguments. Run the program like this:

$ python3 checkmypass.py <password1> ...
