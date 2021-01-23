# Git demo
---
## Part 1: Initializing

1. Create a directory for the demo and configure git.
```shell
git config --global user.name “[firstname lastname]”
git config --global user.email “[valid-email]”
git config --global color.ui auto
```
1. Start the git flow.
```shell
git init
```
1. Show the directories created inside the working directory. Git will track the code and store relevant info inside those directories.
```shell
ls -la .
```
---
## Part 1.1: Commiting changes
1. Create a simple file. For example, let's assume it contains a numpy array x, and a numpy function like np.sin as y. Save the file and return to the shell.
1. Verify what the tracking part is doing.
```shell
git status
```
1. Add the file you created to version control.
```shell
git add [file]
```
1. Double check your file.
```shell
git status
```
1. Make your initial commit.
```shell
git commit -m "Initial commit"
```
1. Triple check your file.
```shell
git status
```
1. Add a plotting capability to your file: plot (x,y) with matplotlib. Save the file and run it in the shell.
1. See that the file was changed.
```shell
git status
```
1. Stage the file in the local repository.
```shell
git add [file]
```
1. Make a second commit:
```shell
git commit -m "Added plotting capability"
```
1. Let's see how the tracking goes.
```shell
git status
```
1. Overview the commit history.
```shell
git log
```
---
## Part 1.2: Advanced commands during the commit process

Sometimes there is a need to change what your are commiting. Git allows you to change the status of your added items.

---
## Part 1.3: Hosting (with github)


---
## Part 2: Collaborative workflow with Branches