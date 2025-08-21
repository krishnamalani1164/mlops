# Git & GitHub Learning Guide

## BASICS REQUIRED BEFORE MOVING TO MLOPS

### 1. Git is a VCS/SCM

### 2. What is the need? Why should we learn?
- Bug fixing and version control
- Collaboration  
- Nonlinear development

### 3. Download/install from git-scm.com

## BASIC SETUP

### Defining the user name
```bash
git config --global user.name Vikash
```

### Defining the email
```bash
git config --global user.email vikashdas770@gmail.com
```

### Check your user name
```bash
git config --global user.name
```

### Check your email
```bash
git config --global user.email
```

## Terminal Session Example

<img width="917" height="408" alt="Screenshot 2025-08-20 114305" src="https://github.com/user-attachments/assets/100bbb15-cf0a-42d1-81ec-dfaf3b30905b" />

## Git Architecture

<img width="706" height="395" alt="Screenshot 2025-08-20 114404" src="https://github.com/user-attachments/assets/4267b999-f7a8-4e8a-bfb5-e9b685c5c5c5" />

## Git Workflow Example

### Step 1: Basic Git Areas

- **Workspace**: Where you create and modify files
- **Staging**: Temporary area to prepare files for commit
- **Local Repo**: Your local Git database
- **Remote Repo**: GitHub/GitLab server repository

### Step 2: Git Operations Flow

1. **untracked** → Files created but not added to Git
2. **Staging** → Files added with `git add` command
3. **commit** → Files saved to Local Repo with `git commit`
4. **push** → Files uploaded to Remote Repo with `git push`

### Simple Example:
```bash
# 1. Create a file in workspace
echo "Hello World" > hello.txt

# 2. Add to staging area
git add hello.txt

# 3. Commit to local repo
git commit -m "Add hello.txt file"

# 4. Push to remote repo (GitHub)
git push origin main
```
