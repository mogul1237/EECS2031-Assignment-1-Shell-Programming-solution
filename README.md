# EECS2031-Assignment-1-Shell-Programming-solution

Download Here: [EECS2031 Assignment 1 : Shell Programming solution](https://jarviscodinghub.com/assignment/eecs2031-assignment-1-shell-programming-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

In this assignment, you will be writing four shell programs. The first program (myrm.sh) is designed to emulate a safer rm command. The second program (guess.sh) emulates a simple number guessing game. The third program (calculator.sh) is a tool that emulates a basic calculator. The fourth program (utilities.sh) is an interactive tool for running basic utility commands.
Important Notes:
 You must use the submit command to electronically submit your solution by the due date.  All programs are to be written using #!/bin/bash.  Your programs should be tested on the EECS labs before being submitted. Failure to test your programs on EECS labs will result in a mark of 0 being assigned.  To get full marks, your code must be well-documented (code comments start with “#”).
What To Submit
When you have completed the assignment, move or copy your four shell scripts in a directory (e.g., assignment1), and use the following command to electronically submit your files within that directory:
% submit 2031M a1 myrm.sh guess.sh calculator.sh utilities.sh
You can also submit the files individually after you complete each part of the assignment– simply execute the submit command and give the filename that you wish to submit. You may submit your solutions as many times as you wish prior to the submission deadline. Make sure you name your files exactly as stated (including lower/upper case letters). Failure to do so will result in a mark of 0 being assigned. You may check the status of your submission using the command:
% submit -l 2031M a1

A. Safe Delete (25%)
The UNIX command rm does not provide for recovery of deleted files through a mechanism like the recycle bin typically found in modern operating systems. Write a shell script “myrm.sh” that is designed to replace rm. It will move the target file(s) specified as parameters to a recycled bin directory instead of really deleting them. Your script should:
 Create a new directory to be used as the recycle bin.  Print an error message if there are no files specified as parameters, where the correct usage is also explained.  Print a feedback message “deleting
