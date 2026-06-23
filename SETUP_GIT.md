# Git & GitHub Setup Guide

## Local Git Initialization

Run these commands in the project root (`E:\ClaudeOS\PROJECTS\stunning-website`):

```bash
# Initialize repository
git init

# Set user config (one-time)
git config user.name "Rama"
git config user.email "remopdj04@gmail.com"

# Stage all files
git add .

# Create initial commit
git commit -m "Initial commit: Apex Creative portfolio website"

# Check status
git log --oneline
```

## Push to GitHub

1. **Create repository on GitHub** at [github.com/new](https://github.com/new)
   - Repository name: `stunning-website`
   - Description: "Premium creative agency portfolio — Apex Creative"
   - Public or Private (your choice)
   - Do NOT initialize with README, .gitignore, or license

2. **Connect remote and push**:
   ```bash
   # Replace YOUR_USERNAME with your actual GitHub username
   git remote add origin https://github.com/YOUR_USERNAME/stunning-website.git
   
   # Rename branch to main if needed
   git branch -M main
   
   # Push to GitHub
   git push -u origin main
   ```

3. **Verify** — Visit `https://github.com/YOUR_USERNAME/stunning-website` to confirm

## Subsequent Commits

```bash
# After making changes
git add .
git commit -m "Description of changes"
git push
```

## If Git Already Initialized

If you see "fatal: not a git repository", the folder may have a corrupted .git folder. Fix with:

```bash
# Back up your files first
mkdir backup
xcopy * backup\ /S

# Remove broken .git
rmdir /S /Q .git

# Re-initialize
git init
git config user.name "Rama"
git config user.email "remopdj04@gmail.com"
git add .
git commit -m "Initial commit: Apex Creative portfolio website"
```

Then connect to GitHub as above.
