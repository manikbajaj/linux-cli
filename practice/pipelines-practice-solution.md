# Solution: Mastering Pipelines and Filters

### Solution for Task 1: Simple Pipeline

**Objective**: Use the `ls` command and pipe its output to `wc` to count the number of files and directories in the current directory.

**Solution**:

```bash
ls | wc -l
```

This will list all the files and directories and pipe the output to `wc -l` to count the number of lines, effectively giving the number of items in the directory.

---

### Solution for Task 2: grep with Pipeline

**Objective**: List all files and directories in the current directory and use `grep` to filter out items that contain the word "test".

**Solution**:

```bash
ls | grep -v 'test'
```

Here, `grep -v 'test'` will filter out lines containing the word 'test'.

---

### Solution for Task 3: uniq and sort with Pipeline

**Objective**: Create a text file called `names.txt` containing multiple names, some of them repeating. Use `sort` and `uniq` to display a sorted list of unique names.

**Solution**:

```bash
sort names.txt | uniq
```

This will sort the names in `names.txt` and then remove any duplicates with `uniq`.

---

### Solution for Task 4: Count Lines using wc and Pipeline

**Objective**: Count the number of lines in the `names.txt` file using `wc`.

**Solution**:

```bash
wc -l names.txt
```

This command will display the number of lines in `names.txt`, which should represent the total count of names.

---

### Solution for Task 5: Combining Multiple Filters

**Objective**: Use a combination of `sort`, `uniq`, and `wc` to count the number of unique names in the `names.txt` file.

**Solution**:

```bash
sort names.txt | uniq | wc -l
```

This chain of commands sorts the names, removes duplicates, and then counts the number of unique names.

---

### Solution for Task 6: Using head and tail

**Objective**: Display the first 5 and last 5 lines of the `names.txt` file.

**Solution**:

```bash
# For displaying the first 5 lines
head -n 5 names.txt

# For displaying the last 5 lines
tail -n 5 names.txt
```

The `head` command will show the first 5 lines, and the `tail` command will show the last 5 lines of `names.txt`.
