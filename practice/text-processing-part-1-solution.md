# Solution: Text Processing in Linux

### Task 1: View File Content

**Command:**

```bash
cat sales.txt
```

**Explanation:**
The `cat` command is used to concatenate and display the content of files. In this case, it simply displays the content of `sales.txt` in the terminal.

### Task 2: Sort Data Alphabetically by Fruit Name

**Command:**

```bash
sort sales.txt > sorted_sales.txt
```

**Explanation:**
This `sort` command organizes the lines in `sales.txt` alphabetically. The `>` operator is used to redirect the sorted output to a new file called `sorted_sales.txt` instead of displaying it on the terminal.

### Task 3: Identify Unique Entries

**Command:**

```bash
uniq sorted_sales.txt > unique_sales.txt
```

**Explanation:**
The `uniq` command is used to report or filter out repeated lines in a file. It requires that the input is sorted. Since `sorted_sales.txt` is already sorted, `uniq` will remove duplicate adjacent lines and the result is saved into `unique_sales.txt`.

### Task 4: Count Item Occurrences

**Command:**

```bash
sort sales.txt | cut -d ',' -f 1 | uniq -c
```

**Explanation:**
This is a pipeline of commands. The `sort` command first sorts the file. The `cut` command is then used with `-d ','` to specify the delimiter as a comma, and `-f 1` to select the first field, which is the fruit name. The `uniq -c` command then counts the number of occurrences of each unique line. Because the lines are sorted, `uniq` can accurately count the occurrences.

### Task 5: Sort by Quantity

**Command:**

```bash
sort -t ',' -k2 -n sales.txt
```

**Explanation:**
The `sort` command is used with the `-t ','` option to specify the comma as the field separator, and `-k2` to indicate that sorting should be based on the second field, which is the quantity. The `-n` option specifies that the sort should be numerical rather than alphabetical, which is important for sorting numbers correctly.

### Task 6: Find the Most Sold Item

**Command:**

```bash
sort -t ',' -k2 -n sales.txt | tail -1
```

**Explanation:**
This command chain first sorts the items numerically by quantity as in the previous task. Then, `tail -1` is used to get the last entry of the sorted data, which corresponds to the item with the highest quantity sold, because the list is sorted in ascending order.

### Bonus Challenge: Ranked List of Fruits by Total Quantity Sold

**Command:**

```bash
awk -F ',' '{ fruit[$1] += $2 } END { for (f in fruit) print f, fruit[f] }' sales.txt | sort -k2 -nr
```

**Explanation:**
In this `awk` script, `-F ','` sets the field separator to a comma. In the main block, `fruit[$1] += $2` creates an associative array `fruit` where each fruit name is a key and the values are the sum of the second field across the dataset. In the `END` block, it iterates over the `fruit` array to print each fruit with its total quantity. The output is then piped into `sort` with `-k2` to sort based on the second field (the total quantity), `-n` for numerical sort, and `-r` to reverse the order, resulting in a list from most to least sold quantities.
