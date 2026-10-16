# Quick Setup Guide: CALD Forum Website

## ✅ What You Have

Your website files are ready:
- ✅ `index.html` - Main website with all sections
- ✅ `styles.css` - Modern, responsive styling
- ✅ `script.js` - Interactive features
- ✅ `README.md` - Full documentation
- ✅ `.gitignore` - Git configuration

## 📋 Next Steps (5 minutes)

### Step 1: Generate Your QR Code (2 min)

The website expects a file called `qr-code.png` in the project directory.

**Option A: Use Free Online QR Code Generator**

1. Go to: https://qr-code-generator.com
2. Paste your registration form URL:
   ```
   https://docs.google.com/forms/d/1efc4Xc74nRmJgpsNSfdbroWt_7QIdQW5B2R50PG2AyM/edit?ts=6ab9f43e
   ```
3. Click "Generate"
4. Download as PNG image
5. Rename to `qr-code.png`
6. Save to your `/Users/tarek/CALD/` directory

**Option B: Use Google Charts API**

You can also reference the QR code directly by URL. In `index.html`, find the QR code line and replace it with:

```html
<img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https%3A%2F%2Fdocs.google.com%2Fforms%2Fd%2F1efc4Xc74nRmJgpsNSfdbroWt_7QIdQW5B2R50PG2AyM%2Fedit%3Fts%3D6ab9f43e" alt="Registration QR Code" class="qr-code">
```

### Step 2: Test Locally (1 min)

1. Open the `/Users/tarek/CALD/` folder in your file explorer
2. Double-click `index.html` to open it in your browser
3. Check that all sections load correctly
4. Test the navigation links
5. Verify the QR code appears (if you added it)

### Step 3: Create GitHub Repository (1 min)

1. Go to **GitHub.com** and log in to your account
2. Click the **+** icon → **New repository**
3. Name it: **`cald-uq.github.io`**
   - ⚠️ Must be exactly this name (replace `cald-uq` with your actual org name if needed)
4. Select **Public**
5. Click **Create repository**
6. Copy the repository URL (looks like: `https://github.com/YOUR-USERNAME/cald-uq.github.io.git`)

### Step 4: Push to GitHub (1 min)

Open Terminal and run these commands:

```bash
# Navigate to your project directory
cd /Users/tarek/CALD

# Initialize git (if not already done)
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit: CALD HDR forum website"

# Add your GitHub repository
git remote add origin https://github.com/YOUR-USERNAME/cald-uq.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 5: Enable GitHub Pages (1 min)

1. Go to your repository on GitHub: `https://github.com/YOUR-USERNAME/cald-uq.github.io`
2. Click **⚙️ Settings**
3. Click **Pages** (in the left sidebar)
4. Under "Source", select **Deploy from a branch**
5. Select **main** and **/ (root)**
6. Click **Save**

## 🎉 You're Done!

Your website will be live at: **https://cald-uq.github.io**

(It may take 1-2 minutes to fully deploy. Refresh your browser if it shows a 404.)

## 🔄 Making Updates

To make changes to your website:

1. Edit the files locally (HTML, CSS, or JavaScript)
2. Save the changes
3. Commit and push:
   ```bash
   git add .
   git commit -m "Update: describe your changes"
   git push
   ```
4. GitHub Pages will automatically rebuild your site (usually within seconds)

## 🎨 Quick Customizations

### Change the Colors

Edit `styles.css` and look for this section:

```css
:root {
    --primary-color: #00539b;      /* Change this for main color */
    --secondary-color: #e74c3c;    /* Change this for accent color */
    --accent-color: #3498db;       /* Change this for light blue */
}
```

Find colors at: https://htmlcolorcodes.com

### Update Committee Members

In `index.html`, find the "Contact Section" and update the names and titles.

### Add Real Events

In the `<!-- Events Section -->`, replace the placeholder with actual event details.

### Update Text Content

Search for any text you want to change directly in `index.html` and edit it.

## 🆘 Troubleshooting

**Q: Website shows 404 error**
- A: Wait 2 minutes for GitHub Pages to deploy, then refresh
- A: Check that your repository is named exactly `cald-uq.github.io`

**Q: QR code doesn't appear**
- A: Make sure `qr-code.png` is in the same directory as `index.html`
- A: Try the Google Charts API option in Step 1

**Q: Changes aren't showing up**
- A: Hard refresh your browser: `Cmd+Shift+R` (Mac) or `Ctrl+Shift+R` (Windows)
- A: Wait a few seconds for GitHub Pages to rebuild

**Q: Git commands don't work**
- A: Install Git: https://git-scm.com/download
- A: Or use GitHub Desktop: https://desktop.github.com

## 📞 Need Help?

- **Git/GitHub Help**: https://docs.github.com
- **GitHub Pages Guide**: https://pages.github.com
- **HTML/CSS Reference**: https://developer.mozilla.org/en-US/docs/Web/

---

**Ready to go live?** Start with Step 1 above! 🚀
