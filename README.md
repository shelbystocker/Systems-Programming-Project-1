# Systems Programming Project 1
Name: Shelby Stocker
Files being submitted: prog1.c, README.txt, and Makefile

Project Overview: This program takes a file and is able to run the following 6 commands: 'q' to quit the program, 'e' to print the name of the program, 'p' n to print the first n bytes of the file as characters, 'L' n to print the last n bytes of the file as characters, 'i' n to print the first 4n bytes of the file as n unsigned integers, and 'x' n to print the XOR of the first n bytes of the file as a 3 digit unsigned octal number. 

Known bugs/testing: I tested this program with various commands to try and throw it off and also commands that should work. I would compare my results to the workingProgram results to verify their accuracy. I ran this program with various test files I made and also ran it with /etc/hosts. The only issue I encounter with my program is with the L command. It completely works with every test file I made but whenever I ran my program with /etc/hosts the 'L' command would only give me garbage. However, it worked in many other test files I made. 
