**Basic Linux Commands for Day-to-Day Usage**.

---

### **Introduction to Linux Commands**

- **What are Linux Commands?**
  - Instructions that users can give to the Linux operating system through the command line interface (CLI).
  - Essential for navigating, managing files, and interacting with the system.

---

### **Navigating Directories**

- **pwd (Print Working Directory)**  
  Displays the current directory you're in.

  ```bash
  $ pwd
  ```

  _Example output:_ `/home/user`

- **ls (List)**  
  Lists files and directories in the current directory.

  ```bash
  $ ls
  ```

  _Example output:_ `Documents/  Downloads/  Pictures/`

- **cd (Change Directory)**  
  Changes the current directory.
  ```bash
  $ cd /home/user/Documents
  ```

---

### **Managing Files**

- **touch**  
  Creates an empty file or updates a file's timestamp.

  ```bash
  $ touch newfile.txt
  ```

- **cp (Copy)**  
  Copies files or directories.

  ```bash
  $ cp file1.txt /home/user/Backup/
  $ cp -r /home/user/Documents/project /home/user/Backup/
  ```

- **mv (Move/Rename)**  
  Moves or renames files or directories.

  ```bash
  $ mv oldname.txt newname.txt
  ```

- **rm (Remove)**  
  Deletes files and folders.
  ```bash
  $ rm file1.txt
  $ rm -rf folder/
  ```

---

### **Viewing File Content**

- **cat**  
  Displays the contents of a file.

  ```bash
  $ cat file.txt
  ```

- **less**  
  View file content one screen at a time.

  ```bash
  $ less largefile.txt
  ```

- **head / tail**  
  Shows the first/last 10 lines of a file.
  ```bash
  $ head file.txt
  $ tail file.txt
  ```

---

### **System Monitoring Commands**

- **top**  
  Displays a real-time view of running processes.

  ```bash
  $ top
  ```

- **df (Disk Free)**  
  Shows available disk space on file systems.

  ```bash
  $ df -h
  ```

- **free**  
  Displays available and used memory.
  ```bash
  $ free -h
  ```

---

### **Searching & Finding Files**

- **find**  
  Search for files in a directory hierarchy.

  ```bash
  $ find /home/user -name "file.txt"
  ```

- **grep**  
  Searches for a pattern within files.
  ```bash
  $ grep "error" logfile.txt
  ```

---

### **Basic Networking Commands**

- **ping**  
  Checks the connectivity to another machine.

  ```bash
  $ ping google.com
  ```

- **ifconfig / ip**  
  Displays or configures network interfaces.
  ```bash
  $ ifconfig
  $ ip addr show
  ```

---

### **File Permissions**

- **chmod**  
  Changes file or directory permissions.

  ```bash
  $ chmod 755 script.sh
  ```

- **chown**  
  Changes file ownership.
  ```bash
  $ chown user:user file.txt
  ```

---

### **Package Management (Ubuntu Example)**

- **apt-get update**  
  Updates the package lists.

  ```bash
  $ sudo apt-get update
  ```

- **apt-get install**  
  Installs a package.
  ```bash
  $ sudo apt-get install vim
  ```

---

## Explore further

1. [More on `ls` and `cp`](file/ls-and-cp.md)
2. [File Permissions](file/permissions.md)
