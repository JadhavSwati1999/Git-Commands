# Git-Commands
Git commands with discription
Sure! Here’s a comprehensive list of basic and advanced Git commands along with their descriptions:

### Basic Git Commands

1. **git init**
   - Initializes a new Git repository in the current directory.

2. **git clone <repository-url>**
   - Creates a copy of a remote repository locally.

3. **git add <file>**
   - Stages changes to the specified file for the next commit.

4. **git add .**
   - Stages all changes in the current directory.

5. **git commit -m "<message>"**
   - Records the staged changes in the repository with a descriptive message.

6. **git status**
   - Displays the status of the working directory and staging area.

7. **git log**
   - Shows the commit history for the current branch.

8. **git diff**
   - Displays the differences between the working directory and the staging area.

9. **git checkout <branch>**
   - Switches to the specified branch.

10. **git branch**
    - Lists all local branches in the repository.

11. **git branch <branch-name>**
    - Creates a new branch with the specified name.

12. **git merge <branch>**
    - Merges the specified branch into the current branch.

13. **git pull**
    - Fetches and merges changes from the remote repository into the current branch.

14. **git push**
    - Uploads local commits to the remote repository.

15. **git remote -v**
    - Displays the remote repositories associated with the local repository.

16. **git fetch**
    - Retrieves changes from the remote repository without merging.

### Advanced Git Commands

1. **git rebase <branch>**
   - Reapplies commits on top of another base branch, allowing for a cleaner project history.

2. **git cherry-pick <commit>**
   - Applies the changes from a specific commit to the current branch.

3. **git stash**
   - Temporarily saves changes that are not ready to be committed.

4. **git stash pop**
   - Restores the most recent stash and removes it from the stash list.

5. **git reset <commit>**
   - Resets the current branch to a specific commit, altering the commit history.

6. **git reset --hard <commit>**
   - Resets the current branch to a specific commit and discards all changes in the working directory.

7. **git tag <tag-name>**
   - Creates a tag (a marker for a specific commit) in the repository.

8. **git rebase -i <commit>**
   - Interactive rebase allows you to edit, reorder, or squash commits.

9. **git blame <file>**
   - Shows who made changes to each line of a file and when.

10. **git bisect**
    - Uses binary search to find the commit that introduced a bug.

11. **git clean -fd**
    - Removes untracked files and directories from the working directory.

12. **git remote add <name> <url>**
    - Adds a new remote repository with the specified name.

13. **git revert <commit>**
    - Creates a new commit that undoes the changes made by the specified commit.

14. **git reflog**
    - Shows a log of all actions that modified the repository's HEAD, useful for recovering lost commits.

15. **git config --global user.name "<name>"**
    - Sets the global username for commits.

16. **git config --global user.email "<email>"**
    - Sets the global email for commits.

### Conclusion

These commands cover a wide range of functionalities in Git, from basic repository management to advanced history manipulation. Familiarizing yourself with these commands can greatly enhance your version control skills!
