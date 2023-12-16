# Solution: Mastering VI Editor

## Solution for Task 1: VI Basics
```shell
# Open VI editor and create a new file named practice_file.txt.
vi practice_file.txt
```
- In the VI editor, enter some random text, numbers, and special characters.
- Save the file by pressing `Esc`, typing `:wq`, and pressing `Enter`.

## Solution for Task 2: Deleting Text in VI
```shell
# Open practice_file.txt in VI editor.
vi practice_file.txt
```
- Navigate to the word you want to delete and type `dw` to delete a word.
- Navigate to the line you want to delete and type `dd` to delete a line.
- To delete a block of text, move to the starting point and press `V`, move to the end point and press `d`.
- Save the changes using `:wq`.

## Solution for Task 3: Cut, Copy, Paste in VI
```shell
# Create a new file named sample_file.txt and open in VI editor.
vi sample_file.txt
```
- Enter some text.
- To cut specific lines, navigate to the line and type `dd`.
- To copy specific lines, navigate to the line and type `yy`.
- Open `practice_file.txt` and navigate to the location where you want to paste the content.
- Type `p` to paste the content after the cursor or `P` to paste before the cursor.
- Save the changes to both files using `:wq`.

## Solution for Task 4: Joining Lines in VI
```shell
# Open practice_file.txt in VI editor.
vi practice_file.txt
```
- Navigate to the line you want to split and enter insert mode by pressing `i`.
- Press `Enter` to create new lines within paragraphs.
- Navigate between the lines you want to join and type `J`.
- Save the changes using `:wq`.

## Solution for Task 5: Search and Replace in VI
```shell
# Open practice_file.txt in VI editor.
vi practice_file.txt
```
- To search for a word, type `/` followed by the word, and press `Enter`.
- To replace a found word with a new word, type `:s/old-word/new-word/` and press `Enter`.
- For a global search and replace, type `:%s/old-word/new-word/g` and press `Enter`.
- Save the changes using `:wq`.

## Solution for Task 6: Working with Multiple Files in VI
```shell
# Open both practice_file.txt and sample_file.txt in VI editor.
vi practice_file.txt sample_file.txt
```
- To switch between the files, type `:n` to move to the next file and `:N` to move to the previous file.
- Make the necessary edits in both files.
- Save the changes to both files using `:wa`.
