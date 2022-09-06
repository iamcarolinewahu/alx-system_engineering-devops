Thisdirectory contains tasks for shell i/o Redirections and filters
General Requirements:
Allowed editors: vi, vim, emacs
All your scripts will be tested on Ubuntu 20.04 LTS
All your scripts should be exactly two lines long ($ wc -l file should print 2)
All your files should end with a new line (why?)
The first line of all your files should be exactly #!/bin/bash
A README.md file, at the root of the folder of the project, describing what each script is doing
You are not allowed to use backticks, &&, || or ;
All your files must be executable
You are not allowed to use sed or awk

0. Write a script that prints “Hello, World”, followed by a new line to the standard output.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 0-hello_world

1. Write a script that displays a confused smiley "(Ôo)'.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 1-confused_smiley

2. Display the content of the /etc/passwd file.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 2-hellofile

3. Display the content of /etc/passwd and /etc/hosts

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 3-twofiles

4. Display the last 10 lines of /etc/passwd

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 4-lastlines

5. Display the first 10 lines of /etc/passwd

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 5-firstlines

6. Write a script that displays the third line of the file iacta.

The file iacta will be in the working directory

You’re not allowed to use sed

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 6-third_line

7. Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 7-file

8. Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 8-cwd_state

9. Write a script that duplicates the last line of the file iacta

The file iacta will be in the working directory

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 9-duplicate_last_line

10. Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 10-no_more_js

11. Write a script that counts the number of directories and sub-directories in the current directory.

The current and parent directories should not be taken into account
Hidden directories should be counted

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 11-directories

12. Create a script that displays the 10 newest files in the current directory.

Requirements:

One file per line
Sorted from the newest to the oldest

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 12-newest_files

13. Create a script that takes a list of words as input and prints only words that appear exactly once.

Input format: One line, one word
Output format: One line, one word
Words should be sorted


Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 13-unique

14. Display lines containing the pattern “root” from the file /etc/passwd

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 14-findthatword

15. Display the number of lines that contain the pattern “bin” in the file /etc/passwd

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 15-countthatword

16. Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.


Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 16-whatsnext

17. Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 17-hidethisword

18. Display all lines of the file /etc/ssh/sshd_config starting with a letter.

include capital letters as well

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 18-letteronly

19. Replace all characters A and c from input to Z and e respectively.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 19-AZ

20. Create a script that removes all letters c and C from input.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 20-hiago

21. Write a script that reverse its input.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 21-reverse

22. Write a script that displays all users and their home directories, sorted by users.

Based on the the /etc/passwd file

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 22-users_and_homes

23. Write a command that finds all empty files and directories in the current directory and all sub-directories.

Only the names of the files and directories should be displayed (not the entire path)
Hidden files should be listed
One file name per line
The listing should end with a new line
You are not allowed to use basename, grep, egrep, fgrep or rgrep

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x02-shell_redirections
File: 100-empty_casks


