TASK 04
Elevate Labs


# 📁 DevOps Version-Controlled Project using Git & GitHub

## 🎯 Objective
Manage and organize a DevOps project using Git best practices including branching strategies, pull requests, tagging, and documentation.

---

## 🧰 Tools Used
- Git (Version Control)
- GitHub (Remote Repository)

---

## 🚀 Project Workflow

✅ Step 1: Initialize the Repository

git init
git remote add origin https://github.com/Faikhan147/TASK-4.git
git config --global user.name "Faisal Khan"
git config --global user.email "faisalkhanattari35@gmail.com"
git add README.md
git commit -m "first commit"

✅ Step 2: Create and Push Branches

# Create main branch
git checkout -b main
git push -u origin main

# Create dev branch
git checkout -b dev
git push -u origin dev

# Create a feature branch (e.g., for Docker setup)
git checkout -b feature/docker-setup
git push -u origin feature/docker-setup


git remote add origin https://github.com/Faikhan147/TASK-4.git
git push -u origin main


✅ Step 3: Workflow with Pull Requests

Work on feature/branch

Commit changes with clear messages

Push feature branch to GitHub

Open a Pull Request (PR) from feature/* ➡️ dev

Once tested and approved, merge dev ➡️ main


✅ Step 4: Use Tags for Releases

# Create a version tag
git tag -a v1.0 -m "Initial stable release"
git push origin v1.0
