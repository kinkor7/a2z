# How to Upload A2Z to GitHub

Follow these steps to upload the A2Z project to your GitHub account.

## Step 1: Create a New Repository on GitHub
1. Go to [github.com/new](https://github.com/new).
2. Repository name: `a2z`
3. Set it to **Public** or **Private** based on your preference.
4. **Do NOT** initialize with a README, license, or .gitignore.
5. Click **Create repository**.

## Step 2: Upload the Code via Terminal (Terminator)
Open your Terminator app and run these commands one by one:

```bash
# 1. Navigate to the a2z project folder
cd /Users/ag700/Downloads/RE/a2z

# 2. Initialize the git repository
git init

# 3. Add all files to the staging area
git add .

# 4. Commit the changes
git commit -m "Initial commit: A2Z Project replication"

# 5. Rename the branch to main
git branch -M main

# 6. Link the local repo to your GitHub repo
git remote add origin https://github.com/kinkor7/a2z.git

# 7. Push the code to GitHub
git push -u origin main
```

## Troubleshooting
- **Authentication**: If asked for a password, use your **GitHub Personal Access Token (PAT)**.
- **Permission Denied**: Ensure you have the correct permissions for the `kinkor7` account.
