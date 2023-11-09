# Practice: Text Editing

Here is a practice exercise incorporating `tr`, `sed`, and `aspell` for your Linux command line course:

### Practice Exercise: Text Processing and Spell Checking

**Scenario:**
You have a text file named `draft.txt` that contains website content written by a non-native English speaker. The file has several formatting inconsistencies and potential spelling errors. Your task is to clean up the file and correct the spelling.

**Tasks:**

1. **Normalization with `tr`:**

   - The file uses a mix of uppercase and lowercase inconsistently. Use `tr` to convert all text in `draft.txt` to lowercase.
   - The file contains windows style line endings. Convert all Windows line endings (CRLF) to Unix line endings (LF).

2. **Formatting with `sed`:**

   - The text uses the British spelling of 'colour'. Convert this to the American spelling 'color'.
   - Every instance of 'website' is mistakenly written as 'web site'. Use `sed` to correct this.

3. **Spell Checking with `aspell`:**
   - Check `draft.txt` for spelling mistakes and correct them interactively.
   - Save the corrected file as `final.txt`.

**Initial `draft.txt` Content (Use `vim` to create this file):**

```
WElCOME to the COLOurFUL WEBSITE.

We are commited to providing you with the best web site experience possible. Our web site features a wide range of prodcts and services.

Please don't hesitate to conact us with your questions.
```

**Instructions:**

1. Open the terminal.
2. Use `vim` to create `draft.txt` and insert the provided content.
3. Perform the normalization task using `tr`. Remember to direct the output to a new file or overwrite the original.
4. Use `sed` to make the required text replacements.
5. Finally, run `aspell` to interactively check and correct the spelling of the modified file.

**Expected Results:**

After completing the tasks, the content of `final.txt` should look like this:

```
welcome to the colorful website.

we are committed to providing you with the best website experience possible. our website features a wide range of products and services.

please don't hesitate to contact us with your questions.
```

**Hints:**

- You can use `tr '[A-Z]' '[a-z]' < draft.txt > temp.txt` and `mv temp.txt draft.txt` to convert to lowercase.
- Use `tr -d '\r' < draft.txt > temp.txt` to convert CRLF to LF.
- For `sed`, you can chain commands like `sed -e 's/colour/color/g' -e 's/web site/website/g' draft.txt > temp.txt`.
- `aspell check draft.txt` will start an interactive spell-checking session.
