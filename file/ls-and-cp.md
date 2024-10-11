
### **Common `ls` Options**

- **1. `ls -l` (Long Format)**  
  Displays detailed information about files, including permissions, owner, size, and last modified date.

  ```bash
  $ ls -l
  ```

  _Example output:_  
  `-rw-r--r-- 1 user user 4096 Oct 11 10:15 file.txt`

- **2. `ls -a` (All Files)**  
  Lists all files, including hidden files (files starting with `.`).

  ```bash
  $ ls -a
  ```

  _Example output:_  
  `.bashrc  .hiddenfile  Documents/`

- **3. `ls -h` (Human-Readable Format)**  
  Displays file sizes in human-readable format (e.g., KB, MB).

  ```bash
  $ ls -lh
  ```

  _Example output:_  
  `-rw-r--r-- 1 user user 4.0K Oct 11 10:15 file.txt`

- **4. `ls -r` (Reverse Order)**  
  Lists files and directories in reverse order.

  ```bash
  $ ls -r
  ```

  _Example output:_  
  `Videos/  Pictures/  Downloads/  Documents/`

- **5. `ls -t` (Sort by Modification Time)**  
  Sorts files by their modification time, with the most recently modified files appearing first.

  ```bash
  $ ls -lt
  ```

  _Example output:_  
  `-rw-r--r-- 1 user user 4096 Oct 11 10:15 recent.txt`

- **6. `ls -S` (Sort by Size)**  
  Sorts files by size, with the largest files displayed first.
  ```bash
  $ ls -lS
  ```

---

To copy a folder in Linux, you can use the `cp` command with the `-r` (recursive) option. Here's how it works:

---

### **Copying a Folder in Linux**

- **Basic Syntax**:

  ```bash
  cp -r <source_folder> <destination>
  ```

- **Key Option**:
  - **`-r` or `--recursive`**: This tells `cp` to copy all files and subdirectories inside the folder recursively.

---

### **Examples of Copying a Folder**

1. **Copy a folder to another location**:

   ```bash
   cp -r /home/user/Documents/project /home/user/Backup/
   ```

   _This will copy the `project` folder and all its contents to the `Backup` directory._

2. **Copy a folder and rename it**:

   ```bash
   cp -r /home/user/Documents/project /home/user/Backup/project_copy
   ```

   _This will copy the `project` folder and rename the copied version to `project_copy` in the `Backup` directory._

3. **Copy a folder to the current directory**:
   ```bash
   cp -r /home/user/Documents/project .
   ```
   _This will copy the `project` folder from `/Documents` to the current working directory._

---
