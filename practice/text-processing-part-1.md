# Practice: Text Processing in Linux

In this exercise, you'll consolidate your understanding of the `cat`, `sort`, and `uniq` commands. You will simulate a common scenario where you need to process a dataset to find unique entries and understand their distribution. Let's pretend we're working with a dataset that lists fruits and their quantities sold on a particular day in a grocery store.

### Exercise Setup

1. **Create a Data File**: Use `vim` to create a file named `sales.txt`:

   ```bash
   vim sales.txt
   ```

   Insert the following data into the file:

   ```plaintext
   apple,10
   banana,5
   apple,15
   orange,7
   banana,8
   apple,10
   cherry,12
   banana,5
   cherry,12
   orange,7
   ```

   Save the file and exit (`Esc`, `:wq`, `Enter`).

### Tasks

1. **View File Content**:

   - Use the `cat` command to display the contents of `sales.txt`.

2. **Sort Data**:

   - Sort the contents of the file alphabetically by fruit name using the `sort` command. Output the result to a new file called `sorted_sales.txt`.

3. **Identify Unique Entries**:

   - Use `uniq` to filter `sorted_sales.txt` to show unique lines. Save the output to `unique_sales.txt`.

4. **Count Item Occurrences**:

   - Use `sort` and `uniq` together to count how many times each fruit appears in the `sales.txt`. Remember to sort the file first before using `uniq` to count the occurrences.

5. **Sort by Quantity**:

   - Sort the `sales.txt` file numerically by the quantity (the second field in each line) and display the result in the terminal.

6. **Find the Most Sold Item**:
   - Chain `sort` and `uniq` commands to find the most sold item. You will need to think about how to use the sort options to arrange the quantities in the correct order and how `uniq` can be used to aggregate quantities.

### Instructions

- Use pipes `(|)` to chain commands together where appropriate.
- Redirect output to files when instructed to do so.
- Feel free to use the `man` command to explore more options for each command.
- Ensure that when you're counting occurrences or sorting by quantities, you're using the appropriate options to consider only the relevant data (you might need to sort and then cut the quantity field, for example).

### Expected Outputs

You need to create commands that produce the following outputs (they will be checked against these criteria):

1. A file with all sales sorted alphabetically by fruit.
2. A file with only unique sales entries.
3. A terminal output showing each fruit followed by the number of times it appears in the list.
4. A terminal output showing all sales sorted by the quantity in ascending order.
5. A terminal output displaying the most sold item's line from the `sales.txt` file.

### Bonus Challenge

If you complete the main tasks quickly, try this bonus challenge:

- Combine the use of `cat`, `sort`, `uniq`, and other commands like `grep` or `awk` to produce a ranked list of fruit by the total quantity of each sold, from most to least.

This exercise will help you to get comfortable with manipulating text data on the command line, an essential skill for any Linux user, especially those who work with logs, datasets, or any other kind of text data.
