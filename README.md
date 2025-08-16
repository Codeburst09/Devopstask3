# Devopstask3

# DevOps Project with Git & GitHub

## 📌 Objective
Manage a DevOps project using Git best practices:
- Proper branching strategy
- Pull requests & merges
- Tags for releases
- Documentation in markdown

---

## 🚀 Steps Followed

🔹 Initial Setup

git init → Initialize a new Git repository (if not cloned).

git clone <repo-url> → Clone an existing repository.

🔹 Branch Management

git branch → List all branches and show current branch (*).

git branch <branch-name> → Create a new branch.

git checkout <branch-name> → Switch to a branch.

git checkout -b <branch-name> → Create and switch to a new branch.

git branch -d <branch-name> → Delete a branch.


🔹 File Tracking & Staging

git status → Check current branch, staged/untracked files.

git add <file> → Stage specific file(s).

git add . → Stage all modified/untracked files.

git reset <file> → Unstage a file.

🔹 Commit & Push

git commit -m "message" → Commit staged changes.

git log --oneline → View commit history.

git push origin <branch> → Push changes to remote branch.

git pull origin <branch> → Pull latest changes from remote.

🔹 Best Practices

Always run git status before committing.

Keep commits small & meaningful.

Use branches for new features or bug fixes.

Merge changes via Pull Requests (if working in a team).