# 0x03. Shell, init files, variables and expansions

## Resources
[Expansions](http://linuxcommand.org/lc3_lts0080.php)

[Shell Arithmetic](https://www.gnu.org/software/bash/manual/html_node/Shell-Arithmetic.html)

[Variables](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_03_02.html)

[Shell initialization files](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_03_01.html)

[The alias Command](https://www.linfo.org/alias.html)

[Technical Writing](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/misc/2021/6/9112669886fd446a2aa3113c31319d1f468dc160.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240419%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240419T012117Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=3c8055ceff7d0a4257a8e7ef8d3463d2e54829da639431f6e2c03b4c67b1b7be)

**man or help:**
+ printenv
+ set
+ unset
+ export
+ alias
+ unalias
+ source
+ printf

## Shell Initialization Files
- What are the /etc/profile file and the /etc/profile.d directory
- What is the ~/.bashrc file
## Variables
- What is the difference between a local and a global variable
- What is a reserved variable
- How to create, update and delete shell variables
- What are the roles of the following reserved variables: HOME, PATH, PS1
- What are special parameters
- What is the special parameter $??
## Expansions
- What is expansion and how to use them
- What is the difference between single and double quotes and how to use them properly
- How to do command substitution with $() and backticks
## Shell Arithmetic
- How to perform arithmetic operations with the shell
## The alias Command
- How to create an alias
- How to list aliases
- How to temporarily disable an alias 
# Requirements
- All your scripts will be tested on Ubuntu 20.04 LTS
- All your scripts should be exactly two lines long ($ wc -l file should print 2)
- All your files should end with a new line 
- The first line of all your files should be exactly #!/bin/bash
- You are not allowed to use &&, || or ;
- You are not allowed to use bc, sed or awk
- All your files must be executable
## More Info
- Read your /etc/profile, /etc/inputrc and ~/.bashrc files.
- Look at some files in the /etc/profile.d directory.
> Note: You do not have to learn about awk, tar, bzip2, date, scp, ulimit, umask, or shell scripting, yet.
# Tasks
## 0. <o>
Create a script that creates an alias.
- Name: ls
- Value: rm *
> File: 0-alias 
## 1. Hello you
Create a script that prints hello user, where user is the current Linux user.
> File: 1-hello_you 
## 2. The path to success is to take massive, determined action
Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
> File: 2-path 
## 3. If the path be beautiful, let us not ask where it leads
Create a script that counts the number of directories in the PATH. 
> File: 3-paths 
## 4. Global variables 
Create a script that lists environment variables.
> File: 4-global_variables 
## 5. Local variables
Create a script that lists all local variables and environment variables, and functions.
> File: 5-local_variables 
## 6. Local variable
Create a script that creates a new local variable.
- Name: BEST
- Value: School
> File: 6-create_local_variable
## 7. Global variable
Create a script that creates a new global variable.
- Name: BEST
- Value: School
> File: 7-create_global_variable
## 8. Every addition to true knowledge is an addition to human power
Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
> File: 8-true_knowledge 
## 9. Divide and rule
Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.
- POWER and DIVIDE are environment variables
> File: 9-divide_and_rule
## 10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath
Write a script that displays the result of BREATH to the power LOVE
- BREATH and LOVE are environment variables
- The script should display the result, followed by a new line
> File: 10-love_exponent_breath 
## 11. There are 10 types of people in the world -- Those who understand binary, and those who don't
Write a script that converts a number from base 2 to base 10.
- The number in base 2 is stored in the environment variable BINARY
- The script should display the number in base 10, followed by a new line


> File: 11-binary_to_decimal
## 12. Combination
Create a script that prints all possible combinations of two letters, except oo.
- Letters are lower cases, from a to z
- One combination per line
- The output should be alpha ordered, starting with aa
- Do not print oo
- Your script file should contain maximum 64 characters


> File: 12-combinations
## 13. Floats
Write a script that prints a number with two decimal places, followed by a new line.


The number will be stored in the environment variable NUM. 
> File: 13-print_float
## 14. Decimal to Hexadecimal
Write a script that converts a number from base 10 to base 16.
- The number in base 10 is stored in the environment variable DECIMAL
- The script should display the number in base 16, followed by a new line
> File: 100-decimal_to_hexadecimal
## 15. Everyone is a proponent of strong encryption
Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII.
> File: 101-rot13
## 16. The eggs of the brood need to be an odd number
Write a script that prints every other line from the input, starting with the first line.
> File: 102-odd
## 17. I'm an instant star. Just add water and stir.
Write a shell script that adds the two numbers stored in the environment variables WATER and STIR and prints the result.
- WATER is in base water
- STIR is in base stir.
- The result should be in base bestchol
> File: 103-water_and_stir



