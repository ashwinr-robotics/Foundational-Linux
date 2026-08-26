# 📁 02 — Files & Directories

> Learning how Linux organizes and manages files and directories.
When switching from Windows to Linux, folders are here known as **Directories**.
---

## 🎯 Objective

Learn how to create, copy, move, rename, inspect, and remove files and directories using the Linux command line.

---

## 🧠 What I Learned

### `mkdir` — Make Directory

Used to create a new directory.

```bash
mkdir directory_name
```
For creating multiple directories at same time:

```bash
mkdir dir1 dir2 dir3
```

Creating nested directories:

```bash
mkdir -p parent/child
```
-p option creates the parent directories if they don't already exist.

### touch - Create a File

Used to create a new empty file.

```bash
touch file.txt
```
It can also update the timestamp of an existing file.

### cp - Copy

Used to copy a file from one location to another.

```bash
cp file.txt backup.txt
```

Copy a file into a directory:

```bash
cp file.txt directory/
```

To copy a directory and its contents:

```bash
cp -r dir1 dir2
```
The -r option means recursive 

### mv - Move/Rename

Used to move a file or directory.

```bash
mv file.txt directory/
```

It can also be used to rename a file:

```bash
mv old_name.txt new_name.txt
```

### rm - Remove 

Used to remove a file.

```bash
rm file.txt
```

To remove a directory and its contents:

```bash
rm -r directory_name
```
⚠️ Be careful with rm. The deleted files normally do not go to a recycle bin.

### rmdir - Remove Directory

Used to remove an empty directory

```bash
rmdir directory_name
```
If the directory contains files, rmdir will not remove it.

## 🔍 Viewing Files

### cat

Displays the contents of a text file.

```bash
cat file.txt
```

### less

Allows a file to be viewed one screen at a time.

```bash
less file.txt
```
Press:
```bash
q
```
To exit.

### file

Shows information about the type of a file.

```bash
file file.txt
```

## 📂 Linux Directory Structure

Linux uses a hierarchical filesystem.

A simplified structure looks like:

```
/
├── home/
│   └── user/
│       ├── Documents/
│       ├── Downloads/
│       └── Projects/
│
├── etc/
├── usr/
├── var/
└── tmp/
```
/ is the root of the filesystem.

My personal files are generally stored inside my home directory:

```
/home/username
```

## 🧪 Practice

1. Create a  practice directory Animals.
2. Enter into it.
3. Create a file named Wolf.md 
4. Create a backup directory backup.
5. Add the contents of the file via shell. 
6. Print the contents in the shell.
7. Overwrite the contents.
8. Add contents at the end of the file.
9. Move/Copy the original file to backup directory.
10. Rename the file -> Remove the file -> Remove the Original directory.



