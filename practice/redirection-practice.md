# Practice Exercise: Mastering Redirection

## Objective

The aim of this exercise is to reinforce your understanding of standard streams and redirection in Linux. You will practice redirecting stdout, stderr, stdin, and understand the significance of their ordering.

---

## Pre-Requisites

- A Linux terminal
- Basic understanding of shell commands like `ls`, `cat`, `echo`, etc.
- Familiarity with redirection operators (`>`, `>>`, `<`, `2>`, `2>&1`, etc.)

---

## Tasks

### Task 1: Redirecting stdout

**Objective**: Redirect the output of the `ls` command to a file named `filelist.txt`.

### Task 2: Redirecting stderr

**Objective**: Attempt to `cat` a non-existent file and redirect the error message to a file named `error.txt`.

### Task 3: Redirecting stdout and stderr to different files

**Objective**: Run a command that will produce both stdout and stderr and redirect them into two different files (`output.txt` for stdout and `error.txt` for stderr).

**Hint**: Use `ls` for an existing file and a non-existing file simultaneously.

### Task 4: Redirecting stdin

**Objective**: Use the `wc` command to count the number of words in a sentence provided via stdin redirection.

**Hint**: Create a file named `sentence.txt` with some text in it.

### Task 5: Redirection Order

**Objective**: Redirect both stdout and stderr to a single file, `all_output.txt`.

**Note**: You need to swap the order of stdout and stderr redirection and observe the differences.
