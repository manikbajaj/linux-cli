# Practice Exercise: Linux Permissions

In this exercise, you will practice the use of permissions in Linux.

## Preliminary Setup

First, let's set up a directory with some files to manipulate. Run the following commands:

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

1. Run `ls -l` to see the current permissions of `file1.txt`.
2. Use `chmod` in symbolic mode to give read permission to all users on `file1.txt`.
3. Verify the new permissions by running `ls -l` again.

### Task 2: Remove Write Permission for Group and Others

1. Check the current permissions for `file2.txt`.
2. Use `chmod` in symbolic mode to remove write permission for the group and others.
3. Confirm the permissions were updated.

## Exercise 2: `chmod` - Numeric Mode

### Task 1: Give Execute Permission to the Owner

1. Use `ls -l` to see the current permissions of `file1.txt`.
2. Use `chmod` in numeric mode to give only the owner execute permissions.
3. Verify using `ls -l`.

### Task 2: Set Specific Permissions

1. For `sub_directory/sub_file.txt`, set the permissions so that the owner can read, write, and execute; the group can read and execute; others can only read.
2. Confirm the permissions were updated.

## Exercise 3: `umask`

### Task 1: Set a New `umask`

1. Check the current `umask` setting by running `umask`.
2. Set a new `umask` so that new files will have `rw-r-----` and directories will have `rwxr-x---`.
3. Confirm the new `umask` by running `umask` again.

### Task 2: Create a New File and Directory

1. Create a new file and directory:

   ```bash
   echo "This is a new file." > new_file.txt
   mkdir new_directory
   ```

2. Check their permissions using `ls -l` and confirm they match the intended permissions set by `umask`.

## Bonus: Reset to Default

After you've completed the exercises, reset the `umask` to your system's default or as per your requirement.
