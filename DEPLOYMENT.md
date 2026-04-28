# Deploy to GitHub Pages - Step by Step

Follow these exact steps to push your Kenya Youth Dashboard to GitHub Pages. **Total time: 10 minutes.**

## Prerequisites
- Git installed on your computer
- A GitHub account
- This project folder (`kenya-youth-dashboard`)

## Steps

### 1. Create a New Repository on GitHub

1. Go to github.com and log in
2. Click the **+** icon (top right) → **New repository**
3. Repository name: **`kenya-youth-dashboard`**
4. Description: "Interactive data analysis dashboard for Kenya youth employment and opportunity mapping"
5. Make it **Public** (so Mastercard Foundation can access it)
6. Click **Create repository**
7. GitHub will show you commands — copy your repo URL (looks like `https://github.com/YOUR-USERNAME/kenya-youth-dashboard.git`)

### 2. Open Terminal/Command Prompt

Navigate to your project folder:
```bash
cd /path/to/kenya-youth-dashboard
```

### 3. Initialize Git & Push Code

**Copy and paste these commands one by one:**

```bash
# Initialize git in this folder
git init

# Add all files to git
git add .

# Create your first commit
git commit -m "Initial commit: Kenya Youth Opportunity Dashboard with 42 counties analysis"

# Add the remote repository (replace YOUR-USERNAME)
git remote add origin https://github.com/YOUR-USERNAME/kenya-youth-dashboard.git

# Rename branch to main (GitHub's default)
git branch -M main

# Push to GitHub
git push -u origin main
```

**After `git push`, you'll be asked for your GitHub credentials:**
- Username: your GitHub username
- Password: your GitHub personal access token (or password if enabled)

✅ **If you see no errors, you're live on GitHub!**

### 4. Enable GitHub Pages

1. Go to your repo on GitHub: `https://github.com/YOUR-USERNAME/kenya-youth-dashboard`
2. Click **Settings** (top right)
3. Scroll to **Pages** (left sidebar)
4. Under "Source," select **Deploy from a branch**
5. Select branch: **main**
6. Select folder: **root** (where your index.html is)
7. Click **Save**

**Wait 1-2 minutes for GitHub to build your site.**

### 5. Access Your Live Dashboard

Your dashboard is now live at:
```
https://YOUR-USERNAME.github.io/kenya-youth-dashboard/
```

That's the link you'll share with Mastercard Foundation reviewers!

---

## Troubleshooting

**"git: command not found"**
- Install Git from https://git-scm.com/

**"fatal: not a git repository"**
- Make sure you're in the correct folder: `cd kenya-youth-dashboard`
- Run `git init` again

**"Authentication failed"**
- Use a Personal Access Token instead of your GitHub password:
  1. Go to github.com → Settings → Developer settings → Personal access tokens
  2. Generate a new token (select `repo` scope)
  3. Copy the token and paste it as your password when git asks

**GitHub Pages not showing after 5 minutes**
- Check Settings → Pages to confirm the deployment source is correct
- Clear your browser cache (Ctrl+Shift+Del) and refresh

**My dashboard looks broken**
- Try opening `index.html` locally first: double-click it in your file explorer
- If it works locally but not on GitHub Pages, file a test issue in the repo

---

## After Deployment: Next Steps

1. **Screenshot the dashboard** for your portfolio
2. **Share the GitHub Pages link** in your Mastercard Foundation application
3. **Reference it in your cover letter:**
   > "I've built an interactive analysis dashboard identifying youth employment opportunities across Kenya's 42 counties, directly aligned with Young Africa Works priorities. The dashboard is live at [link] and demonstrates my ability to translate data into decision-support tools."
4. **In your portfolio**, add a project card linking to both the GitHub repo and the live dashboard

---

## For Option 2 (Tableau + Python)

After this is live, we'll build the same analysis in Tableau using a Python script that pulls the data. You'll have both versions to demonstrate depth.

Good luck! 🚀
