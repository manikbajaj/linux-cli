# Practice: Mastering Pipelines and Filters

## Objective

This practice exercise aims to solidify your understanding of pipelines, filters, and text-processing tools like `grep`, `uniq`, `wc`, `head`, and `tail` in the Linux command line.

---

## Pre-Requisites

- A Linux terminal
- Basic understanding of shell commands (`ls`, `cat`, `echo`, etc.)
- Text files with some content for manipulation
- Familiarity with pipeline (`|`) and filter commands (`grep`, `uniq`, `wc`, `head`, `tail`)

---

## Create a `names.txt` file to work with

```txt
Alice
Bob
Catherine
Dave
Eve
Frank
Grace
Alice
Hannah
Ian
Grace
Jack
Bob
Kelly
Liam
Mia
Nora
Oscar
Pam
Quincy
Dave
Rita
Steve
Tina
Ulysses
Vera
Walter
Mia
Xander
Yara
Zane
```

## Tasks

### Task 1: Simple Pipeline

**Objective**: Use the `ls` command and pipe its output to `wc` to count the number of files and directories in the current directory.

### Task 2: grep with Pipeline

**Objective**: List all files and directories in the current directory and use `grep` to filter out items that contain the word "test".

### Task 3: uniq and sort with Pipeline

**Objective**: Create a text file called `names.txt` containing multiple names, some of them repeating. Use `sort` and `uniq` to display a sorted list of unique names.

### Task 4: Count Lines using wc and Pipeline

**Objective**: Count the number of lines in the `names.txt` file created in Task 3 using `wc`.

### Task 5: Combining Multiple Filters

**Objective**: Use a combination of `sort`, `uniq`, and `wc` to count the number of unique names in the `names.txt` file.

### Task 6: Using head and tail

**Objective**: Display the first 5 and last 5 lines of the `names.txt` file.

---
