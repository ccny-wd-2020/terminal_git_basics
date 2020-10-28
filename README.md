# Terminal & Git Basics

---

# Beginner Terminal

- [Mac Command Line Start](https://www.theodinproject.com/courses/web-development-101/lessons/command-line-basics-web-development-101)
- [Windows Command Line Start](https://www.atlassian.com/git/tutorials/git-bash)

---

# Basic Terminal Commands

- Change Directory
```bash
cd <path/to/project/directory>
```
- Present Working Directory
```bash
pwd
```
- View Files in Directory
```bash
ls
```
```bash
ls -la
```
- Create Folder
```bash
mkdir <folder name>
```
- Create File
```bash
touch <file name>
```
- Show History of Commands
```bash
history
```
- Clear terminal
```bash
clear
```
- zip a directory
```bash
zip -r <file_name>.zip <directory>
```
for example
```bash
zip -r my_project.zip my_project/*
```
- edit file contents ("vi" gets you into editing mode. press "i" to start editing. Press: Escape -> ":wq" to get out of editing mode)
```bash
vi <file>
```
for example
```bash
vi whatever.txt
```
---

# Git Setup
- [Download git on windows](https://git-scm.com/download/win)
- [Steps to setup git on windows](https://phoenixnap.com/kb/how-to-install-git-windows)

- [Steps to setup git on a mac](https://www.atlassian.com/git/tutorials/install-git)

---

# Basic Git Commands
- git is a command line tool used to sync your local projects up with a code repository (i.e. github)

- Initialzing a github repository in your local project
```bash
git init
```
- Syncing up your local project with the github repository
```bash
git remote add origin
```
- Set up all local changes to eventually be pushed to a github repository
```bash
git add .
```
- Commit message describing local changes
```bash
git commit -m 'description of changes'
```
- Pushing your code up to your github repository
```bash
git push origin main
```
- Switching to a new local branch called main. When we create the github repository they create a branch called main. however, when we run the "git remote" command locally, it has us on the "master" branch. We run this command in order to be on the same branch as our github repository
```bash
git checkout -b main
```
---
# GIT IGNORE
- add a .gitignore file to the main directory in your repository in order to restrict certain files from being pushed up to git.
- the .gitignore file below is restricting .DS_Store files from my local maching to being pushed to the github repository. It's as simple as it looks below.
```
.DS_Store
```
---
