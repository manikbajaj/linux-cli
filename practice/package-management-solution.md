# Solution - Linux Package Management

## Task 1: Searching for Packages

1. To search for the package `git`:

   ```bash
   apt search git
   ```

2. To search for the package `nodejs`:
   ```bash
   apt search nodejs
   ```

## Task 2: Installing Packages

1. To install the package `git`:

   ```bash
   sudo apt install git
   ```

2. To search for and install `vim`:

   ```bash
   apt search vim
   sudo apt install vim
   ```

3. To search for and install `curl`:
   ```bash
   apt search curl
   sudo apt install curl
   ```

## Task 3: Listing Installed Packages

1. To list all the installed packages:

   ```bash
   dpkg --list
   ```

2. To identify if `wget` is installed:
   ```bash
   dpkg --list | grep wget
   ```

## Task 4: Updating Packages

1. To update the package list:

   ```bash
   sudo apt update
   ```

2. To upgrade all packages:

   ```bash
   sudo apt upgrade
   ```

3. To specifically check and update `curl`:
   ```bash
   sudo apt install --only-upgrade curl
   ```

## Task 5: Removing Packages

1. To remove `vim`:

   ```bash
   sudo apt remove vim
   ```

2. To remove `nano` (if installed):

   ```bash
   sudo apt remove git
   ```

3. To list and ensure the packages were removed:
   ```bash
   dpkg --list | grep vim
   dpkg --list | grep nano
   ```

## Task 6: Clean-up

1. To fully purge `vim`:

   ```bash
   sudo apt purge vim
   ```

2. To remove unnecessary packages:
   ```bash
   sudo apt autoremove
   ```

---

Students should compare their steps and commands with this solution guide to evaluate their understanding and performance.
