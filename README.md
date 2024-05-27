# FawryInternShip

- Onsite intern in amazing branch at Smart Village
- ![build](https://github.com/ahmedelhdad123/FawryInternShip/assets/91333530/41e71817-fb6f-4a6c-9f25-2cee6aa336dd)

# Week 1

## OOP
- E-Commerce(OOP)
  - [E-Commerce OOP Repository](https://github.com/ahmedelhdad123/E-Commerce-OOp/tree/master)

## Git

### What is Git?

Git is a distributed version control system designed to track changes in source code during software development. It allows multiple developers to work on a project simultaneously without overwriting each other's changes.

### Why Git is Essential:

- **Collaboration**: Multiple developers can work on the same project simultaneously.
- **Version Control**: Tracks history of changes, making it easy to revert to previous states.
- **Branching and Merging**: Facilitates feature development and bug fixing without disrupting the main project.
- **Backup**: Acts as a backup by storing the entire project history.

### What is the Difference Between Local, Central, and Distributed Version Control?

- **Local Version Control**: Tracks changes in files on a local system, but collaboration is difficult.
- **Central Version Control (CVCS)**: Uses a single central server to store all versions of a project. Developers commit changes to this central repository (e.g., Subversion).
- **Distributed Version Control (DVCS)**: Every developer has a full copy of the project repository, including its history. Changes can be shared between repositories. Git is an example of DVCS.

### What is the Git Architecture?

Git's architecture consists of:
- **Working Directory**: The local files of the project.
- **Staging Area (Index)**: A file that stores information about what will go into the next commit.
- **Git Directory (Repository)**: Contains the complete history of the project, including all commits, branches, and tags.

### What is the Staging Area?

The staging area is a space where you can group changes you want to commit. It acts as a preparation area before changes are recorded in the repository. You add changes to the staging area using `git add`.

### What is a Git Object?

Git objects are the fundamental entities in a Git repository. The four types of Git objects are:
- **Blob**: Stores file data.
- **Tree**: Represents a directory, containing blobs and other trees.
- **Commit**: Points to a tree and represents a snapshot of the project at a given point in time.
- **Tag**: Points to a commit and is used to mark a specific point in the repository history as important.

### What is a Git Tag?

A Git tag is a reference that points to a specific commit. Tags are often used to mark release points (e.g., v1.0, v2.0).

### What is the Difference Between `git log` and `git reflog`?

- **git log**: Displays the commit history of the repository, showing each commit's hash, author, date, and message.
- **git reflog**: Shows the history of all the references in the repository, including updates to the HEAD, branches, and other references.

### What is the Difference Between `git pull` and `git fetch`?

- **git pull**: Fetches changes from a remote repository and immediately attempts to merge them into the current branch.
- **git fetch**: Downloads changes from a remote repository but does not merge them. You need to merge the changes manually.

### What is the Difference Between `git merge` and `git rebase`?

- **git merge**: Combines the changes from one branch into another, creating a new merge commit if there are no conflicts.
- **git rebase**: Moves or reapplies commits from one branch onto another, effectively rewriting the project history.
