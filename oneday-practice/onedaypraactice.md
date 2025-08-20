🚀 One-Day Git Challenge

Complete end-to-end Git practice in 1 day.

✅ Setup

Install Git

Windows → Git for Windows

Linux/macOS → sudo apt install git / brew install git

Configure Git (one-time setup)

git config --global user.name "Your Name"
git config --global user.email "your@email.com"


Create project folder & init repo

mkdir git-challenge
cd git-challenge
git init

🚀 Part 1 – First Commit
echo "Hello Git" > file1.txt
git add file1.txt
git commit -m "First commit: add file1"

🚀 Part 2 – Modify & Track Changes
echo "Adding more content" >> file1.txt
git status
git diff
git add file1.txt
git commit -m "Update file1 with more content"

🚀 Part 3 – Work with Multiple Files
echo "Second file" > file2.txt
git add .
git commit -m "Add file2"

🚀 Part 4 – Branching
git branch feature-branch
git checkout feature-branch
echo "Feature work" > feature.txt
git add feature.txt
git commit -m "Add feature work"


Switch back:

git checkout main

🚀 Part 5 – Merging
git merge feature-branch

🚀 Part 6 – Undo Mistakes

Unstage a file

git reset file2.txt


Discard changes in file

git checkout -- file1.txt


Undo last commit but keep changes

git reset --soft HEAD~1

🚀 Part 7 – Push to GitHub

Create a repo on GitHub (without README).

Link remote:

git remote add origin https://github.com/<your-username>/git-challenge.git
git branch -M main
git push -u origin main

🚀 Bonus – Pull Latest Changes
git pull origin main

