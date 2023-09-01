# Linux Command Line Practice Exercise

## Objective

To practice and reinforce your understanding of the following Linux command line utilities:

- `ls`
- `file`
- `less`
- Wildcards
- `mkdir`
- `cp`
- `mv`
- `ln`
- `rm`

## Initial Setup

1. Open your terminal.
2. Navigate to your home directory using the `cd` command.

## Exercise Tasks

### Task 1: Directory Operations

1. Create a new directory named `myWorkspace`.
2. Change your current directory to `myWorkspace`.

### Task 2: Creating Files and Directories

1. Inside `myWorkspace`, create the following directories: `dir1`, `dir2`, `dir3`.
2. Inside `dir1`, create a text file named `file1.txt` and write "Hello World" into it.
3. Create another text file named `file2.txt` in `dir1` and write "Linux Command Line" into it.

### Task 3: Exploring Files and Directories

1. List all the files and directories inside `myWorkspace`.
2. List all the files and directories inside `myWorkspace` along with their detailed information.

### Task 4: File Type

Use the `file` command to determine the type of `file1.txt` and `file2.txt`.

### Task 5: Reading File Contents

Use the `less` command to read the contents of `file1.txt`.

### Task 6: Working with Wildcards

1. Use a wildcard to list all `.txt` files in `dir1`.
2. Use a wildcard to list all items in `myWorkspace` that start with the letter "d".

### Task 7: Copying Files

1. Copy `file1.txt` from `dir1` to `dir2`.
2. Verify that `file1.txt` is indeed copied to `dir2`.

### Task 8: Moving and Renaming Files

1. Move `file2.txt` from `dir1` to `dir3`.
2. Rename `file2.txt` in `dir3` to `renamedFile.txt`.

### Task 9: Creating Links

1. Create a symbolic link for `file1.txt` in `dir2` and name it `file1_link.txt`.
2. Create a hard link for `file1.txt` in `dir2` and name it `file1_hardlink.txt`.

### Task 10: Deleting Files and Directories

1. Remove the file `file1.txt` from `dir2`.
2. Remove `dir1` and its contents.

## Final Steps

1. Use the `ls` command to list the contents of `myWorkspace` to verify that you've completed all tasks successfully.
2. Exit the terminal.
