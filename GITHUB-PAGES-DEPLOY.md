# GITHUB PAGES DEPLOYMENT GUIDE

Your portfolio is ready to deploy. Follow these steps to go live in minutes.

## Prerequisites

- GitHub account (free at github.com)
- Git installed on your computer (or use GitHub Desktop)
- Your portfolio files (already prepared)

---

## Method 1: Via GitHub Web Interface (Easiest)

### Step 1: Create a GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Enter repository name: `harriet-mutonyi-portfolio`
3. Choose **Public** (so the site is visible to everyone)
4. Check "Initialize this repository with a README" *(optional)*
5. Click **Create repository**

### Step 2: Upload Your Files

1. In the repository, click **Add file → Upload files**
2. Drag and drop your files:
   - `index.html`
   - `styles.css`
   - `photo.jpg` (once you add your photo)
3. Click **Commit changes**

### Step 3: Enable GitHub Pages

1. Go to **Settings** (top menu of your repo)
2. Click **Pages** (left sidebar)
3. Under "Build and deployment":
   - **Source:** Select `Deploy from a branch`
   - **Branch:** Select `main` and `/(root)`
4. Click **Save**

Your site will be published at:
```
https://YOUR-USERNAME.github.io/harriet-mutonyi-portfolio/
```

---

## Method 2: Via Git Command Line

### Step 1: Create Repository (GitHub web interface)

1. Go to [github.com/new](https://github.com/new)
2. Name: `harriet-mutonyi-portfolio`
3. Choose **Public**
4. Click **Create repository** (do NOT initialize with README)

### Step 2: Push Your Files

Copy and run these commands in your terminal (replace `YOUR-USERNAME`):

```bash
cd C:\Users\User\Desktop\harriet

git remote add origin https://github.com/YOUR-USERNAME/harriet-mutonyi-portfolio.git
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

Same as Method 1, Step 3 above.

---

## Method 3: Using GitHub Desktop (GUI)

1. Download [GitHub Desktop](https://desktop.github.com/)
2. In GitHub Desktop, click **File → New Repository**
3. Name: `harriet-mutonyi-portfolio`
4. Choose your portfolio folder as the location
5. Click **Create repository**
6. Click **Publish repository** (top right)
7. Ensure it's set to **Public**
8. Click **Publish**
9. Enable Pages in repository Settings (as described above)

---

## After Deployment

### Update Your Portfolio

1. Edit `index.html` or `styles.css` locally
2. Commit and push:
   ```bash
   git add .
   git commit -m "Update portfolio content"
   git push
   ```
3. Changes appear live in ~1-2 minutes

### Add Your Photo

1. Replace `photo.txt` with your `photo.jpg` (500x500px)
2. Commit and push:
   ```bash
   git add photo.jpg
   git commit -m "Add profile photo"
   git push
   ```

### Share Your Portfolio

Your live URL is:
```
https://YOUR-USERNAME.github.io/harriet-mutonyi-portfolio/
```

Share this link in:
- Email signature
- LinkedIn profile
- CV/Cover letter
- Professional bio

---

## Troubleshooting

**"Site not showing?"**
- Wait 2-3 minutes for GitHub Pages to build
- Clear your browser cache (Ctrl+Shift+Delete)
- Check that Pages is enabled in Settings

**"Photo not appearing?"**
- Ensure file is named exactly `photo.jpg`
- Restart your browser after uploading

**"Want a custom domain?"**
- In Settings → Pages, scroll to "Custom domain"
- Add your domain (requires DNS setup)

---

## Questions?

- GitHub Pages Help: https://pages.github.com/
- Contact: hmutonyi@yahoo.com

---

**Your portfolio is git-ready and waiting to go live!** 🚀
