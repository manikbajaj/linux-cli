# Solution: Mastering Compression and Archiving in Linux

### Task 1: Zip

**Objective:** Compress the `documents` directory into a file named `documents.zip` and verify its contents.

1. **Navigate to the directory:**

```bash
cd ~/compression-practice
```

2. **Compress the `documents` directory:**

```bash
zip -r documents.zip documents/
```

3. **Verify the contents of the zip file:**

```bash
unzip -l documents.zip
```

### Task 2: Tar

**Objective:** Create a tar archive named `images.tar` containing the `images` directory and verify its contents.

1. **Create a tar archive of the `images` directory:**

```bash
tar -cvf images.tar images/
```

2. **List the contents of the archive:**

```bash
tar -tvf images.tar
```

### Task 3: Bzip2

**Objective:** Compress the `logs` directory using `tar` with `bzip2` compression into a file named `logs.tar.bz2` and confirm the compression.

1. **Compress the `logs` directory with bzip2:**

```bash
tar -cvjf logs.tar.bz2 logs/
```

2. **List the contents of the bzip2 compressed tar file:**

```bash
tar -tvjf logs.tar.bz2
```

### Bonus Task

**Objective:** Compress the entire `compression-practice` directory first into a tar archive and then compress it using `bzip2`.

1. **Create a tar archive of the entire `compression-practice` directory:**

```bash
tar -cvf complete-backup.tar compression-practice/
```

2. **Compress the archive using bzip2:**

```bash
bzip2 complete-backup.tar
```

_Note: The above command will create `complete-backup.tar.bz2` and remove the original `complete-backup.tar`._

The final result of the bonus task will be a bzip2 compressed tar archive named `complete-backup.tar.bz2`.
