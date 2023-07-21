Resources
Read or watch:

Expansions
Shell Arithmetic
Variables
Shell initialization files
The alias Command
Technical Writing
man or help:

printenv
set
unset
export
alias
unalias
.
source
printf
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What happens when you type $ ls -l *.txt
Shell Initialization Files
What are the /etc/profile file and the /etc/profile.d directory
What is the ~/.bashrc file
Variables
What is the difference between a local and a global variable
What is a reserved variable
How to create, update and delete shell variables
What are the roles of the following reserved variables: HOME, PATH, PS1
What are special parameters
What is the special parameter $??
Expansions
What is expansion and how to use them
What is the difference between single and double quotes and how to use them properly
How to do command substitution with $() and backticks
Shell Arithmetic
How to perform arithmetic operations with the shell
The alias Command
How to create an alias
How to list aliases
How to temporarily disable an alias
Other help pages
How to execute commands from a file in the current shell
Requirements
General
Allowed editors: vi, vim, emacs
All your scripts will be tested on Ubuntu 20.04 LTS
All your scripts should be exactly two lines long ($ wc -l file should print 2)
All your files should end with a new line (why?)
The first line of all your files should be exactly #!/bin/bash
A README.md file, at the root of the folder of the project, describing what each script is doing
You are not allowed to use &&, || or ;
You are not allowed to use bc, sed or awk
All your files must be executable
More Info
Read your /etc/profile, /etc/inputrc and ~/.bashrc files.

Look at some files in the /etc/profile.d directory.

Note: You do not have to learn about awk, tar, bzip2, date, scp, ulimit, umask, or shell scripting, yet.

0. <o>
Create a script that creates an alias.
*Name: ls
*Value: rm *
File: 0-alias

1. Hello you
Create a script that prints "hello user", where "user" is the current Linux user.
File: 1-hello_you

2. The path to success is to take massive, determined action
Add /action to the "PATH". /action should be the last directory the shell looks into when looking for a program.
File: 2-path

3. If the path be beautiful, let us not ask where it leads
Create a script that counts the number of directories in the "PATH".
File: 3-paths

4. Global variables
Create a script that lists environment variables.
File: 4-global_variables

5. Local variables
Create a script that lists all local variables and environment variables, and functions.
File: 5-local_variables

6. Local variable
Create a script that creates a new local variable.
*Name: BEST
*Value: School
File: 6-create_local_variable

7. Global variable
Create a script that creates a new global variable.
*Name: BEST
*Value: School
File: 7-create_global_variable

8. Every addition to true knowledge is an addition to human power
Write a script that prints the result of the addition of 128 with the value stored in the environment variable "TRUEKNOWLEDGE", followed by a new line.
File: 8-true_knowledge

9. Divide and rule
Write a script that prints the result of "POWER" divided by "DIVIDE", followed by a new line.
*"POWER" and "DIVIDE" are environment variables
File: 9-divide_and_rule

10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath
Write a script that displays the result of "BREATH" to the power "LOVE"
*"BREATH" and "LOVE" are environment variables
*The script should display the result, followed by a new line
File: 10-love_exponent_breath

11. There are 10 types of people in the world -- Those who understand binary, and those who don't
Write a script that converts a number from base 2 to base 10.

The number in base 2 is stored in the environment variable "BINARY"
*The script should display the number in base *10, followed by a new line
File: 11-binary_to_decimal

12. Combination
Create a script that prints all possible combinations of two letters, except "oo".

*Letters are lower cases, from "a" to "z"
*One combination per line
*The output should be alpha ordered, starting with "aa"
*Do not print "oo"
*Your script file should contain maximum 64 characters
File: 12-combinations

13. Floats
Write a script that prints a number with two decimal places, followed by a new line.
*The number will be stored in the environment variable "NUM".
File: 13-print_float

14. Decimal to Hexadecimal
Write a script that converts a number from base 10 to base 16.
*The number in base 10 is stored in the environment variable "DECIMAL"
*The script should display the number in base 16, followed by a new line
File: 14-decimal_to_hexadecimal

15. What happens when you type ls *.c
Write a blog post describing step by step what happens when you type ls *.c and hit Enter in your shell. Try to explain every step you know of, and give examples. A total beginner should understand what you have written.

Have at least one picture, at the top of the blog post
Publish your blog post on Medium or LinkedIn
Share your blog post at least on LinkedIn
Write professionally and intelligibly
Please, remember that these blogs must be written in English to further your technical ability in a variety of settings
Remember, future employers will see your articles; take this seriously, and produce something that will be an asset to your future

When done, please add all urls below (blog post, LinkedIn post, etc.)

16. Everyone is a proponent of strong encryption
Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII.
File: 15-rot13

17. The eggs of the brood need to be an odd number
Write a script that prints every other line from the input, starting with the first line.
File: 16-odd

18. I'm an instant star. Just add water and stir.
Write a shell script that adds the two numbers stored in the environment variables "WATER" and "STIR" and prints the result.
*"WATER" is in base "water"
*"STIR" is in base "stir".
*The result should be in base bestchol
File: 17-water_and_stir


