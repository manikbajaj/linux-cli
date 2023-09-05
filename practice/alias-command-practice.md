# Practice Exercise: Alias

**Objective**: This exercise will help you understand how to create, manage, and use aliases in Linux. Aliases are shortcuts or abbreviations that help you simplify complex or lengthy commands.

## Prerequisites

- Basic understanding of the Linux command line
- Access to a Linux terminal (physical or virtual machine)

## Exercise Sections

### Section 1: Basic Alias Creation

1. Open a terminal.
2. Create an alias `l` for the command `ls -l`.
3. Execute the alias `l` and observe the output.
4. Verify whether your alias is correct or not.

### Section 2: Changing Directories Using Alias

1. Create an alias `gotohome` which will navigate you to your home directory using `cd ~`.
2. Use `gotohome` to navigate to your home directory.
3. Confirm that you are in the correct directory by executing `pwd`.

### Section 3: Alias for Directory Operations

1. Create an alias `mkcd` that makes a new directory and then automatically changes into it. You can use `mkdir` and `cd` for this, combined in a single command.
2. Test `mkcd` by creating and moving into a new directory of your choice.

### Section 4: Listing Aliases

1. List all aliases that you've created so far in this exercise.
2. Check the output and confirm that the aliases you've created are displayed.

### Section 5: Unalias

1. Remove the alias `l` that you created in Section 1 using `unalias`.
2. Confirm that the alias has been removed by trying to execute it.
