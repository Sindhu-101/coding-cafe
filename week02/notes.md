1. /home/ravi
2. ls -a showed hidden files and directories that plain ls did not. 
 like bashrc, .cache etc. here -a means all, including hidden files (i.e. names starting with .)
3. the line: drwxr-xr-x 2 ravi ravi 4096 Aug 25 17:10 Downloads
here, the first column shows the file type and permissions.
So, here in drwxr-xr-x, d implies directory, r implies read permissions, w implies write permissions, x implies execute permission.
4. coding-cafe/week02 works because it a path relative to current directory (home). it is a relative path because it starts from the current location rather than the root.
5. mv was used to move a file from one directory to another and then to rename a file within the directory.
6. There are 9 folders on my PATH.
7. /usr/bin/python3
8. No, they are not same. Because their computer can have a different PATH and Python installation location.
9. The shell said ( Command 'pyton3' not found ). This probably happened because the shell looked through folders listed in PATH to find a command. Since python3 wasn't in PATH, the shell couldn't locate it. 
10. any file starting with (.) is classfied as a hidden file. ls only lists visible files but ls -a lists all entries including hidden. 
11. (.venv) is added to the very beggining of terminal prompt line. this indicates that python virtual environment is now active.
12. Current path (/home/ravi/coding-cafe/.venv/bin/). So, it isn't the same path.
Running activate opened virtual environmrnt's bin folder to front system's PATH variable. Since bin is listed first, it gets priortised and runs python binary inside .venv directory instead of the system-wide one.
13. The second list added requests along with its dependencies like certifi, charset-normaliser, urillib3, etc, whereas first list cobtained only pip.
14. It points at (/usr/bin/python3) which is basically back to system's global python installation because running deactivate removed the virtual environment.
15. the ls -h option prints brief usage summary and help message for the command directly in terminal, listing available flags and options ithout opening a full manual page.
16. Ctrl+C cancels running command and printed (KeyboardInterrupt), leaving inside python shell (>>>), while Ctrl+D sends End of FIle signal which returns the code to regular bash terminal prompt.
