# 🎓 CodeCrypto Student Repository Guide

Welcome to your personal repository for the coding academy! This repository will be used to showcase your progress, projects, and assignments. Please follow the instructions below to set up your repository, create branches, and push your work.

---

## 📋 Table of Contents
1. [Getting Started](#getting-started)
2. [Working with Branches](#working-with-branches)
3. [Additional Branch Management](#additional-branch-management)
4. [Notes](#notes)

---

## 🚀 Getting Started

### 1. Clone the Repository
First, clone your repository to your local machine. Use the following git command:

```bash
git clone https://github.com/codecrypto-admin/<your-github-username>.git
```
> Replace `<your-github-username>` with your GitHub username.

### 2. Navigate to Your Repository
Change your directory to the newly cloned repository:

```bash
cd <repository-name>
```

> Replace `<repository-name>` with the name of your repository.

---

## 🌿 Working with Branches

### 3. Create a New Branch
For each module or project, you will need to create a new branch. The module name project will be provided at the end. The branch name should follow this format:

- `web[x]-[provided-module-name]`

**Examples:** 
- `web2-nextjs`
- `web2.5-faucet`
- `web3-ethereum-erc-20`

To create a new branch, use the following command:

```bash
git checkout -b <branch-name>
```

**Example:**

```
git checkout -b web2.5-faucet
```

### 4. Work on Your Branch
Once on your branch, you can make changes, add files, and commit your work. For example:

```bash
# Add new files or make changes to existing ones
git add .
git commit -m "Added project files for <branch-name>"
```
> Replace `<branch-name>` with the appropriate module name.

### 5. Push Your Branch to GitHub
When you're ready to push your changes, use the following command:

```bash
git push origin <branch-name>
```

**Example:**

```
git push origin web2.5-faucet
```

---

## 🔄 Additional Branch Management

### 6. Switch to a Different Branch
If you need to switch between branches, use:

```bash
git checkout <branch-name>
```

### 7. Delete a Branch (Optional)
If you need to delete a branch locally or on GitHub after it's no longer needed, use:

- **Locally:**

  ```bash
  git branch -d <branch-name>
  ```

- **On GitHub:**

  ```bash
  git push origin --delete <branch-name>
  ```

---

## 📝 Notes

- **Main Branch:** The `main` branch serves as your public portfolio and is protected. You should not push any changes directly to the `main` branch.
- **Branch Naming:** Always name your branches according to the module or project you're working on.
- **Commits:** Make sure your commit messages are clear and descriptive.
