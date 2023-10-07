# Solution - Storage Management

---

## **1. Drive Identification**:

```bash
lsblk
```

From the output, identify your USB drive (for this solution, we'll assume it's `/dev/sdb`).

---

## **2. Unmount the Drive**:

To unmount the drive (assuming it's mounted):

```bash
sudo umount /dev/sdb1
sudo umount /dev/sdb2
```

---

## **3. Format the Drive with `fdisk`**:

Start the `fdisk` utility:

```bash
sudo fdisk /dev/sdb
```

Delete any existing partitions (assuming two partitions exist):

```bash
d
1
d
```

Create the first partition (8GB):

```bash
n
p
1
[Enter]
+8G
```

Create the second partition with the remaining space:

```bash
n
p
2
[Enter]
[Enter]
```

Write changes and exit:

```bash
w
```

---

## **4. Create New File Systems**:

Format the first partition with `ext4`:

```bash
sudo mkfs.ext4 /dev/sdb1
```

Format the second partition with `ntfs`:

```bash
sudo mkfs.ntfs /dev/sdb2
```

---

## **5. Mount the Drive**:

Create mount points:

```bash
sudo mkdir /mnt/part1
sudo mkdir /mnt/part2
```

Mount the partitions:

```bash
sudo mount /dev/sdb1 /mnt/part1
sudo mount /dev/sdb2 /mnt/part2
```

---

## **6. Verification**:

List mounted drives:

```bash
df -h
```

Ensure that `/dev/sdb1` is mounted on `/mnt/part1` and `/dev/sdb2` on `/mnt/part2`.

Create test files:

```bash
echo "This is a test for ext4 partition" | sudo tee /mnt/part1/testfile.txt
echo "This is a test for ntfs partition" | sudo tee /mnt/part2/testfile.txt
```

Check if files were created:

```bash
cat /mnt/part1/testfile.txt
cat /mnt/part2/testfile.txt
```

---

## **Conclusion**:

By following these steps, you should have successfully formatted your USB drive with two partitions and verified its writability. Always ensure to follow the commands carefully to avoid accidental data loss.
