# 🚀 Day 1 - DevOps Journey

## 🧠 What I Learned Today
- What DevOps is and why it's important.
- Basics of Git and version control.
- How to use GitHub to host code.
- How to install and use GitHub Copilot in VS Code.
- How to push code to a GitHub repository using Git commands.

## 📂 Tools Used
- Git
- GitHub
- Visual Studio Code
- GitHub Copilot

## 🔧 Commands I Used
```bash
git init                            # Initialize a new Git repository
git add .                           # Stage all files for commit
git commit -m "Day 1 DevOps Challenge"  # Save changes with a message
git config --global user.name "Rakshith Murugesh"  # Set Git username
git config --global user.email "rakshith.09m@gmail.com"  # Set Git email
git remote add origin https://github.com/RakshithMurugesh/devops-journey-day1.git  # Link to GitHub repo
git push -u origin master           # Push code to GitHub
```

## 📘 Learning
Git Commands Explained (Day 1)
🔹 git init
What it does:
Initializes a new Git repository in your current folder.

Why it's important:
It tells Git to start tracking changes in this folder. After this, Git will monitor all file changes.

🔹 git add .
What it does:
Stages all the files in the current folder for the next commit.

Why it's important:
Before you can save changes (commit), you need to tell Git which files to include. The . means “all files”.

🔹 git commit -m "Day 1 DevOps Challenge"
What it does:
Saves a snapshot of your staged files with a message.

Why it's important:
Commits are like save points. The -m flag lets you add a message describing what you did.

🔹 git config --global user.name "Rakshith Murugesh"
🔹 git config --global user.email "rakshith.09m@gmail.com"
What they do:
Set your name and email for all Git commits on your system.

Why it's important:
Git uses this info to track who made each change. It’s also shown on GitHub.

🔹 git remote add origin https://github.com/RakshithMurugesh/devops-journey-day1.git
What it does:
Links your local Git repo to a remote GitHub repo.

Why it's important:
This tells Git where to push your code online (to GitHub).

🔹 git push -u origin master
What it does:
Pushes your local commits to the master branch on GitHub.

Why it's important:
This uploads your code to GitHub so others (and you) can access it online.

🔐 If GitHub asks for a login, use your username and a Personal Access Token (PAT) instead of a password.

🔹 git commit --amend --reset-author
What it does:
Updates the author info on your last commit.

Why it's important:
Useful if you forgot to set your name/email before committing.

🔹 git config --global --add safe.directory "C:/Users/..."
What it does:
Tells Git to trust a folder even if ownership looks suspicious.

Why it's important:
Fixes the “dubious ownership” error when Git thinks the folder might be unsafe.
