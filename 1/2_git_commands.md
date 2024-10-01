# Basic Git Commands

## Commonly Used Git Commands

To see a list of commonly used Git commands for daily operations, you can use the following command in your terminal:

```bash
git help -a
```

This command will display a list of all available Git commands, but for daily operations, you may find the following commands particularly useful.

## Git Daily

### 1. **git init**
   Initializes a new Git repository in the current directory.

   ```bash
   git init
   ```

### 2. **git clone**
   Creates a copy of an existing Git repository. (Note: Not needed for setup.)

   ```bash
   git clone <repository_url>
   ```

### 3. **git status**
   Displays the status of the working directory and staging area, showing which changes have been staged, which are not, and which files aren't being tracked.

   ```bash
   git status
   ```

### 4. **git add**
   Stages changes (files) for the next commit. You can add specific files or all changes.

   To add a specific file:
   ```bash
   git add <filename>
   ```

   To add all changes:
   ```bash
   git add .
   ```

### 5. **git commit**
   Records changes to the repository with a message describing the changes made.

   ```bash
   git commit -m "Your commit message here"
   ```

### 6. **git push**
   Uploads local repository content to a remote repository.

   ```bash
   git push origin <branch_name>
   ```

### 7. **git pull**
   Fetches and merges changes from the remote repository to your local branch.

   ```bash
   git pull origin <branch_name> --rebase
   ```

### 8. **git branch**
   Lists all branches in the repository and indicates the current branch.

   ```bash
   git branch
   ```

### 9. **git checkout**
   Switches to a specified branch or restores working tree files.

   To switch to a branch:
   ```bash
   git checkout <branch_name>
   ```

   To create and switch to a new branch:
   ```bash
   git checkout -b <new_branch_name>
   ```

### 10. **git merge**
   Merges changes from one branch into another.

   ```bash
   git merge <branch_name>
   ```

### 11. **git log**
   Shows the commit history for the current branch.

   ```bash
   git log
   ```

## Conclusion

These basic Git commands are essential for daily operations when working with Git repositories. Make sure to practice these commands to become more comfortable using Git!
```

Feel free to copy and paste this content into your `git_commands.md` file for your workshop! Let me know if you need any further modifications or additional commands.
