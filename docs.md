# ��� Git Workflow Documentation – Task 4

This document explains the Git commands and workflow followed to complete **Task 4 – Version-Controlled DevOps Project with Git**.

---

## 1️⃣ Initial Repository Setup
```bash
# Initialize local repository
git init

# Add files and commit
git add .
git commit -m "Initial commit: Python app and Dockerfile"

# Rename default branch to main
git branch -M main

# Link local repo with GitHub
git remote add origin https://github.com/<your-username>/Task-4-DevOps-Git.git

# Push to GitHub
git push -u origin main
2️⃣ Creating Branches
# Create and switch to dev branch
git checkout -b dev
git push -u origin dev

# Create a feature branch from dev
git checkout dev
git checkout -b feature-add-readme
3️⃣ Adding README.md and Pushing
# Add README.md file
git add README.md
git commit -m "Added README.md with project details"
git push -u origin feature-add-readme
4️⃣ Pull Request Process
On GitHub:

Create a Pull Request from feature-add-readme → dev.

Merge the Pull Request.

Create a Pull Request from dev → main.

Merge the Pull Request.

5️⃣ Adding .gitignore
# Create .gitignore file
echo "*.log
*.tmp
__pycache__/" > .gitignore

git add .gitignore
git commit -m "Added .gitignore file"
git push
6️⃣ Tagging a Version
git tag v1.0
git push origin v1.0
7️⃣ Stashing (If Needed)
git stash
git stash pop
✅ Outcome
By completing this task:

Practiced creating and managing multiple branches.

Understood Pull Request and merge workflows.

Used .gitignore and tags effectively.

Documented steps in Markdown for clarity.
