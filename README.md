# Portfolio Deployment Guide

This folder contains your production-ready portfolio website files.

## 📁 Files Included

1. **index.html** - Main portfolio page (landing page)
2. **style.css** - Stylesheet with all design
3. **resume.html** - Your detailed CV (optional - upload if you want the "View Full Resume" button to work)

## 🚀 How to Upload to a Hosting Website

### Option 1: GitHub Pages (FREE)
1. Create a new repository on GitHub
2. Upload these files to the repository
3. Go to Settings → Pages
4. Select "main" branch and click Save
5. Your site will be live at `https://yourusername.github.io/repository-name/`

### Option 2: Netlify (FREE)
1. Go to [netlify.com](https://netlify.com)
2. Sign up for free
3. Drag and drop this entire `deploy` folder
4. Your site goes live instantly!
5. You get a free subdomain like `yourname.netlify.app`

### Option 3: Vercel (FREE)
1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Import your project
4. Deploy with one click

### Option 4: Traditional Web Hosting (cPanel/FTP)
1. Log into your hosting control panel
2. Navigate to File Manager or use FTP client (like FileZilla)
3. Upload all files to your `public_html` or `www` folder
4. Access your site at your domain name

## ⚙️ Configuration Before Upload

### Update LinkedIn URL (if needed)
In `index.html`, find line 48 and update:
```javascript
linkedin: "https://www.linkedin.com/in/YOUR-ACTUAL-LINKEDIN-USERNAME",
```

### Update CV Link (if needed)
- If you upload `resume.html`, the link will work automatically
- If you want to link to an external CV, update line 49:
```javascript
cvLink: "https://your-cv-url.com/resume.pdf"
```

## 🌐 External Dependencies (Already Included via CDN)
- React 18 (production build)
- Font Awesome 6.4.0
- Google Fonts (Inter & Roboto Mono)

All dependencies load from CDN, so no installation needed!

## 📱 Features
✅ Fully responsive (mobile, tablet, desktop)
✅ SEO optimized with meta tags
✅ Fast loading with production React
✅ Clickable email and LinkedIn links
✅ Interactive accordions
✅ Professional green and blue color scheme

## 🎨 Customization
To change colors, edit `style.css`:
- Green header: Line 64
- Blue section titles: Line 196
- Background gradient: Line 37

## 📞 Support
If you need help deploying, let me know which hosting platform you're using!

---
**Last Updated:** November 2025
**Version:** 1.0
