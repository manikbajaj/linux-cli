# Practice Exercise: Quoting and Escaping

## Objective

This exercise aims to solidify your understanding of quoting and escaping in the Linux command line. You will get hands-on practice with single quotes, double quotes, escape characters, and escape sequences.

## Prerequisites

- A working Linux terminal
- Basic understanding of shell commands

---

## Exercise Questions

### Quoting

1. **Double Quotes**: Write a command using `echo` to print the following string exactly as it appears: `The value of $HOME is: /home/username`

2. **Single Quotes**: Again, using `echo`, print the string `That's all, folks!` to the terminal.

### Double Quotes vs Single Quotes

3. Create a variable called `greeting` with the value `"world"`. Write two `echo` statements, one using single quotes and another using double quotes, to print "Hello, world!" by referencing the `greeting` variable.

### Escape Characters

4. Use `echo` to print a string that includes a double quote (`"`) character. The string should read: `She said, "Hello, world!"`

5. Again using `echo`, print the following string on a single line: `First Line. Second Line.` Hint: Use an escape character to indicate where the new line would have been.

### Escape Sequences

6. Use `echo` to print a tab-indented list of fruits like this:

   ```
   Apple
       Banana
       Cherry
   ```

7. Create a text file using the `echo` command that includes a form feed character. Name the file `page_break.txt`.

8. Using `echo`, print a bell sound.
