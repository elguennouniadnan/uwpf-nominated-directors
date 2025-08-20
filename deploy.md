# GitHub Pages Deployment Instructions

## Step 1: Create GitHub Repository
1. Go to https://github.com
2. Click the "+" icon in top right corner
3. Select "New repository"
4. Repository name: `wpf-nominees` (or any name you prefer)
5. Make it **Public** (required for free GitHub Pages)
6. Don't initialize with README (we already have files)
7. Click "Create repository"

## Step 2: Connect Local Repository to GitHub
After creating the repository, GitHub will show you commands. Run these in your terminal:

```bash
git remote add origin https://github.com/YOUR_USERNAME/wpf-nominees.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username.

## Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

## Step 4: Your Site Will Be Live
Your site will be available at:
`https://YOUR_USERNAME.github.io/wpf-nominees/`

It may take a few minutes to deploy initially.

## Quick Alternative: Use Netlify Drop
If you want to deploy right now without GitHub:
1. Go to https://app.netlify.com/drop
2. Drag your entire project folder onto the page
3. Your site will be live instantly!
