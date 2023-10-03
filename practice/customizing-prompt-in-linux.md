# Practice Exercise - Customizing The Prompt

**Objective:** The aim of this exercise is to test and enhance your understanding of various aspects related to the Linux command-line prompt. This includes the anatomy of the prompt, customizing the information displayed, modifying its color, and manipulating the cursor.

## Exercise Instructions:

1. **Anatomy of the Prompt:**

   - Display the current PS1 value and take note of its structure. Write down what each segment of the PS1 variable represents in your current prompt.
   - Explain the meaning of any special characters or escape sequences you find.

2. **Customizing the Prompt:**

   - Change your prompt to display the current working directory (`\w`), followed by the time in HH:MM format (`\t`), and then your username. It should look something like this: `[directory][time]username$`

3. **Modifying the Color of the Prompt:**

   - Change the color of the directory in your prompt to green.
   - Change the color of the time to cyan.
   - Ensure the username remains in the default color.

   Hint: Use ANSI escape codes to achieve this.

4. **Cursor Movement:**

   - Write a one-liner command that does the following:
     - Prints "Hello World!" to the screen.
     - Moves the cursor up one line.
     - Moves the cursor to the beginning of the line.
     - Clears the line.
     - Now, type out the reason for the observed output.

5. **Bonus Task (Advanced):**

   - Incorporate an element into your prompt that moves the cursor to create a two-line prompt, where the first line displays the time and the second line contains the rest of the prompt. This means every time you enter a command, the command itself starts on a new line, just below the time.

**Note:** Always remember to revert any permanent changes (like modifications to `~/.bashrc`) if they are not desired beyond this exercise.
