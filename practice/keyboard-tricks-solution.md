# Solutions: Keyboard Tricks

## Exercise 1: Bash Readline

1. **Solution to Question 1**:

   - Execute a simple command like `ls`.
   - Press `Ctrl + R` and start typing `ls`.
   - Press `Enter` to re-execute the `ls` command.

2. **Solution to Question 2**:

   - Execute a few commands like `ls`, `pwd`, `echo hello`.
   - Use the `Up` and `Down` arrows to navigate through your history.
   - Choose any command and press `Enter` to execute it.

3. **Solution to Question 3**:
   - Execute any three commands, like `ls`, `pwd`, and `date`.
   - Press `up arrow`.
   - You'll notice that the last command (`date` in this example) will execute again, and the shell will automatically prepare the second last command (`pwd` here) for execution.

---

## Exercise 2: Cursor Movements

1. **Solution to Question 1**:

   - Type `echo This is a long command` but don't execute it.
   - Press `Ctrl + A` to move the cursor to the beginning of the line.
   - Press `Ctrl + E` to move the cursor to the end of the line.

2. **Solution to Question 2**:

   - Type `echo Delete me from the beginning` but don't execute it.
   - Move the cursor to the word `from` and press `Ctrl + U`.

3. **Solution to Question 3**:
   - Type `echo Delete me from the end` but don't execute it.
   - Move the cursor to the word `from` and press `Ctrl + K`.

---

## Exercise 3: Modifying Text

1. **Solution to Question 1**:

   - Type `echo Hello Wrld` but don't execute it.
   - Move the cursor to where `o` should be, between `r` and `l`.
   - Type `o`.

2. **Solution to Question 2**:

   - Type `echo Helloooo World` but don't execute it.
   - Move the cursor to the first extra `o`.
   - Press `Ctrl + K` to delete to the end, then type ` World` and reposition your cursor to complete the command.

3. **Solution to Question 3**:
   - Type `echo "This is a bad example"` but don't execute it.
   - Move the cursor to the word `bad`.
   - Use `Ctrl + K` to delete `bad example`, type `good example`, and then execute.

---

## Exercise 4: Text Completion

1. **Solution to Question 1**:

   - Navigate to a directory with multiple files, say `/usr/bin/`.
   - Type `ls` and then the first few letters of any file, say `ba`.
   - Press `Tab` to auto-complete.

2. **Solution to Question 2**:

   - Again, in `/usr/bin/`, type `ls b` (if multiple files start with `b`).
   - Press `Tab` twice quickly to see a list of all possible completions.

3. **Solution to Question 3**:
   - Type `ls /usr/bi` but don't execute it.
   - Press `Tab` to auto-complete the command to `ls /usr/bin`.
