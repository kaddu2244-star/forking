# Forking

This is a practice GitHub repository for learning and practicing **forking** on GitHub.

## 📖 About

This repository is created for practice purposes to understand how GitHub forking works and how developers contribute to other repositories.

Forking allows you to create your own copy of someone else's repository under your GitHub account. You can make changes in your fork without affecting the original repository.

---

## 🎯 What I Am Learning

In this repository, I am practicing:

* How to fork a repository
* How to clone a forked repository
* How to make changes
* How to check repository status
* How to add changes using Git
* How to commit changes
* How to push changes to GitHub
* How to create a Pull Request
* How to contribute changes to the original repository

---

# 🚀 Steps to Perform Forking

## Step 1: Fork the Repository

1. Open the repository on GitHub.
2. Click the **Fork** button in the top-right corner.
3. Select your GitHub account.
4. GitHub will create a copy of the repository in your account.

Now you have your own version of the repository.

---

## Step 2: Clone Your Fork

Copy the URL of your forked repository and run:

```bash
git clone <your-fork-repository-url>
```

Example:

```bash
git clone https://github.com/your-username/forking-practice.git
```

---

## Step 3: Move into the Repository Folder

```bash
cd forking-practice
```

Check the files:

```bash
ls
```

On Windows Command Prompt, you can use:

```bash
dir
```

---

## Step 4: Check the Remote Repository

Run:

```bash
git remote -v
```

You should see something similar to:

```bash
origin  https://github.com/your-username/forking-practice.git (fetch)
origin  https://github.com/your-username/forking-practice.git (push)
```

Here, **origin** refers to your forked repository.

---

## Step 5: Make Some Changes

Open the project in your code editor:

```bash
code .
```

Make changes to a file.

For example, update the `README.md` file or create a new file:

```bash
touch practice.txt
```

---

## Step 6: Check Git Status

Run:

```bash
git status
```

This command shows:

* Modified files
* New files
* Untracked files

---

## Step 7: Add Changes

Add a specific file:

```bash
git add README.md
```

Or add all changes:

```bash
git add .
```

---

## Step 8: Commit the Changes

Create a commit:

```bash
git commit -m "Added changes for fork practice"
```

A commit saves your changes in the local Git repository.

---

## Step 9: Push Changes to Your Fork

Run:

```bash
git push origin main
```

If your branch name is different, replace `main` with your branch name.

Your changes will now be uploaded to **your forked repository** on GitHub.

---

# 🔄 Creating a Pull Request

After making and pushing changes:

1. Open your forked repository on GitHub.
2. Click **Contribute**.
3. Click **Open Pull Request**.
4. Compare your changes with the original repository.
5. Add a title and description.
6. Click **Create Pull Request**.

Your Pull Request will be sent to the owner of the original repository for review.

---

# 🔗 Understanding the Forking Workflow

```text
Original Repository
        │
        │ Fork
        ▼
Your Forked Repository
        │
        │ Clone
        ▼
Local Repository
        │
        │ Make Changes
        ▼
Git Add → Git Commit
        │
        │ Push
        ▼
Your Forked Repository
        │
        │ Pull Request
        ▼
Original Repository
```

---

# 🛠️ Important Git Commands

| Command                   | Description              |
| ------------------------- | ------------------------ |
| `git clone <url>`         | Clone a repository       |
| `git status`              | Check the current status |
| `git add .`               | Add all changes          |
| `git commit -m "message"` | Save changes as a commit |
| `git push origin main`    | Push changes to GitHub   |
| `git remote -v`           | View remote repositories |
| `git branch`              | View branches            |
| `git log --oneline`       | View commit history      |

---

# 💡 Fork vs Clone

### Fork

A **fork** creates a copy of a repository on **GitHub** under your own account.

### Clone

A **clone** creates a local copy of a repository on **your computer**.

### Simple Flow

```text
Fork → GitHub Account

Clone → Local Computer
```

---

# 🎯 Purpose

The purpose of this repository is to practice the complete GitHub contribution workflow:

```text
Fork
 ↓
Clone
 ↓
Create / Modify Files
 ↓
Git Add
 ↓
Git Commit
 ↓
Git Push
 ↓
Create Pull Request
```

This repository is only for **learning and practicing Git and GitHub concepts**.

**Happy Coding! 🚀**
