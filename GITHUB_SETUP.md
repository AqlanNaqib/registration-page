# GitHub Setup Instructions

Your files have been committed to git! Now follow these steps to push to GitHub:

## Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **"+"** icon in the top right corner
3. Select **"New repository"**
4. Fill in the details:
   - **Repository name**: `registration-page` (or any name you prefer)
   - **Description**: HTML5 registration page with validation and modern styling
   - **Visibility**: Choose **Public** or **Private**
   - **DO NOT** initialize with README, .gitignore, or license (we already have these)
5. Click **"Create repository"**

## Step 2: Connect and Push Your Code

After creating the repository, GitHub will show you commands. Run these in your terminal:

```bash
git remote add origin https://github.com/YOUR-USERNAME/registration-page.git
git branch -M main
git push -u origin main
```

**Replace `YOUR-USERNAME` with your actual GitHub username.**

## Step 3: Update the GitHub Link in Your HTML

After pushing to GitHub, I can update the footer link in `index.html` to point to your repository. Just provide me with:
- Your GitHub username
- The repository name you chose

---

## Quick Commands Reference

```bash
# Navigate to project directory
cd "C:\Users\aqlan\OneDrive - Sheffield Hallam University\database & web module\registration_page"

# Check status
git status

# Add remote (after creating repo on GitHub)
git remote add origin https://github.com/YOUR-USERNAME/repo-name.git

# Push to GitHub
git push -u origin main
```

## Your Current Repository Info

- **Current branch**: master
- **Files committed**: index.html, style.css, README.md, .gitignore
- **Ready to push**: ✅ Yes

