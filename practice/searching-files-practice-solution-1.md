# Solution: Searching for Files and Directories Part 1

Below you will find the solutions to the practice tasks given in the exercise. Remember that the output can vary based on the state and the configuration of your file system.

## Task 1: Locate Command Practice

1. **Update the `locate` database:**

```bash
sudo updatedb
```

2. **Find all instances of the `passwd` file:**

```bash
locate passwd
```

3. **Locate `.conf` files related to `httpd`:**

```bash
locate httpd | grep '\.conf$'
```

## Task 2: Find Command - Type and Size Tests

1. **List all directories named `config` within `/etc`:**

```bash
find /etc -type f -name *.conf
```

2. **Find all regular files larger than 5MB not accessed in the last 30 days:**

```bash
find ~/ -type f -size +5M -atime +30
```

3. **Search for all block device files in the `/dev` directory:**

```bash
find /dev -type b
```

## Task 3: Find Command - Pre-existing Tests

1. **Find all empty files within the `/var/log` directory:**

```bash
find /var/log -type f -empty
```

2. **Identify all files modified more than 7 days ago but less than 14 days ago:**

```bash
find /home -type f -mtime +7 -mtime -14
```

3. **Locate files in the `/tmp` directory not owned by the current user:**

```bash
find /tmp -type f ! -user $(whoami)
```

Replace `$(whoami)` with the actual username if necessary.


## Bonus Challenge

**Combine multiple tests to list specific files in `/var/log`:**

```bash
find /var/log -type f -size +10M -mtime -2 ! -path "*/archive/*"
```

This command will find files in `/var/log` that are regular files (`-type f`), larger than 10MB (`-size +10M`), modified within the last two days (`-mtime -2`), and not within any subdirectory named `archive` (`! -path "*/archive/*"`).

The commands provided are based on common file paths and names. If certain files or directories do not exist on the system where these commands are executed, the output will reflect that accordingly.
