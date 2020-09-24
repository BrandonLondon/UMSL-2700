CMP SCI 2700 – Assembly Language Project

Your program will find the sum of numbers input and display all of the input values. You will be writing
an assembly language project (using the virtual machine described in class and available on Canvas) to
perform a series of three tasks. These tasks will build on each other, starting with the simplest program
and progressing to the full program. The full program will read in numbers from the keyboard until the
value -1 is entered, then display all of the numbers that were entered, followed by their sum.

**Task 1:**

Write a program that will read in numbers until the value -1 is entered on the keyboard. Call this
program ‘task1.asm’ (use the .txt suffix if you are using eclipse to write the program).

**Task 2:**

Make a copy of your ‘task1.asm’ file called ‘task2.asm’ using “cp task1.asm task2.asm” on the shell
command line. This program should read in numbers until -1 is entered and then display the sum of all
single digit numbers [-9, -2] and [0, 9] that were entered. - 1 is used a flag to end the program, do not
use -1 in the sum.

**Task 3:**

Make a copy of ‘task2.asm’ and call it ‘task3.asm’. The stack must be used for this program. This final
version should read in numbers until -1 is entered, it should display all of the numbers entered (not just
single digit ones) followed by printing out the total of these numbers following these rules:

```
1) If a single digit number then multiply the single digit number to the accumulator.
2) All other numbers then add the number to the accumulator.
3) Do not display -1 as being entered, nor include it in the total.
```
**Submission:**

Your submission has to run on the virtual machine used in class and must be written in that assembly
language. You should submit it as an attachment on Canvas. The three files should have *.asm suffixes.
If you used *.txt suffix, please change to *.asm before submission.


