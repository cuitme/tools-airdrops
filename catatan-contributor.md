# Contributor Guide

This guide will help you contribute to this project. Follow the steps below to set up your local environment, make changes, and submit a pull request.

## Steps to Contribute

### 1. Clone the Repository
Run the following command to clone the repository to your local machine:
```bash
git clone <repository-url>
```
**Example:**
```bash
git clone https://github.com/gerrywang1117/Arweave-Academy.git
```

### 2. Navigate to the Repository Folder
Move into the repository folder:
```bash
cd <repository-folder>
```
**Example:**
```bash
cd Arweave-Academy
```

### 3. Verify the Remotes
Ensure that you have the correct remotes set up:
```bash
git remote -v
```

### 4. Add the Upstream Remote
Add the original repository as an upstream remote:
```bash
git remote add upstream <original-repository-url>
```
**Example:**
```bash
git remote add upstream https://github.com/ArweaveOasis/Arweave-Academy.git
```

### 5. Fetch the Latest Changes
Fetch the latest changes from the upstream repository:
```bash
git fetch upstream main
```

### 6. Checkout a Branch
To switch to an existing branch, use the following command:
```bash
git checkout <branch-name>
```
**Example:**
```bash
git checkout feature-branch
```
To switch to the `dev` branch specifically:
```bash
git checkout dev
```
If you want to create a new branch and switch to it:
```bash
git checkout -b <new-branch-name>
```
**Example:**
```bash
git checkout -b new-feature
```

### 7. Stage Your Changes
Stage the files you have modified or added:
```bash
git add .
```

### 8. Commit Your Changes
Commit your changes with a descriptive message:
```bash
git commit -m "Description of changes"
```

### 9. Push Your Changes
Push your changes to your forked repository:
```bash
git push origin main
```

### 10. Create a Pull Request
1. Go to the original repository on GitHub.
2. Click the **Pull Requests** tab.
3. Click **Create Pull Request**.

### Notes
- Ensure your code follows the project's guidelines.
- Provide a clear and concise description of your changes in the pull request.
- Be responsive to any feedback from the maintainers.

Thank you for contributing!
