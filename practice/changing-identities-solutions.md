# Practice Solutions: Changing Identities

Congratulations on completing the practice exercise! Now let's go through the solutions to ensure you have performed each task correctly.

## Preliminary Setup

1. Create a new directory for this exercise:

   ```bash
   mkdir user_mgmt_practice
   cd user_mgmt_practice
   ```

   _Solution: You should be inside the directory `user_mgmt_practice`._

2. Create two new users:

   ```bash
   sudo adduser username1
   sudo adduser username2
   ```

   _Solution: Two users, `username1` and `username2`, should have been created._

3. Create a new group:

   ```bash
   sudo addgroup practice_group
   ```

   _Solution: A new group named `practice_group` should have been created._

4. Create a text file and a directory:

   ```bash
   echo "This is a test file." > testfile.txt
   mkdir test_directory
   ```

   _Solution: A text file `testfile.txt` and a directory `test_directory` should be created._

## Exercise 1: `su` Command

### Task 1: Switch User

1. To switch to `username1`:

   ```bash
   su - username1
   ```

   _Solution: You should have switched to `username1`._

2. Confirm you've switched:

   ```bash
   whoami
   ```

   _Solution: It should output `username1`._

3. Exit back to your original user:

   ```bash
   exit
   ```

   _Solution: You should be back to your original user._

## Exercise 2: `sudo` Command

### Task 1: Run a Command with `sudo`

1. Attempt to create a new directory in `/var/`:

   ```bash
   mkdir /var/new_directory
   ```

   _Solution: Permission should have been denied._

2. Create the directory using `sudo`:

   ```bash
   sudo mkdir /var/new_directory
   ```

   _Solution: Directory should be created._

3. Remove the directory:

   ```bash
   sudo rmdir /var/new_directory
   ```

   _Solution: Directory should be removed._

## Exercise 3: `sudoers` File

### Task 1: Edit the `sudoers` File

1. Open the `sudoers` file:

   ```bash
   sudo visudo
   ```

   _Solution: The `sudoers` file should have opened._

2. Add permission for `username2`:

   ```bash
   username2 ALL=(ALL:ALL) ALL
   ```

   _Solution: The `sudoers` file should contain this new line._

## Exercise 4: `chown` Command

### Task 1: Change File Ownership

1. Change the owner of `testfile.txt`:

   ```bash
   sudo chown username1 testfile.txt
   ```

   _Solution: The owner should be changed to `username1`._

2. Verify:

   ```bash
   ls -l
   ```

   _Solution: The owner of `testfile.txt` should now be `username1`._

## Exercise 5: `chgrp` Command

### Task 1: Change Group Ownership

1. Change the group of `test_directory`:

   ```bash
   sudo chgrp practice_group test_directory
   ```

   _Solution: The group should be changed to `practice_group`._

2. Confirm:

   ```bash
   ls -l
   ```

   _Solution: The group of `test_directory` should now be `practice_group`._

If you've completed all these tasks correctly, well done! You have successfully practiced the `su`, `sudo`, `sudoers`, `chown`, and `chgrp` commands.
