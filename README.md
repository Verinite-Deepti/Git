
# Git

Welcome to the Git Cheatsheet! 
This file provides a quick reference for common Git commands and operations. 
Git is a powerful version control system used to track changes in source code during software development. 
It enables multiple developers to work on a project simultaneously while maintaining a complete history of changes.


# Introduction to Git
Git is a distributed version control system designed to handle everything from small to very large projects with speed and efficiency. It allows you to:

Track changes: Keep a history of changes made to files and directories.

Branching: Create branches to work on different features or fixes simultaneously.

Merging: Integrate changes from different branches.

Collaboration: Share your work with others and integrate changes from collaborators.


# Setup and Configuration
git config --global user.name "Your Name"

git config --global user.email "your.email@example.com"

git config --global core.editor "your-editor"

# View your configuration settings

git config --list


# Basic Commands

*Initialize a new Git repository*
git init

*Clone an existing repository*
git clone <repository-url>

*Check the status of your working directory*
git status

*View the commit history*
git log

# Branching

- **List all branches**
git branch

*Create a new branch*
git branch <branch-name>

*Switch to a different branch*
git checkout <branch-name>

*Create and switch to a new branch*
git checkout -b <branch-name>

*Delete a branch*
git branch -d <branch-name>

Staging and Committing
*Stage a specific file*
git add <file-name>

*Stage multiple files*
git add <file1> <file2> <file3>

*Stage all changes in the current directory*
git add .

*Stage all changes in the repository*
git add -A

*Unstage a specific file*
git reset <file-name>

*Unstage all changes*
git reset

*Commit staged changes with a message*
git commit -m "Your commit message"

*Commit with a detailed message*
git commit

