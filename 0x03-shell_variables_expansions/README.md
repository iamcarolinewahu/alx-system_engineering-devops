This directory contains tasks for shell, init files, variabes and expansions. 
General Requirements:
Allowed editors: vi, vim, emacs
All your scripts will be tested on Ubuntu 20.04 LTS
All your scripts should be exactly two lines long ($ wc -l file should print 2)
All your files should end with a new line (why?)
The first line of all your files should be exactly #!/bin/bash
A README.md file, at the root of the folder of the project, describing what each script is doing
You are not allowed to use &&, || or ;
You are not allowed to use bc, sed or awk
All your files must be executable

0. Create a script that creates an alias.

Name: ls
Value: rm *

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 0-alias

1.  Create a script that prints hello user, where user is the current Linux user.
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 1-hello_you

2. dd /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 2-path

3. Create a script that counts the number of directories in the PATH.
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 3-paths

4. Create a script that lists environment variables.
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 4-global_variables

5. Create a script that lists all local variables and environment variables, and functions.
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 5-local_variables

6. Create a script that creates a new local variable.

Name: BEST
Value: School

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 6-create_local_variable

7. Create a script that creates a new global variable.

Name: BEST
Value: School

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 7-create_global_variable

8. Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 8-true_knowledge

9. Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.

POWER and DIVIDE are environment variables

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 9-divide_and_rule

10. Write a script that displays the result of BREATH to the power LOVE

BREATH and LOVE are environment variables
The script should display the result, followed by a new line

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 10-love_exponent_breath

11. Write a script that converts a number from base 2 to base 10.

The number in base 2 is stored in the environment variable BINARY
The script should display the number in base 10, followed by a new line

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 11-binary_to_decimal

12. Create a script that prints all possible combinations of two letters, except oo.

Letters are lower cases, from a to z
One combination per line
The output should be alpha ordered, starting with aa
Do not print oo
Your script file should contain maximum 64 characters

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 12-combinations

13. Write a script that prints a number with two decimal places, followed by a new line.

The number will be stored in the environment variable NUM.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 13-print_float

14. Write a script that converts a number from base 10 to base 16.

The number in base 10 is stored in the environment variable DECIMAL
The script should display the number in base 16, followed by a new line

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 100-decimal_to_hexadecimal

