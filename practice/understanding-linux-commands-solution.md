## Understanding Commands In Linux Practice - Solutions

### Basic Commands and Locating Binaries

1. **Solution to Question 1**: To identify the type of the commands `ls`, `cd`, `pwd`, and `echo`, the `type` command is used as follows:

   ```bash
   type ls
   type cd
   type pwd
   type echo
   ```

   The `type` command will return whether each of these is a built-in command, an alias, a file, etc.

2. **Solution to Question 2**: To locate the full path of the `grep` and `awk` commands, the `which` command is used:

   ```bash
   which grep
   which awk
   ```

   These commands will return the full paths where `grep` and `awk` are located.

### Getting Help and Documentation

3. **Solution to Question 3**: To find out what the `-r` option does in the `cd` built-in command:

   ```bash
   help cd
   ```

   This will display the help text for `cd`, where you can find the description for the `-r` option.

4. **Solution to Question 4**: To find out what the `-z` option does in the `tar` command:

   ```bash
   man tar
   ```

   Once the manual page is open, you can search for the `-z` option to find its description.

5. **Solution to Question 5**: To find commands related to 'directory':

   ```bash
   apropos directory
   ```

   The command will return a list of commands and utilities that are related to 'directory'. Listing any three from the returned list would satisfy this question.

6. **Solution to Question 6**: To get a one-line description of the `chmod`, `chown`, and `chgrp` commands:

   ```bash
   whatis chmod
   whatis chown
   whatis chgrp
   ```

   These commands will return one-line descriptions for each.

### Using Info for Detailed Documentation

7. **Solution to Question 7**: To find the description of the `-R` option in the `cp` command:

   ```bash
   info cp
   ```

   Once inside the `info` page, navigate to the section that describes the `-R` option.

8. **Solution to Question 8**: To find out how you can navigate to the "Next" node in an `info` document:

   ```bash
   info info
   ```

   Once inside the `info` page for `info`, navigate or search to find how to move to the "Next" node.

---
