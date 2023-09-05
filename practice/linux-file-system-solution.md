# Practice Exercise File System: Solutions

## Initial Setup

1. Open your terminal.

   ```bash
   # No command needed; simply open the terminal application.
   ```

2. Navigate to your home directory using the `cd` command.
   ```bash
   cd ~
   ```

## Exercise Tasks

### Task 1: Directory Operations

1. Create a new directory named `myWorkspace`.

   ```bash
   mkdir myWorkspace
   ```

2. Change your current directory to `myWorkspace`.
   ```bash
   cd myWorkspace
   ```

### Task 2: Creating Files and Directories

1. Inside `myWorkspace`, create the following directories: `dir1`, `dir2`, `dir3`.

   ```bash
   mkdir dir1 dir2 dir3
   ```

2. Inside `dir1`, create a text file named `file1.txt` and write "Hello World" into it.

   ```bash
   echo "Hello World" > dir1/file1.txt
   ```

3. Create another text file named `file2.txt` in `dir1` and write "Linux Command Line" into it.
   ```bash
   echo "Linux Command Line" > dir1/file2.txt
   ```

### Task 3: Exploring Files and Directories

1. List all the files and directories inside `myWorkspace`.

   ```bash
   ls
   ```

2. List all the files and directories inside `myWorkspace` along with their detailed information.
   ```bash
   ls -l
   ```

### Task 4: File Type

Use the `file` command to determine the type of `file1.txt` and `file2.txt`.
`bash
    file dir1/file1.txt
    file dir1/file2.txt
    `

### Task 5: Reading File Contents

Use the `less` command to read the contents of `file1.txt`.
`bash
    less dir1/file1.txt
    `

### Task 6: Working with Wildcards

1. Use a wildcard to list all `.txt` files in `dir1`.

   ```bash
   ls dir1/*.txt
   ```

2. Use a wildcard to list all items in `myWorkspace` that start with the letter "d".
   ```bash
   ls d*
   ```

### Task 7: Copying Files

1. Copy `file1.txt` from `dir1` to `dir2`.

   ```bash
   cp dir1/file1.txt dir2/
   ```

2. Verify that `file1.txt` is indeed copied to `dir2`.
   ```bash
   ls dir2/
   ```

### Task 8: Moving and Renaming Files

1. Move `file2.txt` from `dir1` to `dir3`.

   ```bash
   mv dir1/file2.txt dir3/
   ```

2. Rename `file2.txt` in `dir3` to `renamedFile.txt`.
   ```bash
   mv dir3/file2.txt dir3/renamedFile.txt
   ```

### Task 9: Creating Links

1. Create a symbolic link for `file1.txt` in `dir2` and name it `file1_link.txt`.

   ```bash
   ln -s ../dir1/file1.txt dir2/file1_link.txt
   ```

2. Create a hard link for `file1.txt` in `dir2` and name it `file1_hardlink.txt`.
   ```bash
   ln dir1/file1.txt dir2/file1_hardlink.txt
   ```

### Task 10: Deleting Files and Directories

1. Remove the file `file1.txt` from `dir2`.

   ```bash
   rm dir2/file1.txt
   ```

2. Remove `dir1` and its contents.
   ```bash
   rm -r dir1
   ```

## Final Steps

1. Use the `ls` command to list the contents of `myWorkspace` to verify that you've completed all tasks successfully.

   ```bash
   ls -l
   ```

2. Exit the terminal.
   ```bash
   exit
   ```

---
