# Solution: Mastering Shell Expansions

Certainly! Below are the solutions for each task in your practice exercise on shell expansions in the Linux command line.

---

### Solution for Task 1: Simple Expansion

**Objective**: Use simple expansion to echo the current user and home directory.

**Solution**:

```bash
echo "Current user: $USER, Home directory: $HOME"
```

This command uses variable expansion to print the current username and home directory.

---

### Solution for Task 2: Pathname Expansion

**Objective**: Use pathname expansion to list all `.txt` files in the current directory.

**Solution**:

```bash
ls *.txt
```

Using the `*` wildcard, this command lists all `.txt` files in the current directory.

---

### Solution for Task 3: Tilde Expansion

**Objective**: Use tilde expansion to navigate to the home directory and then to a sub-directory `Documents` within it, all in a single command.

**Solution**:

```bash
cd ~/Documents
```

The tilde (`~`) expands to the home directory, so this command changes the current working directory to `Documents` within the home directory.

---

### Solution for Task 4: Brace Expansion

**Objective**: Create directories for each week in a course that lasts 12 weeks. The directories should be named `Week1`, `Week2`, ..., `Week12`.

**Solution**:

```bash
mkdir Week{1..12}
```

Brace expansion makes it easy to create multiple directories with a single command. This creates 12 directories, from `Week1` to `Week12`.

---

### Solution for Task 5: Pathname Expansion (Advanced)

**Objective**: List all `.txt` and `.pdf` files in the current directory using pathname expansion.

**Solution**:

```bash
ls *.{txt,pdf}
```

This command uses brace expansion within pathname expansion to list all files that have either a `.txt` or `.pdf` extension.

---

### Solution for Task 6: Parameter Expansion

**Objective**: Create a variable named `greeting` with the value `Hello`. Use parameter expansion to echo the value of this variable.

**Solution**:

```bash
greeting="Hello"
echo $greeting
```

This sets a variable `greeting` with the value "Hello" and then uses parameter expansion to echo its value.
