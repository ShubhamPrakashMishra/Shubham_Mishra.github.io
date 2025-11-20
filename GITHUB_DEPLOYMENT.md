# 🚀 GitHub Pages Deployment Guide

## Step-by-Step Instructions to Deploy Your Portfolio on GitHub

### Prerequisites
- A GitHub account ([Sign up free here](https://github.com/join))
- Your portfolio files in the `deploy` folder

---

## Method 1: Upload via GitHub Website (Easiest - No Git Required)

### Step 1: Create a New Repository
1. Go to [github.com](https://github.com) and log in
2. Click the **"+"** icon in the top-right corner
3. Select **"New repository"**
4. **Repository name:** `portfolio` (or any name you like)
   - For a personal site, use: `yourusername.github.io`
5. **Description:** "My Professional Portfolio"
6. Select **"Public"**
7. ✅ Check **"Add a README file"**
8. Click **"Create repository"**

### Step 2: Upload Your Files
1. In your new repository, click **"Add file"** → **"Upload files"**
2. Open your file explorer and go to:
   ```
   c:\Users\shubham\.vscode\resume-react\deploy\
   ```
3. **Drag and drop** these files into GitHub:
   - `index.html`
   - `style.css`
   - `resume.html` (if you have it)
4. Scroll down and click **"Commit changes"**

### Step 3: Enable GitHub Pages
1. In your repository, click **"Settings"** (tab at the top)
2. Scroll down and click **"Pages"** (in the left sidebar under "Code and automation")
3. Under **"Source"**, select:
   - Branch: **`main`** (or `master`)
   - Folder: **`/ (root)`**
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

### Step 4: Access Your Live Website! 🎉
Your portfolio will be available at:
- If repository name is `portfolio`: `https://yourusername.github.io/portfolio/`
- If repository name is `yourusername.github.io`: `https://yourusername.github.io/`

**Replace `yourusername` with your actual GitHub username!**

---

## Method 2: Using Git & Command Line (Advanced)

### Step 1: Install Git
1. Download Git from [git-scm.com](https://git-scm.com/)
2. Install with default settings

### Step 2: Initialize Repository
Open Command Prompt or PowerShell in your deploy folder:

```powershell
cd c:\Users\shubham\.vscode\resume-react\deploy
git init
git add .
git commit -m "Initial portfolio commit"
```

### Step 3: Create GitHub Repository
1. Create a new repository on GitHub (see Method 1, Step 1)
2. **Don't** initialize with README this time

### Step 4: Push to GitHub
Replace `yourusername` and `repository-name` with your actual values:

```powershell
git branch -M main
git remote add origin https://github.com/yourusername/repository-name.git
git push -u origin main
```

### Step 5: Enable GitHub Pages
Follow Method 1, Step 3

---

## 🔧 Updating Your Portfolio Later

### Via Website:
1. Go to your repository
2. Click on the file you want to edit (e.g., `index.html`)
3. Click the pencil icon (✏️) to edit
4. Make changes
5. Click "Commit changes"
6. Your site updates automatically in 1-2 minutes!

### Via Git:
```powershell
cd c:\Users\shubham\.vscode\resume-react\deploy
# Make your changes to files
git add .
git commit -m "Updated portfolio content"
git push
```

---

## 🌐 Custom Domain (Optional)

### If You Want Your Own Domain Name:
1. Buy a domain from services like:
   - Namecheap
   - GoDaddy
   - Google Domains
2. In GitHub repository → Settings → Pages
3. Enter your custom domain
4. Update DNS settings at your domain provider

---

## 📱 Testing Your Site

After deployment, test your portfolio:
- ✅ Click all links (email, LinkedIn, resume)
- ✅ Test on mobile device
- ✅ Check accordions work
- ✅ Verify all sections display correctly

---

## ⚠️ Common Issues & Solutions

### Issue: "404 Page Not Found"
**Solution:** Make sure your main file is named `index.html` (lowercase)

### Issue: "Site not updating"
**Solution:** 
1. Hard refresh your browser (Ctrl + Shift + R)
2. Wait 2-3 minutes for GitHub to rebuild
3. Check your commit went through

### Issue: "CSS not loading"
**Solution:** Make sure `style.css` is in the same folder as `index.html`

### Issue: "Resume link not working"
**Solution:** 
1. Make sure `resume.html` is uploaded
2. Or update the link in `index.html` to point to an external CV

---

## 🎯 Quick Checklist

- [ ] Created GitHub account
- [ ] Created new repository
- [ ] Uploaded `index.html`, `style.css`, and `resume.html`
- [ ] Enabled GitHub Pages in Settings
- [ ] Waited 2-3 minutes for deployment
- [ ] Visited your live site URL
- [ ] Tested all links and features
- [ ] Shared your portfolio URL!

---

## 📞 Need Help?

If you encounter any issues:
1. Check the [GitHub Pages documentation](https://docs.github.com/en/pages)
2. Verify all files are uploaded correctly
3. Make sure repository is set to "Public"
4. Clear browser cache and try again

---

**Your Portfolio URL Format:**
```
https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```

**Example:** If your username is `shubhammishra` and repository is `portfolio`:
```
https://shubhammishra.github.io/portfolio/
```

---

## ✨ Congratulations!

Once deployed, you can:
- ✅ Share your portfolio link on LinkedIn
- ✅ Add it to your resume
- ✅ Send it to potential employers
- ✅ Update content anytime by editing files on GitHub

**Your professional portfolio is now live on the internet! 🎉**
