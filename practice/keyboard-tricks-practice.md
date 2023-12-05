# Practice Exercise: Keyboard Tricks

## Objective

The aim of this exercise is to provide hands-on practice with various aspects of the Linux command line, including Bash Readline, cursor movements, text modifications, and text completion.

---

### Pre-requisites

- A Linux environment to practice commands (you can use a virtual machine, a local setup, or an online terminal).

---

## Exercise 1: Bash Readline

1. **Question 1**: Execute a command of your choice. Use reverse search (`Ctrl + R`) to find and re-execute this command.

2. **Question 2**: Navigate through your command history using the Up and Down arrows. Choose a command and execute it.

3. **Question 3**: Execute any three commands. Use `up arrow` to cycle through and execute these commands again. Observe what happens.

---

## Exercise 2: Cursor Movements

1. **Question 1**: Type a long command but do not execute it. Use `Ctrl + A` and `Ctrl + E` to navigate to the beginning and end of the line, respectively.

2. **Question 2**: Again, type a long command. Use `Ctrl + U` to delete text from the cursor to the beginning of the line.

3. **Question 3**: Type another long command. Use `Ctrl + K` to delete text from the cursor to the end of the line.

---

## Exercise 3: Modifying Text

1. **Question 1**: Type `echo Hello Wrld`. Move your cursor to where the letter `o` in `Wrld` should be and insert it.

2. **Question 2**: Type `echo Helloooo World` and then modify it to `echo Hello World` by deleting extra `o`s without using the `Backspace` key for each character.

3. **Question 3**: Type `echo "This is a bad example"`. Change the word `bad` to `good` using text modification shortcuts.

---

## Exercise 4: Text Completion

1. **Question 1**: Navigate to a directory where you have multiple files and folders. Type the first few letters of a file or directory name and use `Tab` for auto-completion.

2. **Question 2**: Try using `Tab` twice in quick succession to list possible completions when multiple files start with the same letters.

3. **Question 3**: Type the command `ls /usr/bi` and use `Tab` to auto-complete it to `ls /usr/bin`.
