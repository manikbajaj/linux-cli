# Practice: Slicing, Dicing and Comparing Text in Linux

In this exercise, you will practice using `cut`, `paste`, `join`, `comm`, `diff`, and `patch` commands to manipulate and compare files. To complete this exercise, follow the instructions step by step and use the commands taught in the course.

### Setup:

1. Create a directory named `exercise` and navigate into it:

   ```bash
   mkdir exercise
   cd exercise
   ```

2. Create the following files with the specified content using `vim`:

   - `names.txt`:
     ```
     Anna
     Bob
     Charlie
     David
     ```
   - `ages.txt`:
     ```
     23
     30
     25
     22
     ```
   - `emails.txt`:
     ```
     anna@example.com
     bob@example.com
     charlie@example.com
     david@example.com
     ```

### Exercises:

1. **Using `cut`**:

   - Extract the first name from `emails.txt` where the names are before the `@` symbol.
   - Create a file `firstnames.txt` containing the extracted first names.

2. **Using `paste`**:

   - Combine `names.txt` and `ages.txt` into a single file `name_ages.txt`, with a tab separating the names and ages.

3. **Using `join`**:

   - Join `names.txt` and `emails.txt` on the name field (assume they are already sorted) and output to `names_emails.txt`.

4. **Using `comm`**:

   - Compare `names.txt` and `firstnames.txt` and identify names that are present in both files. Direct this output to `common_names.txt`.

5. **Using `diff`**:

   - Make some changes to `names.txt` (e.g., add a new name at the end) and save it as `names_modified.txt`.
   - Use the `diff` command to generate a patch file `names.diff` that contains the differences between `names.txt` and `names_modified.txt`.

6. **Using `patch`**:
   - Apply the `names.diff` patch to `names.txt` and revert the changes to ensure `names.txt` goes back to its original state.

#### Deliverables:

- `firstnames.txt` after using `cut`.
- `name_ages.txt` after using `paste`.
- `names_emails.txt` after using `join`.
- `common_names.txt` after using `comm`.
- `names.diff` after using `diff`.
- The original `names.txt` file restored after using `patch`.

Upon completion, you should have a directory structure like this:

```
/exercise
    /names.txt
    /ages.txt
    /emails.txt
    /firstnames.txt
    /name_ages.txt
    /names_emails.txt
    /common_names.txt
    /names_modified.txt
    /names.diff
```

This set of tasks will test your ability to manipulate and compare text files, which is an essential skill for handling data and configuration files in a Linux environment. Good luck!
