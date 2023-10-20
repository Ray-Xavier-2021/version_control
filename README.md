# Version Control Git

-  This project is for learning Git essentials - Init, Log, Add, Commit, Branch, Reset.

## Git Commands

### Init

- **Command**: `git init`
- **Explanation**: Initializes a new Git repository in the current directory. It sets up the basic directory structure and files needed for version control.

### Log

- **Command**: `git log`
- **Explanation**: Displays a log of all the commits made in the repository. It provides information about who made the commit, when it was made, and a unique commit identifier (SHA-1 hash).

### Add

- **Command**: `git add <file(s)>`
- **Explanation**: Stages changes in the specified file(s) to be included in the next commit. This command tells Git to start tracking these changes.

### Commit

- **Command**: `git commit -m "Commit message"`
- **Explanation**: Records the changes that have been staged using the `git add` command. It creates a snapshot of the changes and attaches a meaningful commit message to describe what was done in that commit.

### Branch

- **Command**: `git branch <branch-name>`
- **Explanation**: Creates a new branch in the repository. Branches allow you to work on different features or parts of the project independently. You can switch between branches to isolate your work.

### Reset

- **Command**: `git reset <commit>`
- **Explanation**: Resets the current branch to a specific commit. It's used to undo changes or to move the branch pointer to a different commit. There are different modes of reset (soft, mixed, hard), each affecting how Git handles the reset.
