# Solution: Mastering Redirection

### Solution for Task 1: Redirecting stdout

**Objective**: Redirect the output of the `ls` command to a file named `filelist.txt`.

```bash
ls > filelist.txt
```

This will execute the `ls` command and store its output (stdout) into a file named `filelist.txt`.

---

### Solution for Task 2: Redirecting stderr

**Objective**: Attempt to `cat` a non-existent file and redirect the error message to a file named `error.txt`.

```bash
cat non_existent_file 2> error.txt
```

In this case, `2>` redirects the standard error (stderr) to `error.txt`.

---

### Solution for Task 3: Redirecting stdout and stderr to different files

**Objective**: Run a command that will produce both stdout and stderr and redirect them into two different files (`output.txt` for stdout and `error.txt` for stderr).

```bash
ls existing_file non_existent_file > output.txt 2> error.txt
```

Here, stdout is redirected to `output.txt`, and stderr is redirected to `error.txt`.

---

### Solution for Task 4: Redirecting stdin

**Objective**: Use the `wc` command to count the number of words in a sentence provided via stdin redirection.

First, create a file named `sentence.txt` and put some text in it:

```bash
echo "This is a sample sentence for the word count exercise." > sentence.txt
```

Now, run the `wc` command to count the words:

```bash
wc -w < sentence.txt
```

Here, `<` redirects the stdin to read from `sentence.txt`. The `wc -w` command then counts the number of words.

---

### Solution for Task 5: Redirection Order

**Objective**: Redirect both stdout and stderr to a single file, `all_output.txt`.

You can achieve this in two different ways, as mentioned:

1. Redirect stderr to stdout, then redirect stdout to a file:

   ```bash
   ls existing_file non_existent_file > all_output.txt 2>&1
   ```

2. Redirect stdout to a file, then redirect stderr to stdout:

   ```bash
   ls existing_file non_existent_file 2>&1 > all_output.txt
   ```

**Note**: In the first approach, stdout is saved first and then stderr is appended to the same output. In the second approach, since the stderr is pointed to stdout before stdout is redirected to the file, both stdout and stderr will be saved to `all_output.txt`.
