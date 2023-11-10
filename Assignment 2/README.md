# Assignments
Homework 2
Due Date: 11/17/2023 11.59PM

## Students

We're using GitHub Classroom, which basically means you do all your work in a pre-prepared GitHub repository.
The history of the repository must show contributions from all.

## Instructions

Modify your Assignment 1 submission of dining philosophers code.

The Instructions are same as the Assignemnt 1. 

`java driver` *np nc tt et rl*

*np*, *nc*, *tt*, *et*, and *rl* are five non-negative integers that represent the following:

- *np* is the number of philosophers (and forks).
- *nc* is the number of cycles that each philosopher will go through. If this parameter is 0, they run forever.
- *tt* is the maximum thinking time, in units of milliseconds.
- *et* is the maximum eating time, in units of milliseconds.
- If *rl* is 0, then all philosophers are right-handed and try to grab their right chopstick first. If *rl* is 1, then even-numbered philosophers are right-handed and odd-numbered philosophers are  left-handed.

Obviously you will also have to modify the philosopher class to implement these changes.
Add print statements to trace the flow of execution.
A philosopher should go through the following cycle - I have included sample id numbers and times:

    Philosopher 0 thinks for 123 units
    Philosopher 0 wants right chopstick
    Philosopher 0 has right chopstick
    Philosopher 0 wants left chopstick
    Philosopher 0 has left chopstick
    Philosopher 0 eats for 456 units
    Philosopher 0 releases left chopstick
    Philosopher 0 releases right chopstick

You can extend this format if you want to include other useful information, such as the specific chopstick id, the handedness of a philosopher, or anything else that you think is interesting.

## Execution

On top of your last traces, now include both right-handed and left-handed philosophers to avoid deadlock, the classical "five philosophers eating forever" showing a chance deadlock, and the classical "five philosophers eating forever" but with large maximum thinking and eating times. 
You don't have to limit yourself to just these - any other trace that shows interesting behavior is also appropriate.

For any given deadlock, you should only show the part of the trace from the first chopstick acquisition that causes the deadlock to the deadlock itself.
Do not include pages and pages of uninteresting trace output.

## Rubric

2/3 of the points will be based on the formatting, clarity, and appropriateness of your code.
I am not holding you to a specific code style guide, nor am I demanding professional-level code quality.

1/3 of the points will be based on if you can acheieve the other interesting behavior.
