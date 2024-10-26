# Git Commands for DevOps

This document provides a series of Git commands used for initializing and managing a repository.

### 1. Create a New Directory and Initialize Git

    mkdir git-for-devops
    cd git-for-devops/
    git init

### 2. Basic File Operations

    ls -a          # List all files, including hidden ones
    touch hi.txt   # Create a new file named hi.txt
    ls             # List files in the directory

### 3. Git Status and Adding Files

    git status             # Check the status of the repository
    git add hi.txt         # Stage the file hi.txt
    git status             # Check the status again

### 4. Remove Cached File

    git rm --cached hi.txt # Remove hi.txt from the staging area
    git status             # Check the status of the repository

### 5. Commit Changes

    git add hi.txt                   # Stage the file again
    git commit -m 'adding hi.txt'    # Commit with a message
    git status                       # Check the status

### 6. Remove and Restore Files

    rm hi.txt                        # Delete the file
    git status                       # Check the status
    git restore hi.txt               # Restore the deleted file
    ls                                # List files in the directory

### 7. View Commit History and Branching

    git log                          # View the commit history
    git branch                       # List all branches
    git checkout -b dev              # Create and switch to a new branch 'dev'

### 8. Adding and Committing New Files

    touch hello.txt                  # Create a new file hello.txt
    git add hello.txt                # Stage hello.txt
    git commit -m 'added hello'      # Commit with a message

### 9. Switching Branches

    git checkout                     # Switch to the previous branch
    git branch                       # List branches
    git checkout master              # Switch to the master branch
    git checkout dev                 # Switch back to the dev branch
    ls                                # List files in the directory

### 10. View Command History

    history                          # Show the command history
