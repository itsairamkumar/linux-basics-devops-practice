# Linux Basics DevOps Practice

This repository contains beginner-friendly Linux command line practice tasks covering file operations, permissions, text processing, compression, and environment variables. It is intended for learning and practicing essential Linux skills required in DevOps.

---

## Tasks Covered

### 1. Creating and Renaming Files/Directories

Commands:
```bash
mkdir test_dir
cd test_dir
touch example.txt
mv example.txt renamed_example.txt
```

Explanation:
- mkdir creates a new directory
- touch creates an empty file
- mv renames or moves files

---

### 2. Viewing File Contents

Commands:
```bash
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd
```

Explanation:
- cat displays the entire file content
- head shows the first 5 lines
- tail shows the last 5 lines

---

### 3. Searching for Patterns

Command:
```bash
grep "root" /etc/passwd
```

Explanation:
- grep searches for specific text patterns in a file

---

### 4. Zipping and Unzipping

Commands:
```bash
zip -r test_dir.zip test_dir
unzip test_dir.zip -d unzipped_dir
```

Explanation:
- zip compresses a directory
- unzip extracts compressed files into a directory

---

### 5. Downloading Files

Command:
```bash
wget https://example.com/sample.txt
```

Explanation:
- wget downloads files from a URL

---

### 6. Changing Permissions

Commands:
```bash
touch secure.txt
chmod 444 secure.txt
```

Explanation:
- chmod 444 sets the file to read-only for all users

---

### 7. Working with Environment Variables

Commands:
```bash
export MY_VAR="Hello, Linux!"
echo $MY_VAR
```

Explanation:
- export sets an environment variable
- echo displays the value of the variable

---

## Tools Used

- Linux (WSL - Ubuntu)
- Git and GitHub

---

## Learning Outcome

- Understanding of basic Linux commands
- File and directory management
- Text processing and search using grep
- File compression and extraction
- File permissions management
- Environment variable usage

---

## License

This project is licensed under the MIT License.
