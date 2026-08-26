# 🧭 01 — CLI & Navigation

> Learning how to communicate with Linux through the command line.

---

## 🎯 Objective

Learn the basic Linux Command-Line Interface (CLI) and understand how to navigate through the filesystem.

---

## 🧠 What I Learned

### `pwd` — Print Working Directory

Shows the directory I am currently inside.

```bash
pwd
```

### 'ls' - List

This prints the list of files & directories available.

```bash
ls
```

There will be some hidden files in every folders to list them all, try:

```bash
ls -a 
```
or
```bash
la
```

Sometimes, a hidded file holds the actual thing you're looking for!

### cd - Change Directory

Used to move from one directory(folder) to another.

```bash
cd directory_name
```

Go to home directory

```bash
cd ~
```

Go to parent directory

```bash
cd ..
```

### mv - Move / Rename 

mv can be used to move a file or directory

```bash
mv file.txt directory/
```

It can also rename a file

```bash
mv old_name.txt new_name.txt
```

### Output Redirection

> - Redirects output to a file.

```bash
echo "Linux" > file.txt
```

If the file contains something, this > overwrites its contents.

>> - Appends the output to the end of a file 

```bash
echo "Ubuntu" >> file.txt
```

### ~ 

The ~ symbol represents the current user's home directory

```bash
cd ~
```
