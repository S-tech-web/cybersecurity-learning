# Git Setup Lab Report

## Objective

To set up Git and GitHub on Ubuntu and successfully connect a local repository to a remote GitHub repository using SSH authentication.

---

## Tools Used

* Ubuntu Linux
* Git
* GitHub account
* SSH (Secure Shell)

---

## Steps Performed

### 1. Git Installation Check

Verified Git is installed:

```bash
git --version
```

---

### 2. Git Identity Setup

Configured Git username and email:

```bash
git config --global user.name "S-tech-web"
git config --global user.email "surajsl1092@gmail.com"
```

Checked configuration:

```bash
git config --global --list
```

---

### 3. SSH Key Setup

Generated SSH key for secure authentication:

```bash
ssh-keygen -t ed25519 -C "surajsl1092@gmail.com"
```

Started SSH agent:

```bash
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
```

Copied SSH public key:

```bash
cat ~/.ssh/id_ed25519.pub
```

Added it to GitHub:
GitHub → Settings → SSH and GPG Keys → New SSH Key

---

### 4. Repository Setup

Cloned or linked local repository:

```bash
git remote add origin git@github.com:S-tech-web/cybersecurity-learning.git
```

Verified remote:

```bash
git remote -v
```

---

### 5. First Commit and Push

Staged files:

```bash
git add .
```

Committed changes:

```bash
git commit -m "Day 1 networking fundamentals"
```

Pushed to GitHub:

```bash
git push -u origin main
```

---

## Result

* Git successfully configured
* SSH authentication established
* First commit pushed to GitHub
* Local repository connected to remote repository

---

## Key Learnings

* Git tracks changes in code and files
* SSH provides secure password-less authentication
* GitHub stores remote repositories
* `git add`, `git commit`, and `git push` are core Git workflow commands

---

## Conclusion

The Git setup was successfully completed on Ubuntu. The local machine is now securely connected to GitHub using SSH, and the first project has been pushed successfully.
