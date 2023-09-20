# Practice Exercise: Changing Identities

Welcome to this practice exercise designed to reinforce your understanding of managing users, groups, and permissions in Linux.

## Preliminary Setup

First, let's create a practice environment. Open your terminal and perform the following actions:

1. Create a new directory for this exercise:

   ```bash
   mkdir user_mgmt_practice
   cd user_mgmt_practice
   ```

2. Create two new users (Replace `username1` and `username2` with your desired names). You will be prompted to enter a password:

   ```bash
   sudo adduser username1
   sudo adduser username2
   ```

3. Create a new group:

   ```bash
   sudo addgroup practice_group
   ```

4. Create a text file and a directory:

   ```bash
   echo "This is a test file." > testfile.txt
   mkdir test_directory
   ```

## Exercise 1: `su` Command

### Task 1: Switch User

1. Switch to `username1`:

   ```bash
   su - username1
   ```

2. Confirm you've switched by running `whoami`.

3. Exit back to your original user:

   ```bash
   exit
   ```

## Exercise 2: `sudo` Command

### Task 1: Run a Command with `sudo`

1. As `username1`, try creating a new directory in `/var/`:

   ```bash
   mkdir /var/new_directory
   ```

2. Now try the same using `sudo`:

   ```bash
   sudo mkdir /var/new_directory
   ```

3. Remove the created directory:

   ```bash
   sudo rmdir /var/new_directory
   ```

## Exercise 3: `sudoers` File

### Task 1: Edit the `sudoers` File

1. Open the `sudoers` file:

   ```bash
   sudo visudo
   ```

2. Add permission for `username2` to run all commands:

   ```bash
   username2 ALL=(ALL:ALL) ALL
   ```

3. Save and exit the file.

## Exercise 4: `chown` Command

### Task 1: Change File Ownership

1. Change the owner of `testfile.txt` to `username1`:

   ```bash
   sudo chown username1 testfile.txt
   ```

2. Verify the owner has changed:

   ```bash
   ls -l
   ```

## Exercise 5: `chgrp` Command

### Task 1: Change Group Ownership

1. Change the group of `test_directory` to `practice_group`:

   ```bash
   sudo chgrp practice_group test_directory
   ```

2. Confirm the group ownership has changed:

   ```bash
   ls -l
   ```
