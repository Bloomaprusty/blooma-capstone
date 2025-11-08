# 🧭 File Explorer Application (Linux OS)

## 📘 Objective
Develop a **console-based file explorer application in C++** that interfaces with the Linux operating system to manage files and directories.  
This project demonstrates the use of Linux system calls (`opendir`, `readdir`, `stat`, `chmod`, etc.) to perform essential file operations through a text-based user interface.

---

## 🗓️ Day-wise Development Tasks

### **Day 1 – Application Structure & Setup**
- Designed the console-based structure of the application.
- Set up the development environment using **C++ and Linux terminal**.
- Implemented basic file operations:
  - **Listing files and directories** in the current path.

### **Day 2 – Directory Navigation**
- Added functionality to navigate directories.
- Enabled the program to read files/folders using the `dirent.h` library.
- Used system calls to traverse and display file information dynamically.

### **Day 3 – File Manipulation Features**
Implemented core file operations:
- **Copy File** – Duplicates a file from source to destination.
- **Move File** – Relocates a file to a new path.
- **Delete File** – Removes the specified file.
- **Create File** – Generates a new empty file.

### **Day 4 – File Search Functionality**
- Added **recursive file search** using `searchFile()` function.
- Searches through all directories and subdirectories.
- Displays paths where matching files or folders are found.

### **Day 5 – File Permission Management**
- Implemented viewing and modifying file permissions:
  - **View Permissions** – Displays permissions in `rwxr-xr-x` format.
  - **Change Permissions** – Allows permission modification using octal mode (e.g., `644`, `755`).

---

## ⚙️ Features Implemented

| Feature | Description |
|----------|--------------|
| **List Files** | Displays all files and directories in the current directory. |
| **Copy File** | Copies contents from source to destination file. |
| **Move File** | Moves a file to another directory or renames it. |
| **Delete File** | Deletes a specified file. |
| **Create File** | Creates a new empty file. |
| **Search File** | Recursively searches for files or folders by keyword. |
| **View Permissions** | Displays file permission in symbolic form (`rwxr-xr-x`). |
| **Change Permissions** | Changes file permission using octal values (e.g., `chmod 755 file.txt`). |
| **Exit** | Safely exits the file explorer. |

---

## 🧩 Commands Available

