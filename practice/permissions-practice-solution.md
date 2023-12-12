# Practice Exercise Solutions: Linux Permissions

## Preliminary Setup

If you haven't already, set up the directory and files for this exercise:

```bash
mkdir practice_folder
cd practice_folder
echo "Hello, World!" > file1.txt
echo "Learning Linux permissions is fun!" > file2.txt
mkdir sub_directory
echo "This is inside the subdirectory" > sub_directory/sub_file.txt
```

## Exercise 1: `chmod` - Symbolic Mode

### Task 1: Give Read Permission to All Users

1. To see the current permissions of `file1.txt`, run:

   ```bash
   ls -l
   ```

2. Use `chmod` in symbolic mode to give read permission to all users:

   ```bash
   chmod a+r file1.txt
   ```

3. Verify the new permissions:

   ```bash
   ls -l
   ```

### Task 2: Remove Write Permission for Group and Others

1. To check the current permissions for `file2.txt`, run:

   ```bash
   ls -l
   ```

2. Use `chmod` in symbolic mode to remove write permission for the group and others:

   ```bash
   chmod go-w file2.txt
   ```

3. Confirm the permissions were updated:

   ```bash
   ls -l
   ```

## Exercise 2: `chmod` - Numeric Mode

### Task 1: Give Execute Permission to the Owner

1. To see the current permissions of `file1.txt`, run:

   ```bash
   ls -l
   ```

2. Use `chmod` in numeric mode to give only the owner execute permissions:

   ```bash
   chmod 744 file1.txt
   ```

3. Verify using `ls -l`.

### Task 2: Set Specific Permissions

1. To set the permissions so that the owner can read, write, and execute; the group can read and execute; others can only read, use:

   ```bash
   chmod 754 sub_directory/sub_file.txt
   ```

2. Confirm the permissions were updated:

   ```bash
   ls -l sub_directory/
   ```
