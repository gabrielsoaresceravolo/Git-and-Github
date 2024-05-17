<p align="center">
  <img src="https://github.com/GabrielSoaresCeravolo/Git-and-Github/blob/main/Git-and-Github.png" alt="Capa do Repositório">
</p>

<h1 align="center">Git and GitHub Essentials: Boosting Your Daily Workflow</h1>

![Badge - Status do projeto](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=yellow&style=for-the-badge)

### Description about the repository: 

The purpose of this repository is to learn basic functionalities and tips to enhance my day-to-day experience with Git and GitHub. The repository is open for anyone interested in the same topic to access as well

<hr>

### 🛠️ Global configuration commands for Git

```
git config --global user.name "Github Name"
git config --global user.email "Github Email"
```

The first command sets your global Git username to “GitHub Name”. When you commit changes to a Git repository, this username will be associated with your commits. The next command sets your global Git email address to "Github Email". Your email address is used for identification purposes in your Git commits

<hr>

<br>

### 📑 Command to create and/or clone a repository

| Command                   | Description                               |
|---------------------------|-------------------------------------------|
| `git init`                | Initialize a local Git repository         |
| `git clone [repository-link]` | Create a local copy of a remote repository |

<br>

### 🙂 Basic Commands Used

| Command                             | Description                                      |
|-------------------------------------|--------------------------------------------------|
| `git status`                        | Check status                                     |
| `git add [file-name.txt]`           | Add a file to the staging area                   |
| `git add .`                         | Add all new and changed files to the staging area|
| `git rm -r [file-name.txt]`         | Remove a file (or folder)                        |
| `git commit -m "[commit message]"`  | Commit changes                                   |
| `git push`                          | Push to a remote repository                      |

<br>

### 🌳 Branch and Merge commands

| Command                                                | Description                                        |
|--------------------------------------------------------|----------------------------------------------------|
| `git branch`                                           | List branches                                      |
| `git branch [branch name]`                             | Create a new branch                                |
| `git checkout -b [branch name]`                        | Create a new branch and switch to it               |
| `git branch -d [branch name]`                          | Delete a branch                                    |
| `git branch -m [old branch name] [new branch name]`    | Rename a local branch                              |
| `git checkout [branch name]`                           | Switch to a specific branch                        |
| `git checkout -b [branch name] origin/[branch name]`   | Clone a remote branch and switch to it             |
| `git push origin [branch name]`                        | Push to a remote branch                            |
| `git merge [branch name]`                              | Merge a branch into the active branch              |
| `git merge [source branch] [target branch]`            | Merge a branch into a target branch                |
| `git stash`                                            | Stash changes in a dirty working directory         |
| `git stash clear`                                      | Remove all stashed entries                         |

<hr>

### ⚠️ Some errors that can happen and how to fix them

<br>

Error: Repository Unsafe:

`git config --global --add safe.directory 'Directory Path' `


