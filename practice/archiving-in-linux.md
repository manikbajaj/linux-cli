# Practice: Mastering Compression and Archiving in Linux

## Objective:

The aim of this exercise is to provide hands-on practice with the `zip`, `tar`, and `bzip2` commands in Linux. This will help solidify your understanding of file compression and archiving techniques on a Linux system.

### Prerequisites:

- Access to a Linux terminal.
- Basic knowledge of Linux file system navigation.
- Familiarity with the `zip`, `tar`, and `bzip2` commands.

## Exercise Setup:

First, let's create a set of directories and files that will be used throughout this practice session.

```bash
mkdir -p ~/compression-practice/{documents,images,logs}
echo "Sample text for document 1" > ~/compression-practice/documents/doc1.txt
echo "Sample text for document 2" > ~/compression-practice/documents/doc2.txt
convert -size 100x100 xc:blue ~/compression-practice/images/image1.png
convert -size 100x100 xc:red ~/compression-practice/images/image2.png
echo "Log file entry 1" > ~/compression-practice/logs/log1.log
echo "Log file entry 2" > ~/compression-practice/logs/log2.log
```

**Note:** This setup assumes you have the `convert` utility from ImageMagick to create image files. If it's not installed, you can either install ImageMagick via your package manager or simply create text files in the images directory.

## Exercise Tasks:

### Task 1: Zip

1. Navigate to the `~/compression-practice` directory.
2. Use the `zip` command to compress the `documents` directory into a file named `documents.zip`.
3. Verify the contents of `documents.zip` without extracting them.

### Task 2: Tar

1. In the `~/compression-practice` directory, create a tar archive named `images.tar` containing the `images` directory.
2. List the contents of `images.tar` to verify the archive's integrity.

### Task 3: Bzip2

1. Compress the `logs` directory using `tar` with `bzip2` compression into a file named `logs.tar.bz2`.
2. Ensure that you list the contents of the `logs.tar.bz2` to confirm the compression.

### Bonus Task:

Combine the knowledge of all three commands to compress the entire `compression-practice` directory first into a tar archive and then compress it using `bzip2`. Name the final compressed file `complete-backup.tar.bz2`.

---

**Hint for Zip Task:**

- To compress: `zip -r documents.zip documents/`
- To list contents: `unzip -l documents.zip`

**Hint for Tar Task:**

- To create an archive: `tar -cvf images.tar images/`
- To list contents: `tar -tvf images.tar`

**Hint for Bzip2 Task:**

- To compress with `bzip2`: `tar -cvjf logs.tar.bz2 logs/`
- To list contents: `tar -tvjf logs.tar.bz2`
