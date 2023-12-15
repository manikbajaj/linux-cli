# Solution: Modifying the `.bashrc` File in Ubuntu

## Step 1: Open the `.bashrc` File

Open a terminal and type the following command to edit the `.bashrc` file with a text editor like `nano`. You can replace `nano` with your preferred editor.

```sh
nano ~/.bashrc
```

## Step 2: Modify the `.bashrc` File

Navigate to the end of the file and add the following lines. Remember to add comments to describe each change for future reference.

```sh

# Ignoring duplicate commands in the history
export HISTCONTROL=ignoredups

# Setting the maximum number of commands in the history to 1000
export HISTSIZE=1000

# Creating an alias to list only hidden files with colorized output
alias l.='ls -d .* --color=auto'

# Creating an alias for long format listing of files with colorized output
alias ll='ls -l --color=auto'
```

## Step 3: Save and Exit

After adding the modifications, save the file and exit the editor. If you are using `nano`, you can do this by pressing `CTRL + X`, then `Y` to confirm the changes, and finally `Enter` to exit.

## Step 4: Apply the Changes

To apply the modifications, either close and reopen your terminal or type the following command:

```sh
source ~/.bashrc
```

## Verification and Usage

After applying the changes, you can verify them by:

- Creating a new file and checking its permissions to see if the `umask 0002` setting is effective.
- Typing the same command multiple times and viewing the history by typing `history` to verify if `export HISTCONTROL=ignoredups` is working.
- Counting the number of commands in the history to check the effectiveness of `export HISTSIZE=1000`.
- Using the new aliases `l.` and `ll` to see if they list the files as intended.
