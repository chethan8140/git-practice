# 📘 Git Complete Practice Guide

This guide combines **7-Day Practice Schedule**, **One-Day Challenge**, and a **Mini Project Workflow**.

---

## 🗓 Git Practice Schedule (7 Days)

### Day 1 – Repositories & Commits
- `git init` → create a new repository  
- `git clone <url>` → copy an existing repo  
- `git add <file>` → stage changes  
- `git commit -m "msg"` → save snapshot  
- `git log --oneline` → view history (short)  

### Day 2 – Branching & Merging
- `git branch feature-x` → create a branch  
- `git checkout feature-x` → switch to branch  
- `git merge feature-x` → merge branch  
- `git branch -d feature-x` → delete branch  
- `git log --graph --oneline --all` → visualize branches  

### Day 3 – Remote (GitHub)
- `git remote add origin <url>` → link repo to GitHub  
- `git push -u origin main` → first push  
- `git push / git pull` → sync changes  
- `git fetch` → fetch updates  
- `git clone <url>` → clone repo  

### Day 4 – Undoing Mistakes
- `git checkout -- <file>` → discard local changes  
- `git reset <file>` → unstage file  
- `git reset --soft HEAD~1` → undo commit (keep staged)  
- `git reset --hard HEAD~1` → undo commit (discard)  
- `git commit --amend` → edit last commit  

### Day 5 – Stash
- `git stash` → save work temporarily  
- `git stash list` → list stashes  
- `git stash pop` → reapply stash  
- `git stash drop` → delete stash  

### Day 6 – Rebase & Cherry-pick
- `git rebase main` → move commits on top of main  
- `git rebase -i HEAD~3` → interactive rebase  
- `git cherry-pick <hash>` → apply specific commit  

### Day 7 – Advanced
- Fork + PR → simulate collaboration  
- Conflict resolution → edit → add → commit  
- `git tag v1.0` → create tag  
- `git push origin v1.0` → push tag  

---

## ⚡ One-Day Git Challenge

### Step 1 – Setup & Repo
```bash
git init myproject
cd myproject
git config user.name "Your Name"
git config user.email "your@email.com"

