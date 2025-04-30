## 🔄 4. Version Control – Git & GitHub

Version control is essential for managing your code, tracking changes, and collaborating with your team. Git is the most popular version control system, and GitHub is a platform to host Git repositories.

---
## 🔄 Summary – Git & GitHub Basics

Version control systems like **Git** are essential tools for managing code changes in software development. **GitHub** allows you to store and collaborate on Git repositories remotely. Here’s a quick summary of key Git concepts:

---

### 🛠️ **Git Basics**
- **git init**: Initializes a new Git repository in your project folder. 
    - Example: `git init`
- **git add**: Stages files for committing. You can add specific files or all files.
    - Example: `git add .` (adds all files)
- **git commit**: Saves your changes in the local repository with a description of what was changed.
    - Example: `git commit -m "Initial commit"`
- **git push**: Pushes local changes to the GitHub repository.
    - Example: `git push origin main`
- **git pull**: Retrieves the latest changes from the GitHub repository to your local machine.
    - Example: `git pull origin main`

---

### 🌿 **Branching & Merging**
- **git branch**: Creates or lists branches in your repository. 
    - Example: `git branch new-feature`
- **git checkout**: Switches between branches. You can also create and switch to a new branch at once.
    - Example: `git checkout -b new-feature`
- **git merge**: Combines changes from one branch into another.
    - Example: `git merge new-feature`

---

### ⚔️ **Resolving Merge Conflicts**
- Sometimes, Git cannot automatically combine changes. In such cases, you need to manually resolve conflicts in the files, then stage and commit those changes.
    - Example: 
      - Open the conflicting file
      - Edit the conflict
      - `git add conflicted-file.js`
      - `git commit -m "Resolved merge conflict"`

---

### 🔄 **GitHub Pull Requests & Workflows**
- **Pull Request (PR)**: A request to merge code from one branch into another (often used to merge changes into the `main` branch).
    - Go to GitHub → Create a new PR → Team reviews → Merge into `main`
- GitHub Workflow: 
    - Work on feature → Push to GitHub → Open PR → Review → Merge

---

### 🏷️ **Tagging, Reverting, and Resetting**
- **Tagging**: Marks a specific commit with a version label (like `v1.0`).
    - Example: `git tag v1.0`
- **Reverting**: Creates a new commit that undoes the changes of a previous commit.
    - Example: `git revert <commit-id>`
- **Resetting**: Removes changes by resetting the repository to a previous commit (be cautious!).
    - Example: `git reset --hard <commit-id>`

---

### 📦 **Quick Command Reference**

| Command                     | Description                           |
|-----------------------------|---------------------------------------|
| `git init`                  | Initializes a new repository          |
| `git add .`                 | Stages all files for commit          |
| `git commit -m "message"`   | Saves changes with a commit message  |
| `git push`                  | Pushes changes to GitHub             |
| `git pull`                  | Pulls the latest changes from GitHub |
| `git branch`                | Creates or lists branches            |
| `git merge`                 | Merges one branch into another       |
| `git tag`                   | Marks a commit with a version label  |
| `git reset --hard`          | Resets repository to a specific commit (destructive) |

---

### ✅ **Conclusion**
Git and GitHub are powerful tools for managing code changes and collaborating in software development. Mastering these basics will help you effectively manage your code, work with others, and ensure smooth development workflows.
