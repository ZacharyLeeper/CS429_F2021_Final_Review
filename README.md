# Final Review

This is a set of review problems for the CS 429 F2021 class's final.
It covers everything learned in the last third of the class from exam 2 onward, including Y86 ISA, pipelining, caching, and linking.
The final is cumulative, so you'll still need to study material from exams 1 and 2, but the focus will be what this covers.
As a disclaimer, I'm writing this with much less time available, and I probably won't be able to update it if there's any issues.

The rest is just copy-pasted from the Exam 2 review:

# Overview

There are two self-explanatory directories contained in this repository.
The `problems` directory contains the practice problems, and the `solutions` directory contains documented solutions for each problem.

Inside the problems directory, there are subdirectories for each problem type, for different topics covered in class.
A file named `problem.txt` in the directory will have a corresponding`answer.txt` in the solutions directory, with a detailed explanation.
Most problems will also have corresponding C or Assembly code files, which will follow the same naming scheme.

# Testing Your Answers

Obviously, it defeats the purpose of practicing if you immediately look at the solutions, so I've included a way to test them to know if your answer is correct or not, without seeing the actual solution, in case you want to try again.
Inside each problem subdirectory, there's a file named `sol.txt`, where you can write your answers, and a python script named `check_correctness.py`, which you can invoke with `python3 check_correctness.py` in the terminal to test your answer to all problems, or `python3 check_correctness.py -d <directory name>` to test your answers to that specific directory.
For example, `python3 check_correctness.py -d structs_unions` will check your solution to the problems in the `structs_unions` subdirectory.
