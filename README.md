# Git Command Line Reference

This README provides a quick reference to some of the most commonly used Git command lines.

## Getting Started

- **Clone a repository**: To clone (or download) a repository that exists on GitHub, use the following command:

    ```bash
    git clone <repository-url>
    ```

- **Initialize a new Git repository**: If you've just created a new directory (or have an existing directory) that you want to start versioning with Git, you can use the following command:

    ```bash
    git init
    ```

## Basic Snapshotting

- **Check the status of your files**: To see which files have changes that have not been committed, use:

    ```bash
    git status
    ```

- **Track new files**: To start tracking new files, use:

    ```bash
    git add <file-name>
    ```

- **Stage modified files**: To stage a file that you've modified, use:

    ```bash
    git add <file-name>
    ```

- **Commit changes**: To commit the changes you've staged, use:

    ```bash
    git commit -m "<commit-message>"
    ```

## Branching and Merging

- **List all branches**: To list all local branches, use:

    ```bash
    git branch
    ```

- **Create a new branch**: To create a new branch, use:

    ```bash
    git branch <branch-name>
    ```

- **Switch to a branch**: To switch to a specific branch, use:

    ```bash
    git checkout <branch-name>
    ```

- **Merge a branch**: To merge a branch into the active branch, use:

    ```bash
    git merge <branch-name>
    ```

- **Delete a branch**: To delete a branch, use:

    ```bash
    git branch -d <branch-name>
    ```

## Sharing and Updating

- **Fetch and merge changes from the remote server**:

    ```bash
    git pull
    ```

- **Push local changes to the remote server**:

    ```bash
    git push
    ```

## Inspection and Comparison

- **View commit history**:

    ```bash
    git log
    ```

- **Compare modified files**:

    ```bash
    git diff
    ```


