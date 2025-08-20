🛠️ Git Basics Practice Roadmap
🔹 Stage 1: Local Git Basics

Init a repo → git init

Add & commit files → git add, git commit -m "msg"

Check history → git log, git status

Amend commits → git commit --amend (change last checkpoint)

👉 Goal: Understand commits as checkpoints.

🔹 Stage 2: Branching & Merging

Create a branch → git branch feature-1

Switch branch → git checkout feature-1 (or git switch feature-1)

Do some changes & commit on feature-1

Merge back to main →

git checkout main
git merge feature-1


👉 Goal: See how branching keeps experiments separate.

🔹 Stage 3: Undo & Navigate History

Undo changes before staging → git checkout -- filename

Unstage a file → git reset filename

Go back to old commit (temp) → git checkout <commit-id>

Create new branch from old commit → explore history safely.

👉 Goal: Learn how to recover when mistakes happen.

🔹 Stage 4: Connect with GitHub

Create repo on GitHub.

Push local repo → git remote add origin ... + git push.

Clone a repo → git clone <url>.

Pull updates → git pull.

👉 Goal: See how local ↔ remote sync works.

🔹 Stage 5: Collaboration Simulation

Create two branches → feature-a and feature-b.

Add commits in both.

Merge → experience a merge conflict.

Resolve conflict manually.

👉 Goal: Practice real-world teamwork situations.

🔹 Stage 6: GitHub Workflow (Pull Requests)

Create a feature branch locally.

Push it to GitHub.

On GitHub → open a Pull Request (PR).

Merge PR into main branch via GitHub UI.

👉 Goal: Understand professional collaboration flow.


