# Practice: Searching for Files and Directories Part 1

## Objective:

This exercise is designed to reinforce your knowledge of the `locate` command and the `find` command with a focus on tests for type, size, and pre-existing tests in Linux. You will practice finding files and directories on your Linux system based on various criteria.

### Prerequisites:

- Access to a Linux command line interface.
- Understanding of the `locate` and `find` commands.
- Familiarity with file types and size specifications in Linux.
- Knowledge of pre-existing tests for the `find` command.

## Exercise Tasks:

### Task 1: Locate Command Practice

1. Update the `locate` database before starting the exercises.
2. Use the `locate` command to find all instances of the `passwd` file on your system.
3. Try to locate any `.conf` files related to `httpd` (Hint: The filename might contain the string `httpd` and end with `.conf`).

### Task 2: Find Command - Type and Size Tests

1. Use the `find` command to list all files that end with `.conf` within `/etc`.
2. Find all regular files within your home directory that are larger than 5MB and have not been accessed in the last 30 days.
3. Search for all block device files in the `/dev` directory.

### Task 3: Find Command - Pre-existing Tests

1. Find all empty files within the `/var/log` directory.
2. Use the `find` command to identify all files that have been modified more than 7 days ago but less than 14 days ago in the `/home` directory.
3. Locate files in the `/tmp` directory that are not owned by the current user (replace "current user" with your actual username if necessary).

### Bonus Challenge

Combine multiple tests in a single `find` command to list all regular files within the `/var/log` directory that are larger than 10MB and were modified in the last two days, but ignore files in any subdirectory named `archive`.
