![ME (1)](https://github.com/SuperficialFlow/SuperficialFlow/assets/154480145/555c6a63-70be-4ad3-a661-8bd76ad0b5d6)
<h1 align="center">Hello, I'm Jan Gabriel Rea 🗿</h1>
<h3 align="center">Student of Malayan Colleges of Laguna. Ready to start delving into creating websites</h3>

## About Me :bookmark_tabs:
- 🥶 Currently learning web systems and technologies!
- 📖 How to reach me: (jangabrielrea2020@gmail.com)
- ❤️ My Preferences: Reading, Gaming, and Listening to Music.

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
a. git init <commit1> <commit2> - This command shows the differences between two specific commits.
b. git init <commit> - This command shows the differences between the working directory and a specific commit.
c. git init <path/to/file> - This command shows the differences for a specific file or directory.

Options:
1. --staged - This command shows the differences between the staging area and the last commit.
2. -w - This command ignores whitespace changes when showing differences.
3. --side-by-side - This command shows a side-by-side diff output.

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
Pathspec - capable of adding changes to either a specific <file> or <directory>.

Options:
1. -A, --all - Adds all changes, including untracked files and removing files that are no longer present.
2. -u, --update - Adds modified or deleted files but not untracked files.
3. -p, --patch - Interactively choose hunks of changes to add.
4. -n, --dry-run - Shows what would be added without actually modifying the index.
5. -v, --verbose - Be verbose; show the files being added.
```
- git pull [options] [resporitory url] [branch] -> Fetches and merge changes from a remote repository into the local branch. 
```bash
a. git pull upstream main - Changes from a specific remote repository and branch.

Options:
1. --rebase - Incorporates the changes from the fetched branch by rebasing the current branch.
2. --ff-only - Only allows fast-forward merges. If the remote history has diverged, the pull is aborted.
3. --no-rebase - Disables automatic rebasing. Changes are merged using the default merge strategy.
4. --all - Fetches updates from all remotes.
5. --tags - Fetches tags from the remote repository.
```
- git status [options] -> Command in Git is used to display the status of changes as untracked, modified, or staged in your working directory. 
```bash
Options:
1. -s, --short - Show the status in a short, compact format.
2. -b, --branch - Show the branch information along with the status.
3. -u, --untracked-files=<mode> - Show untracked files. The <mode> can be no (default), normal, or all.
4. --ignored - Show ignored files as well.
```
# Examples:
1. git clone:
![Exe 1](https://github.com/SuperficialFlow/SuperficialFlow/assets/154480145/ebea4de2-ff3e-42b5-9cb4-4635a48d2574)
2. git push:
![Exe 2](https://github.com/SuperficialFlow/SuperficialFlow/assets/154480145/3f84560c-044b-43b5-959c-25e4ac56ed70)
3. git diff:
![Exe 3](https://github.com/SuperficialFlow/SuperficialFlow/assets/154480145/f9101489-799c-48ab-a85c-622a70be7b06)
4. git init:
![Exe 4](https://github.com/SuperficialFlow/SuperficialFlow/assets/154480145/87d28f84-aacc-4974-a76c-af23797babdf)
5. git add:
![Exe 5](https://github.com/SuperficialFlow/SuperficialFlow/assets/154480145/318362ab-a537-4ec4-b482-fe9402c18936)
6. git pull:
![Exe 6](https://github.com/SuperficialFlow/SuperficialFlow/assets/154480145/b491f78d-9b34-47c4-b8c6-bc66e4412555)
7. git status:
![Exe 7](https://github.com/SuperficialFlow/SuperficialFlow/assets/154480145/8ff6570e-8637-4b9b-a488-22777776bf99)





