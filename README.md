# Git Commands Cheat Sheet

### 1. Initialize a Repository

```bash
git init
```

Creates a new Git repository in the current folder.

### 2. Check Repository Status

```bash
git status
```

Shows modified, untracked, and staged files.

### 3. Add a File

```bash
git add filename.html
```

Stages a specific file for the next commit.

### 4. Add All Files

```bash
git add .
```

Stages all changed and untracked files.

### 5. Commit Changes

```bash
git commit -m "Your commit message"
```

Saves the staged changes to Git history.

### 6. Connect to GitHub

```bash
git remote add origin https://github.com/USERNAME/REPOSITORY.git
```

Connects the local repository to a GitHub repository.

### 7. Check Remote Repository

```bash
git remote -v
```

Shows the GitHub repository connected to the project.

### 8. Push to GitHub

```bash
git push -u origin main
```

Uploads the local `main` branch to GitHub.

### 9. Pull Changes

```bash
git pull
```

Downloads and applies the latest changes from the remote repository.

### 10. Create a Branch

```bash
git branch branch-name
```

Creates a new branch without switching to it.

### 11. Create and Switch to a Branch

```bash
git switch -c branch-name
```

Creates a new branch and switches to it.

### 12. Switch Branches

```bash
git switch branch-name
```

Switches to an existing branch.

### 13. List Branches

```bash
git branch
```

Shows all local branches.

### 14. Delete a Local Branch

```bash
git branch -d branch-name
```

Deletes a local branch.

### 15. Push a New Branch

```bash
git push -u origin branch-name
```

Uploads a new branch to GitHub and connects it to the remote branch.

### 16. View Commit History

```bash
git log
```

Shows the commit history of the repository.

### 17. Undo Staging

```bash
git restore --staged filename.html
```

Removes a file from staging without deleting its changes.

### 18. Discard File Changes

```bash
git restore filename.html
```

Reverts a file to its last committed version.

### 19. Clone a Repository

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
```

Downloads an existing GitHub repository to your computer.

### 20. Delete a Remote Branch

```bash
git push origin --delete branch-name
```

Deletes a branch from GitHub.

---

## Basic Git Workflow

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git push -u origin main
```

### For Future Changes

```bash
git add filename.html
git commit -m "Update HTML file"
git push
```

