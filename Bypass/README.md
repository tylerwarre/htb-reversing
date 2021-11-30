# Challenge Description
The Client is in full control. Bypass the authentication and read the key to get the Flag.

# Files
- Bypass.exe: File to reverse
- Bypass.zip: Original file from HTB (password = hackthebox)

# Program TLDR
Program is a .Net 4 executable and asks the user for a username and password, but is hardcoded to always fail to authenticate. By forcing authentication to pass by debugging at runtime the user is presented with a third prompt asking for a key. The key can be extracted while debugging and if inputed correctly, the final flag is printed to the terminal.
