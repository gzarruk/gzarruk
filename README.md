# UTILITIES - HELPER FUNCTIONS AND COMMANDS
Collection of useful utilities

## Seting up a jupyter kernel that works with poetry environment

Added both `jupyter` and `ipykernel` as dependencies in your poetry project then run the following command

    poetry run ipython kernel install --user --name=my-kernel-name

Ideally name the kernel with the same poetry project name 

# Git workflows

## Update local branch with remote master

1. Go to the branch in question
    git checkout <branch-name>
2. Make sure you’ve committed all changes locally
3. Checkout master and do a git pull 
    - git checkout master
    - git pull
4. Go back to your branch and do git merge master
    - git checkout 'branch-name'
    - git merge master
