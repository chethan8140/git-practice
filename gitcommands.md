
⚙️ Getting Started & Configuration
git init: Creates a new local Git repository.

git clone <repository_url>: Copies a remote repository to your local machine.

git config --global user.name "Your Name": Sets your name for all future commits.

git config --global user.email "your_email@example.com": Sets your email for all future commits.

📝 
Staging & Committing
git status: Shows the status of your working directory, staging area, and branch.

git add <file_name>: Stages a specific file for a commit.

git add .: Stages all changes in the current directory.

git commit -m "message": Saves staged changes to the repository with a descriptive message.

git diff: Shows unstaged changes in your working directory.

git diff --staged: Shows staged changes that are not yet committed.

🌳 
Branching & Merging
git branch: Lists all local branches.

git branch <new_branch_name>: Creates a new branch.

git checkout <branch_name>: Switches to a different branch.

git merge <branch_name>: Merges a specified branch into your current branch.

git branch -d <branch_name>: Deletes a local branch (only if it has been merged).

git branch -D <branch_name>: Force-deletes a branch.

git log --graph --oneline: Provides a concise, visual representation of the branch history.


☁️ Remote Operations
git remote -v: Lists the remote repositories you're connected to.

git push <remote_name> <branch_name>: Uploads your local changes to a remote repository.

git pull <remote_name> <branch_name>: Fetches and merges changes from a remote branch.

git fetch: Downloads changes from a remote repository without merging them.

git remote add <name> <url>: Adds a new remote repository.


⏳ Undoing Changes
git reset <file_name>: Unstages a file.

git restore <file_name>: Discards changes in your working directory for a specific file.

git revert <commit_hash>: Creates a new commit that undoes the changes of a previous commit.

git reset --hard <commit_hash>: DANGEROUS! Discards all changes and history back to a specific commit.

📦
Stashing
git stash: Temporarily saves uncommitted changes.

git stash list: Shows all stashed changes.

git stash pop: Reapplies the most recent stash and removes it from the list.

git stash apply: Reapplies a stash without removing it from the list.

git stash drop: Deletes a specific stash.

🔍 
History & Inspection
git log: Shows a full history of commits.

git log --oneline: Shows a concise, one-line version of the commit history.

git show <commit_hash>: Displays the details and file changes of a specific commit.

git blame <file_name>: Shows who last modified each line of a file.


✨ Advanced Operations
git rebase <base_branch>: Rewrites commit history by moving commits to a new base.

git cherry-pick <commit_hash>: Applies a specific commit from one branch to another.

git tag <tag_name>: Creates a permanent marker for a specific commit (e.g., a release version).

git clean -f: Removes untracked files from the working directory. DANGEROUS!

