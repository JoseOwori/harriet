# Dr. Harriet Mutonyi — Professional Portfolio Website

A clean, responsive static portfolio website built with HTML and CSS, ready to deploy to GitHub Pages.

## Features

✓ **Responsive Design** — Works perfectly on mobile, tablet, and desktop  
✓ **Professional Colors** — Custom blue and gold palette reflecting academic excellence  
✓ **Photo Support** — Circular profile photo with elegant styling  
✓ **Print-Friendly** — Convert to PDF directly from browser  
✓ **GitHub Pages Ready** — Deploy to live website in minutes  
✓ **Accessibility** — Semantic HTML and proper link semantics  

## Files Included

- `index.html` — Main portfolio page with all sections
- `styles.css` — Responsive styles with custom color palette
- `photo.jpg` — *Placeholder* (replace with your professional photo)
- `.gitignore` — Git configuration
- `README.md` — This file

## Local Viewing

1. Open `index.html` directly in your browser (double-click the file)
2. To view locally with a live server (optional):
   ```bash
   python -m http.server 8000
   # or with Node.js:
   npx http-server
   ```
3. Visit `http://localhost:8000` in your browser

## Add Your Photo

1. Replace `photo.jpg` with your professional portrait (500x500px JPG recommended)
2. Save it in the same folder as `index.html`
3. The site will automatically display it in the header

## Deploy to GitHub Pages

### Option 1: Quick Deploy (Recommended)

1. **Create a GitHub repository:**
   - Go to [github.com/new](https://github.com/new)
   - Name it: `harriet-mutonyi-portfolio` (or your preferred name)
   - Choose "Public" so the site is visible
   - Click "Create repository"

2. **Push your files to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/harriet-mutonyi-portfolio.git
   git push -u origin main
   ```
   *(Replace `YOUR-USERNAME` with your actual GitHub username)*

3. **Enable GitHub Pages:**
   - Go to your repository settings: `Settings → Pages`
   - Under "Build and deployment," select:
     - Source: `Deploy from a branch`
     - Branch: `main` / `/(root)`
   - Click "Save"
   - Your site will be live at: `https://YOUR-USERNAME.github.io/harriet-mutonyi-portfolio/`

### Option 2: Using GitHub Desktop

1. Click "Code" on your new repository and open with GitHub Desktop
2. Clone the repo to your computer
3. Copy `index.html`, `styles.css`, and `photo.jpg` into the folder
4. Commit and push from GitHub Desktop
5. Enable Pages in repository settings as described above

## Customize

### Change Colors

Edit `styles.css` and update the CSS variables at the top:
```css
:root {
  --primary: #1a5490;        /* Main blue */
  --accent: #d4a574;          /* Gold accent */
  --text: #2c3e50;            /* Text color */
  /* ... other colors ... */
}
```

### Add Sections

Edit `index.html` to add new sections. Example:
```html
<section id="awards" class="card">
  <h2>Awards &amp; Recognition</h2>
  <ul>
    <li>Your award here</li>
  </ul>
</section>
```

### Update Content

Simply edit `index.html` with your text editor. All changes will appear when you refresh the browser.

## Convert to PDF

1. Open your portfolio website (local or GitHub Pages)
2. Press `Ctrl+P` (or `Cmd+P` on Mac)
3. Click "Save as PDF"
4. Choose your location and download

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Next Steps

- [ ] Add your professional photo (`photo.jpg`)
- [ ] Test locally by opening `index.html`
- [ ] Create GitHub repo and push files
- [ ] Enable GitHub Pages in repository settings
- [ ] Share your live portfolio URL
- [ ] Consider adding a contact form (optional)

## Support

For GitHub Pages issues, see: https://pages.github.com/  
For HTML/CSS edits, edit files in your text editor and refresh the browser.

---

**Last Updated:** February 2026  
**Deployed via:** Static HTML + CSS, GitHub Pages
