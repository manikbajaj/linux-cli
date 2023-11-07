# Solution: Text Processing in Linux

### Step 1: Using `cut`

To extract the first names from `emails.txt` where the names are before the `@` symbol, you can use the `cut` command. The `-d` option specifies the delimiter, and the `-f` option specifies the field to be cut out.

```bash
cut -d'@' -f1 emails.txt > firstnames.txt
```

- `-d'@'` tells `cut` to use the `@` symbol as a delimiter.
- `-f1` selects the first field, which is the text before the `@`.

The result is redirected to `firstnames.txt`.

### Step 2: Using `paste`

To combine `names.txt` and `ages.txt` with a tab separating the names and ages, you can use `paste`:

```bash
paste names.txt ages.txt > name_ages.txt
```

- `paste` is used to merge lines of files side by side and is separated by a tab by default.

### Step 3: Using `join`

To join `names.txt` and `emails.txt` on the name field:

```bash
join names.txt emails.txt > names_emails.txt
```

- `join` combines the lines from two files based on a common field. By default, it uses the first field of each file and assumes the files are sorted on the join field.

### Step 4: Using `comm`

To compare `names.txt` and `firstnames.txt` and find common names:

```bash
comm -12 names.txt firstnames.txt > common_names.txt
```

- `comm` compares two sorted files line by line.
- The `-12` option suppresses lines unique to `names.txt` (column 1) and lines unique to `firstnames.txt` (column 2), only printing lines common to both files (which would appear in column 3).

### Step 5: Using `diff`

To generate a patch file from the differences between `names.txt` and `names_modified.txt`:

First, modify `names.txt`:

```bash
vim names_modified.txt
```

Add a new name and save the changes.

Then create the diff:

```bash
diff -u names.txt names_modified.txt > names.diff
```

- `diff -u` creates a unified diff, which is a format that shows lines of context around the changes and is required for `patch`.

### Step 6: Using `patch`

To apply the patch file and then revert the changes:

```bash
patch names.txt names.diff
# Now revert
patch -R names.txt names.diff
```

- The first `patch` command applies the changes in `names.diff` to `names.txt`.
- The `-R` option reverses the patch, undoing the changes.
