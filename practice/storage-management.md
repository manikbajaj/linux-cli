# Practice Exercise - Storage Management

## Objective:

Apply your knowledge of managing drives and file systems in Linux. This exercise will guide you through a series of tasks to help solidify your understanding of mounting, unmounting, formatting drives, and creating new file systems.

---

## Scenario:

You are provided with an external USB drive that contains some old data. Your task is to prepare this drive for a new project. You need to ensure that the drive has two partitions: one formatted with `ext4` and the other with `ntfs`.

---

## Tasks

### 1. **Drive Identification**:

- Use necessary commands to list all connected drives and identify your USB drive (assume it's `/dev/sdb` for this exercise).

### 2. **Unmount the Drive**:

- Ensure that your drive is not currently mounted. If it is, unmount it.

### 3. **Format the Drive with `fdisk`**:

- Start the `fdisk` utility for your drive.
- Delete any existing partitions on the drive.
- Create two new partitions:
  - The first partition should be 8GB.
  - Use the remaining space for the second partition.
- Write changes and exit `fdisk`.

### 4. **Create New File Systems**:

- Format the first partition with an `ext4` file system.
- Format the second partition with an `ntfs` file system.

### 5. **Mount the Drive**:

- Create two mount points: `/mnt/part1` and `/mnt/part2`.
- Mount the first partition (`ext4`) at `/mnt/part1`.
- Mount the second partition (`ntfs`) at `/mnt/part2`.

### 6. **Verification**:

- List the mounted drives and ensure your partitions are mounted correctly.
- Create a test file in each partition to ensure they are writable.

---

**Hints**:

- Remember to use `sudo` where necessary.
- Always double-check your drive's path (`/dev/sdb` in this exercise) to avoid any data loss.

---

Good luck! Remember, the key is to apply the knowledge you've learned, and it's okay to refer back to your notes or research further if you're unsure about any steps.
