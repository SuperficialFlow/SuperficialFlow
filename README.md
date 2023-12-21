![ME (1)](https://github.com/SuperficialFlow/SuperficialFlow/assets/154480145/555c6a63-70be-4ad3-a661-8bd76ad0b5d6)
<h1 align="center">Hello, I'm Jan Gabriel Rea 🗿</h1>
<h3 align="center">Ready to start delving into creating websites</h3>

## About Me :bookmark_tabs:
- 🥶 Currently learning web systems and technologies!
- 📖 How to reach me: (jangabrielrea2020@gmail.com)
- ❤️ My Preferences: Reading, Gaming, Listening to Music.

## Languages Known and Used 📕
<p align="left"> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

## Git Commands Cheat Sheet 
Referential documentation for commonly used Git and GitHub commands provided with descriptions and usage.

- git clone [options] [repository url] [directory] -> Typically used to clone a repository containing the files, branches, and commits.
```bash
Options:
1. --branch, -b<branch> - Clones a default branch.
2. --depth <depth> - Creates a shallow clone with a specified depth.
3. --recursive - Clones submodules along with the repository.
4. --single-branch - Clones only a single branch, reducing the size of the clone. Useful for large repositories.
5. --mirror - Creates a bare mirror of the remote repository.
6. --template <template-directory> - Specifies the directory from which templates will be used.
```
- git push [options] [repository url] [branch name] -> Updates a remote repository with the changes made from a local repository. 
```bash
Options:
1. --all, -a - Pushes all branches to the remote repository.
2. --force, -f - Force-pushes changes to the remote repository, overwriting its history.
3. --tags - Pushes tags to the remote repository.
4. --set-upstream, -u - Sets up tracking information so that future pushes can be done without specifying the remote and branch.
5. --delete - Deletes a remote branch.
6. --mirror - Mirrors all refs to the remote repository. This is often used for creating a backup.
7. --dry-run - Simulates the push without actually sending data to the remote repository.
```
- git diff [options] [commit | branch] [--] [path] -> Views the changes or compares between the changes made. 
```bash
Options:
1. --staged - This command shows the differences between the staging area and the last commit.
2. commit1 commit2 - This command shows the differences between two specific commits.
3. commit - This command shows the differences between the working directory and a specific commit.
4. path/to/file - This command shows the differences for a specific file or directory.
5. -w - This command ignores whitespace changes when showing differences.
6. --side-by-side - This command shows a side-by-side diff output.

```
- git init [options] [directory] -> Initializes a local Git repository.
```bash
a. git init - This initializes a Git repository in the current working directory.
b. git init <directory> - This initializes a Git repository in the specified directory.

Options:
1. --bare - Creates a bare repository. Bare repositories are typically used as central repositories.
2. --template=<template-directory> - Specifies the directory from which templates will be used.
3. --initial-branch=<branch-name> - Sets the name of the initial branch. Useful if you want to start with a branch name other than the default master.
```
- git add [options] [pathspec] ->  Places a modification from the working directory into the staging area, signaling to Git your intention to incorporate changes to a specific file.
```bash
Pathspec - capable of adding changes to either a specific file or directory.

Options:
1. -A, --all - Adds all changes, including untracked files and removing files that are no longer present.
2. -u, --update - Adds modified or deleted files but not untracked files.
3. -p, --patch - Interactively choose hunks of changes to add.
4. -n, --dry-run - Shows what would be added without actually modifying the index.
5. -v, --verbose - Be verbose; show the files being added.
```