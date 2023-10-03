# Solution - Customizing The Prompt

## 1. Anatomy of the Prompt:

- To display the current PS1 value:

  ```bash
  echo $PS1
  ```

- Explanation: The `echo` command is used to display the value of the PS1 variable.

- For a commonly seen value like: `\u@\h:\w\$`, it breaks down as:
  - `\u`: Current username
  - `\h`: Hostname up to the first `.`
  - `:`: Literal colon
  - `\w`: Current working directory (full path)
  - `\$`: Displays `$` for regular users and `#` for root.

## 2. Customizing the Prompt:

- Changing the prompt:

  ```bash
  PS1="\w[\t]\u\$ "
  ```

- Explanation: The PS1 variable is being modified to change the prompt structure.
  - `\w`: Represents the current working directory.
  - `[\t]`: Square brackets contain the time in HH:MM:SS format.
  - `\u`: Represents the current username.
  - `\$`: Displays the appropriate prompt character (`$` or `#`).

## 3. Modifying the Color of the Prompt:

- Change the color of the directory to green and time to cyan:

  ```bash
  PS1="\[\e[32m\]\w\[\e[0m\][\[\e[36m\]\t\[\e[0m\]]\u\$ "
  ```

- Explanation: ANSI escape sequences are used here to change the color.
  - `\[\e[32m\]`: Changes text color to green.
  - `\[\e[0m\]`: Resets the text color to default.
  - `\[\e[36m\]`: Changes text color to cyan.
    These sequences are wrapped within `\[ \]` to inform bash that these sequences are non-printing characters. This ensures correct cursor movement.

## 4. Cursor Movement:

- The one-liner:

  ```bash
  echo "Hello World!" && echo -e "\e[A\e[0K"
  ```

- Explanation:

  - `echo "Hello World!"`: Prints "Hello World!" to the screen.
  - `&&`: A command concatenator, runs the second command if the first is successful.
  - `echo -e "\e[A"`: Uses the `-e` flag to interpret escape sequences. `\e[A` moves the cursor up one line.
  - `\e[0K`: Clears the line from the cursor position to the end.

  The combined effect is to print "Hello World!" and then immediately clear it.

## 5. Bonus Task (Advanced):

- Two-line prompt:

  ```bash
  PS1="\t\n\w[\u]\$ "
  ```

- Explanation:

  - `\t`: Displays the current time.
  - `\n`: Moves to a new line.
  - `\w`: Represents the current working directory.
  - `[\u]`: Square brackets contain the username.
  - `\$`: Displays the appropriate prompt character (`$` or `#`).

  This results in a two-line prompt, where the first line displays the time and the second line contains the directory, username, and the prompt symbol.
