# Git Tutorial: A Comprehensive Guide

### Hello, This is Fatima and this is my Read: 03 submission. You can view my Markdown webpage using the following [link](https://fati-ma.github.io/reading-notes/Read03)

#### In this blog I will do a summary of the following topic: :smile:
:arrow_right: - [Git Tutorial: A Comprehensive Guide](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

### This guid will explain various aspects of Git:

## 1. Version Control

**Version Control** is a *system that allows you to revisit various versions of a file* or set of files by recording changes. 

- **Local Version Control**
A Local VCS entails one database on your hard disk that stores changes to files.

- **Centralized Version Control**
This system entails a single server storing all changes and file versions.

- **Distributed Version Control**

## 2. Git
- Git is a DVCS that stores data in a file system made up of **snapshots**.
- Git mostly **relies on local operations** because most necessary information can be found in local resources.
- Every single **change applied to any file** or directory is tracked by Git.
- Git is set up to greatly **minimize the possibility of irreversible damage** to files, such as accidentally lost data. 
- Files in Git can reside in three main **states: committed, modified and staged**.

## 3. Download Git
Git can be installed in three ways:

Install as a package
Install via another installer
Download and compile the source code.

## 4. Setting up a Git Repository

- **Importing**

1. Switch to the target project’s directory
Example:
```
$ cd test (cd = change directory)
Use the git init command
$ git init
```

2. To start tracking these repository files, perform an initial commit by typing the following:
```
$ git add *.c
$ git add LICENSE
$ git commit -m “any message here”
```

## 5. Cloning

- To  create a copy of an existing Git repository from a particular server

```
$ git clone https://github.com/test
```

- To clone a repository into a directory with another name of your choosing
```
$ git clone https://github.com/test mydirectory
```

## 6. Workflow: Local Repository Structure

The local Git repository has three components:

Working Directory: The actual files reside here.
Index: The area used for staging
Head: Points to the most recent commit

![localrepo](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

## 7. Saving Changes

- **Tracked**

Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.

- **Untracked**

Untracked files were not in the last snapshot and do not currently reside in the staging area.

## 8. Check File Status

```
$ git status
```

## 9. Tracking and Staging a New File

- **Single File**

Track one file only by using the following format:
```
git add filename
```
- **All Files**

Track all files in a repository by using the following command:
```
$ git add *
```

## 10. Committing a File

After staging one or multiple files, you should commit the changes and record what you did within the commit message:
```
$ git commit -m “made change x,y,z”
```
**Committing All Changes**
```
$ git commit -a
```
## 11. Pushing Changes
This command pushes changes from the local “master” branch to the remote repository named “origin”.

```
$ git push origin master
```

## 12. Stashing Changes
When you are not ready to commit changes but do not want to lose them either, `git stash` is the option. This command temporarily removes changes and hides them, giving you a clean working directory. When you are ready to continue working on the changes, simply use the `git stash apply` command to retrieve the hidden changes.

## 13. Remote Repositories

  **13.1** **Cloned Repositories**
  Git will automatically give the name “origin” to the server from which you cloned and   the name “master” to your local branch.


