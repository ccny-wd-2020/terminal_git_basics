# Terminal & Git Basics

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

---

# Git Setup
- [Download git on windows](https://git-scm.com/download/win)
- [Steps to setup git on windows](https://phoenixnap.com/kb/how-to-install-git-windows)

- [Steps to setup git on a mac](https://www.atlassian.com/git/tutorials/install-git)

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
