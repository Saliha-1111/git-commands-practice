# 📘 Git Commands Practice Notes (by Saliha-1111)

<<<<<<< HEAD
This document contains essential Git commands that are frequently used in software development. Each command includes its purpose, usage scenario, and example.
=======
Repository: [git-commands-practice](https://github.com/Saliha-1111/git-commands-practice)

This document contains essential Git commands that are frequently used in development. Each command includes its purpose and an example.
>>>>>>> 5dfe4ba (Final updated Git notes with all commands)

---

## 1. `git init`
<<<<<<< HEAD

**What it does:**  
Initializes a new Git repository in your current project folder.

**When to use:**  
Use it when starting a new project to enable version control.

=======
**What it does:** Initializes a new Git repository in your project folder.
>>>>>>> 5dfe4ba (Final updated Git notes with all commands)
**Example:**
```bash
mkdir my-project
cd my-project
git init
<<<<<<< HEAD
##2. git clone
What it does:
Creates a local copy of a remote GitHub repository.

When to use:
Use it to download someone else’s project or your own repo from GitHub.

Example:

bash
Copy
Edit
git clone https://github.com/username/repo-name.git
3. git status
What it does:
Shows the current status of your working directory and staging area.

When to use:
Use it to check which files are modified, staged, or untracked.

Example:

bash
Copy
Edit
git status
4. git add
What it does:
Stages changes to be committed.

When to use:
Use it after editing files, before committing them.

Example:

bash
Copy
Edit
git add filename.txt
git add .   # to add all files
5. git commit
What it does:
Saves a snapshot of the staged changes with a message.

When to use:
Use it after git add to permanently record changes.

Example:

bash
Copy
Edit
git commit -m "Added new feature"
6. git push
What it does:
Uploads your local commits to the remote GitHub repository.

When to use:
Use it after committing when you want to update GitHub.

Example:

bash
Copy
Edit
git push
7. git pull
What it does:
Fetches and merges changes from the remote repository into your local branch.

When to use:
Use it to keep your local project up-to-date with GitHub.

Example:

bash
Copy
Edit
git pull
8. git branch
What it does:
Lists, creates, or deletes branches.

When to use:
Use it to manage different versions or features of your project.

Example:

bash
Copy
Edit
git branch          # list branches
git branch new-feature
9. git checkout
What it does:
Switches to another branch or restores files.

When to use:
Use it to move to a different branch or undo changes.

Example:

bash
Copy
Edit
git checkout main
git checkout -b new-feature
10. git merge
What it does:
Merges another branch into your current branch.

When to use:
Use it to combine feature branches into the main branch.

Example:

bash
Copy
Edit
git checkout main
git merge new-feature
yaml
Copy
Edit

---

### ✅ What to do next:

1. **Open your VS Code or editor**
2. **Paste** the full content above into your `git_notes.md` file.
3. Then go to terminal and run:
```bash
git add git_notes.md
git commit -m "Final version with all 10 Git commands"
git push
=======
```

---

## 2. `git clone`
**What it does:** Copies an existing repository from GitHub to your computer.
**Example:**
```bash
git clone https://github.com/Saliha-1111/git-commands-practice
```

---

## 3. `git status`
**What it does:** Shows the status of changes (staged, unstaged, untracked).
**Example:**
```bash
git status
```

---

## 4. `git add`
**What it does:** Adds changes to the staging area.
**Example:**
```bash
git add git_notes.md
```

---

## 5. `git commit`
**What it does:** Saves the staged changes to the repository with a message.
**Example:**
```bash
git commit -m "Added first 5 git commands"
```

---

## 6. `git push`
**What it does:** Uploads your local commits to GitHub.
**Example:**
```bash
git push
```

---

## 7. `git pull`
**What it does:** Fetches and merges changes from GitHub to your local project.
**Example:**
```bash
git pull
```

---

## 8. `git branch`
**What it does:** Creates a new branch or lists all branches.
**Example:**
```bash
git branch
```

---

## 9. `git checkout`
**What it does:** Switches to another branch.
**Example:**
```bash
git checkout main
```

---

## 10. `git merge`
**What it does:** Merges another branch into your current branch.
**Example:**
```bash
git merge feature-branch
```

---

✅ **Created by:** Saliha-1111  
🔗 **GitHub Repo:** https://github.com/Saliha-1111/git-commands-practice
>>>>>>> 5dfe4ba (Final updated Git notes with all commands)
