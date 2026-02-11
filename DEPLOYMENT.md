# GitHub Pages Deployment Guide

## Quick Setup (5 minutes)

### Step 1: Initialize Git (if not already done)
```bash
cd portfolio
git init
git add .
git commit -m "Initial portfolio commit"
```

### Step 2: Create GitHub Repository
1. Go to [github.com/new](https://github.com/new)
2. Repository name: `denisepayumo.github.io` (this is important for GitHub Pages)
3. Make it **Public**
4. Click "Create repository"

### Step 3: Push to GitHub
```bash
# Add the remote (replace USERNAME with your GitHub username)
git remote add origin https://github.com/denisepayumo/denisepayumo.github.io.git

# Push to main branch
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select `main` branch
4. Save

**Your site will be live at:** `https://denisepayumo.github.io`

---

## Deploying Updates
Every time you make changes:
```bash
git add .
git commit -m "Update: describe your changes"
git push origin main
```

Changes will be live within 1-2 minutes.

---

## Optional: Custom Domain (adventurecode.dev, etc.)
If you have a custom domain:

1. In GitHub Repository → Settings → Pages
2. Add your custom domain under "Custom domain"
3. Update your domain's DNS records (instructions vary by provider)

---

## Project Structure
```
denisepayumo.github.io/
├── index.html          (Main page)
├── styles.css          (All styling)
├── script.js           (Interactivity)
├── assets/             (Images, files)
└── README.md           (This file)
```

---

## Key Features Deployed
✅ Mobile-responsive design  
✅ Dark/light mode support  
✅ Smooth animations & transitions  
✅ Fast load time (vanilla JS, no frameworks)  
✅ SEO-optimized semantic HTML  
✅ Performance-optimized (lazy loading)  

---

## Troubleshooting

### Site not showing after push?
- Wait 1-2 minutes
- Check Settings → Pages to confirm it's set to `main` branch
- Clear your browser cache (Ctrl+Shift+Delete)

### Want to test locally before pushing?
```bash
# Use Python's built-in server
python -m http.server 8000
# Then visit http://localhost:8000
```

---

## Social Links & Integrations Already Added
- LinkedIn: https://linkedin.com/in/denisepayumo
- GitHub: [Add your GitHub username in index.html]
- Instagram: @dpdigitals
- Itch.io: https://dcp2.itch.io/
- Adventure Catalyst: https://adventurecatalyst.net/

**Update the GitHub link in index.html line ~320 with your username.**

---

## Next Steps (After Deployment)
1. **Share with recruiters** - Add link to LinkedIn, resume, email signature
2. **Update frequently** - Add new projects as you complete them
3. **SEO boost** - Submit sitemap to Google Search Console
4. **Monitor analytics** - Add Google Analytics (optional)

---

**Portfolio built with HTML5 + CSS3 + Vanilla JavaScript**
No frameworks. No bloat. Just skill.
