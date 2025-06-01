# Git Commands Reference Guide

Welcome to the **Git Commands Practice Repository**. This document serves as a concise yet comprehensive reference to essential Git commands, tailored for both beginners and experienced developers. Each command includes a description, use case, and real-world example to facilitate effective version control practices.

---

## 🔧 Git Commands Overview

### 1. `git init`

**Description:**  
Initializes a new Git repository in the current directory.

**Use Case:**  
Use this command when starting a new project to begin tracking it with Git.

**Example:**
```bash
mkdir my-project
cd my-project
git init
```

---

### 2. `git clone`

**Description:**  
Clones a remote repository into a local directory.

**Use Case:**  
Use this to contribute to or work on an existing project hosted on a remote platform such as GitHub.

**Example:**
```bash
git clone https://github.com/Saliha-1111/git-commands-practice.git
```

---

### 3. `git status`

**Description:**  
Displays the state of the working directory and staging area.

**Use Case:**  
Use this command to review which changes are staged, unstaged, or untracked.

**Example:**
```bash
git status
```

---

### 4. `git add`

**Description:**  
Stages changes in the working directory for the next commit.

**Use Case:**  
Use this to prepare specific files or all changes before committing.

**Example:**
```bash
git add filename.txt
# Stage all changes
git add .
```

---

### 5. `git commit`

**Description:**  
Saves a snapshot of the staged changes to the repository history.

**Use Case:**  
Use this command to record the current state of the project with a meaningful message.

**Example:**
```bash
git commit -m "Add initial files and setup project structure"
```

---

### 6. `git push`

**Description:**  
Uploads local commits to the corresponding remote branch.

**Use Case:**  
Use this command to share your local changes with others or back them up on a remote server like GitHub.

**Example:**
```bash
git push origin main
```

---

### 7. `git pull`

**Description:**  
Fetches and merges changes from the remote repository into the local branch.

**Use Case:**  
Use this command to stay up to date with the latest changes made by collaborators.

**Example:**
```bash
git pull origin main
```

---

### 8. `git branch`

**Description:**  
Lists existing branches, or creates a new branch.

**Use Case:**  
Use this command to organize work by feature or task using isolated branches.

**Example:**
```bash
git branch             # List branches
git branch feature-x   # Create a new branch
```

---

### 9. `git checkout`

**Description:**  
Switches to another branch or restores files.

**Use Case:**  
Use this command to navigate between branches or reset changes.

**Example:**
```bash
git checkout feature-x
```

---

### 10. `git merge`

**Description:**  
Combines changes from one branch into another.

**Use Case:**  
Use this command to integrate work from a feature branch into the main development branch.

**Example:**
```bash
git checkout main
git merge feature-x
```

---

## 📚 Recommended Resources

- [Official Git Documentation](https://git-scm.com/doc)
- [Pro Git Book (Free)](https://git-scm.com/book/en/v2)
- [GitHub Learning Lab](https://lab.github.com/)

---

## 👩‍💻 Author

**Saliha Naseer**  
Software Engineer | AI & Web Development Enthusiast  
GitHub: [Saliha-1111](https://github.com/Saliha-1111)  

---

## ✅ License

This repository is licensed under the [MIT License](LICENSE).

---

## 🌟 Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and open a pull request.

---

*This guide is maintained as part of a personal learning initiative and is open to the developer community for further enhancement.*
