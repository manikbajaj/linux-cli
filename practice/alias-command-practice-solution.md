# Practice Exercise Solutions: Alias

## Solution to Exercise Sections

### Section 1: Basic Alias Creation

1. Open a terminal.

   ```bash
   # Simply open the terminal application from the menu or use a keyboard shortcut.
   ```

2. Create an alias `l` for the command `ls -l`.

   ```bash
   alias l='ls -l'
   ```

3. Execute the alias `l` and observe the output.

   ```bash
   l
   ```

4. Verify whether your alias is correct or not.
   ```bash
   # The output should be identical to running `ls -l`
   ```

### Section 2: Changing Directories Using Alias

1. Create an alias `gotohome` which will navigate you to your home directory using `cd ~`.

   ```bash
   alias gotohome='cd ~'
   ```

2. Use `gotohome` to navigate to your home directory.

   ```bash
   gotohome
   ```

3. Confirm that you are in the correct directory by executing `pwd`.
   ```bash
   pwd
   # The output should show your home directory.
   ```

### Section 3: Alias for Directory Operations

1. Create an alias `mkcd` that makes a new directory and then automatically changes into it.

   ```bash
   alias mkcd='mkdir -p $1 && cd $1'
   ```

2. Test `mkcd` by creating and moving into a new directory of your choice.
   ```bash
   mkcd new_directory
   ```

### Section 4: Listing Aliases

1. List all aliases that you've created so far in this exercise.

   ```bash
   alias
   ```

2. Check the output and confirm that the aliases you've created are displayed.
   ```bash
   # The output should list `l`, `gotohome`, and `mkcd` among other aliases you may have.
   ```

### Section 5: Unalias

1. Remove the alias `l` that you created in Section 1 using `unalias`.

   ```bash
   unalias l
   ```

2. Confirm that the alias has been removed by trying to execute it.
   ```bash
   l
   # This should result in an error, confirming that the alias has been removed.
   ```
