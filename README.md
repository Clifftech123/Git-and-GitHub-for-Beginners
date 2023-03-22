
![Git & GitHub for Beginners](image/image8_0e61d0dad8.png)

Welcome to Git & GitHub for Beginners! This guide is designed to help you get started with Git & GitHub. It will help you to understand the basics of Git & GitHub and to get you started with using Git & GitHub.




## Table of Contents

- [What is this?](#what-is-this)
- [Why?](#why)
- [Who is this for?](#who-is-this-for)
- [Notes](#notes)
- [Assumptions](#assumptions)
- [Terms](#terms)
- [What is GitHub?](#what-is-github)
- [What is GitHub used for?](#what-is-github-used-for)
- [What is Git?](#what-is-git)
- [Common tasks you need to do with Git](#common-tasks-you-need-to-do-with-git)
- [How to install Git](#how-to-install-git)
- [How to configure Git](#how-to-configure-git)
- [How to create a repository](#how-to-create-a-repository)
- [How to clone a repository](#how-to-clone-a-repository)
- [How to create a branch](#how-to-create-a-branch)
- [How to make changes to a file](#how-to-make-changes-to-a-file)
- [How to stage changes](#how-to-stage-changes)
- [How to commit changes](#how-to-commit-changes)
- [How to push changes to a remote repository](#how-to-push-changes-to-a-remote-repository)
- [How to create a pull request](#how-to-create-a-pull-request)
- [How to merge a pull request](#how-to-merge-a-pull-request)
- [How to resolve merge conflicts](#how-to-resolve-merge-conflicts)
- [How to revert a commit](#how-to-revert-a-commit)
- [How to delete a branch](#how-to-delete-a-branch)


## What is this?

- A guide to Git & GitHub for beginners
- A collection of resources to help you learn Git & GitHub
- A place to ask questions and get help

## Why?

- I've been using Git & GitHub for a few years now and I've found it to be a really useful tool.- I've used it to collaborate with others on projects, to keep track of changes to my code, and to revert to previous versions of my code when I've made a mistake
- I've also found that there are a lot of resources out there that are either too basic or too advanced
- I wanted to create a guide that would help people who are new to Git & GitHub to get started and to help them to understand the basics of Git & GitHub

## Who is this for?

- Those who are yet to land their first job in tech
- Those who have recently landed their first job in tech
- Those who are looking to improve their skills
- Those who are looking to learn a new skill
- Those who are looking to get a better understanding of Git & GitHub

## Notes

- There are different Git workflows - Trunk, GitFlow, GitHubFlow
- This guide is based on the GitHubFlow workflow


## Assumptions

- You have a [GitHub account](https://github.com/)
- You have [Git installed](https://git-scm.com/)
- You have a [text editor](https://code.visualstudio.com/) installed
- You have [Node.js](https://nodejs.org/en/) installed

## Terms

- Branch - A version of the codebase
- Commit - A unit of change
- Stage
- Merge - Combining two branches
- Pull Request - A request to merge a branch into another branch
- Fork - A copy of a repository
- Clone - A copy of a repository on your local machine
- Remote - A copy of a repository on a remote server
- Origin - The default remote name given to a repository when it is cloned
- Upstream - The original repository that was cloned
- Master - The default branch name given to a repository when it is created
- Repository - A directory that contains all of the files for a project
- Working Directory - The directory that contains the files that you are working on
- Staging Area - The directory that contains the files that are ready to be committed
- Index - The directory that contains the files that are ready to be committed
- HEAD - The current branch that you are working on
- Checkout - Switching between branches
- Push - Sending your commits to a remote repository
- Pull - Fetching and merging changes on a remote repository to your local repository
- Fetch - Fetching changes on a remote repository to your local repository

## What is GitHub?

![Github](image/GitHub-Logo.png)

- GitHub is a code hosting platform for version control and collaboration
- It lets you and others work together on projects from anywhere
- This tutorial teaches you GitHub essentials like repositories, branches, commits, and Pull Requests
- You’ll create your own Hello World repository and learn GitHub’s Pull Request workflow, a popular way to create and review code
- You’ll also learn about issues, GitHub’s powerful tracking tools for every bug and feature request that comes your way

## What is GitHub used for?

- GitHub is a code hosting platform for version control and collaboration
- It lets you and others work together on projects from anywhere
- You can use GitHub to store and share your code, track and assign issues, and manage pull requests
- You can also use GitHub to create your own website using GitHub Pages
- GitHub is a great way to collaborate with others on projects

## What is Git?

![Git](image/68747470733a2f2f6769742d73636d2e636f6d2f696d616765732f6c6f676f732f646f776e6c6f6164732f4769742d4c6f676f2d32436f6c6f722e706e67.png)

- Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency
- Git is easy to learn and has a tiny footprint with lightning fast performance
- It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows
- Git was initially designed and developed by Linus Torvalds for Linux kernel development

- Git is a version control system
- Allows you to track changes to your code over time
- Enables you to collaborate with others on the same codebase
- You can easily revert to a previous version of your code or experiment with new features without affecting the main codebase
- Provides a record of all changes made to your code, including who made them and when, which can be useful for auditing and debugging

## Common tasks you need to do with Git

- Create a repository
- Create a branch
- Make changes to a file
- Stage changes
- Commit changes
- Push changes to a remote repository
- Merge changes
- Revert changes
- Delete a branch


## How to install Git

- [Download Git](https://git-scm.com/downloads)
- [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

## How to configure Git

- `git config --global user.name "Your Name"` - Set a name that is identifiable for credit when review version history

```bash

# Set a name that is identifiable for credit when review version history

$ git config --global user.name "Your Name"

```

- `git config --global user.email "

- Set an email address that will be associated with each history marker

```bash

# Set an email address that will be associated with each history marker

$ git config --global user.email "

```

- `git config --global color.ui auto` - Set automatic command line coloring for Git for easy reviewing

```bash

# Set automatic command line coloring for Git for easy reviewing

$ git config --global color.ui auto

```

- `git config --global core.editor "code --wait"` - Set the default editor for Git

```bash

# Set the default editor for Git

$ git config --global core.editor "code --wait"

```

- `git config --global init.defaultBranch main` - Set the default branch name to main

```bash

# Set the default branch name to main

$ git config --global init.defaultBranch main

```







## Git commands

- `git init` - Create a new local repository

```bash
# Create a new directory called my-project

$ git init my-project

```

- `git status` - Show the status of the current branch

```bash
#  Check the status of the current branch

$ git status  # On branch master

```

- `git clone` - Clone a repository that already exists on GitHub to your local machine

```bash

#Clone a repository that already exists on GitHub to your local machine


$ git clone  project-name # Cloning into `project-name`...

# make sure to copy the URL from the repository you want to clone

```

- `git add` - Add files to the staging area

```bash


# Add files to the staging area


$ git add . # Changes to be committed:
# when you add the dot, it adds all the files in the current directory

$ git add file-name # Changes to be committed:

# when you add the file name, it adds the file with the name you specified


```

- `git commit` - Commit changes to head (but not yet to the remote repository)

```bash

# Commit changes to head (but not yet to the remote repository)


$ git commit -m "Commit message" # [master (root-commit) 1a2b3c4] Commit message


```

- `git push` - Push changes to remote repository (eg. GitHub)

```bash

# Push changes to remote repository (eg. GitHub)

$ git push origin master # Pushing to

```

- `git pull` - Fetch and merge changes on the remote server to your working directory

```bash

# Fetch and merge changes on the remote server to your working directory


$ git pull origin master # Updating 1a2b3c4..3d4e5f6
# Fast-forward
#  README | 1 +
#  1 file changed, 1 insertion(+)
#  create mode 100644 README

```

- `git fetch` - Fetch changes on the remote server to your working directory

```bash

# Fetch changes on the remote server to your working directory


$ git fetch origin master # remote: Counting objects: 5, done.

```

- `git merge` - Merge a branch into the branch you are currently on

````bash


# Merge a branch into the branch you are currently on

$ git merge branch-name # Updating 1a2b3c4..3d4e5f6



- `git branch` - List, create, or delete branches

```bash

# List, create, or delete branches


$ git branch # * master
#  test

$ git branch branch-name # * master
#  branch-name
#  test

$ git branch -d branch-name # Deleted branch branch-name (was 1a2b3c4).

````

- `git checkout` - Switch branches or restore working tree files

```bash

# Switch branches or restore working tree files


$ git checkout branch-name # Switched to branch 'branch-name'

$ git checkout -b branch-name # Switched to a new branch 'branch-name'

```

- `git remote` - Manage set of tracked repositories

```bash

# Manage set of tracked repositories
$ git remote -v # origin


```

- `git log` - Show commit logs

```bash
# Show commit logs
$ git log # commit 1a2b3c4

```

- `git diff` - Show changes between commits, commit and working tree, etc

```bash

   # Show changes between commits, commit and working tree, etc

   $ git diff # diff --git a/README.md b/README.md

```

- `git reset` - Reset current HEAD to the specified state

```bash

# Reset current HEAD to the specified state


$ git reset --hard HEAD # HEAD is now at 1a2b3c4

```

- `git rm` - Remove files from the working tree and from the index

```bash

# Remove files from the working tree and from the index


$ git rm file-name # rm 'file-name'

```

- `git mv` - Move or rename a file, a directory, or a symlink

```bash

# Move or rename a file, a directory, or a symlink


$ git mv file-from file-to # rename file1 => file2

```

- `git stash` - Stash the changes in a dirty working directory away

```bash

# Stash the changes in a dirty working directory away


$ git stash # Saved working directory and index state WIP on master: 1a2b3c4

```

- `git tag` - Create, list, delete or verify a tag object signed with GPG

```bash

# Create, list, delete or verify a tag object signed with GPG


$ git tag # v1.0.0

```

## The Git workflow

- Create a repository
- Create a branch
- Make changes to a file
- Stage changes
- Commit changes
- Push changes to a remote repository
- Merge changes
- Revert changes
- Delete a branch

## How to create a repository

- `git init` - Create a new local repository

```bash

# Create a new directory called my-project

$ git init my-project

```

- `git clone` - Clone a repository that already exists on GitHub to your local machine

```bash

# Clone a repository that already exists on GitHub to your local machine

$ git clone project-name # Cloning into `project-name`...


# make sure to copy the URL from the repository you want to clone

```

## How to make changes to a file

- `git status` - Show the status of the current branch

```bash

# Check the status of the current branch

$ git status # On branch master

```


- `git add` - Add files to the staging area

```bash

# Add files to the staging area

$ git add . # Changes to be committed:

# when you add the dot, it adds all the files in the current directory

$ git add file-name # Changes to be committed:

```

- `git commit` - Commit changes to the current branch

```bash

# Commit changes to the current branch

$ git commit -m "Commit message" # [master (root-commit) 1a2b3c4] Commit message

```

- `git diff` - Show file differences that haven’t been staged

```bash

# Show file differences that haven’t been staged

$ git diff # diff --git a/README.md b/README.md

```


## How to push changes to a remote repository

- `git push` - Push changes to a remote repository

```bash

# Push changes to a remote repository


$ git push origin master # Enumerating objects: 3, done.
# Counting objects: 100% (3/3), done.
# Writing objects: 100% (3/3), 226 bytes | 226.00 KiB/s, done.
# Total 3 (delta 0), reused 0 (delta 0)
# To
    
  ```

## How to merge changes

- `git merge` - Merge changes from one branch to another

```bash

# Merge changes from one branch to another


$ git merge branch-name # Updating 1a2b3c4..4d5e6f7

```


## How to revert changes

- `git revert` - Revert changes to a file

```bash

# Revert changes to a file


$ git revert file-name # Revert "Revert "Update README.md""

```

## How to delete a branch

- `git branch -d` - Delete a branch

```bash


# Delete a branch


$ git branch -d branch-name # Deleted branch branch-name (was 1a2b3c4).

```

## How to create a branch

- `git branch` - Create a new branch

```bash

# Create a new branch


$ git branch branch-name # Switched to a new branch 'branch-name'

```

## How to view the history of a repository

- `git log` - View the history of a repository

```bash

# View the history of a repository


$ git log # commit 1a2b3c4 (HEAD -> master)

```
