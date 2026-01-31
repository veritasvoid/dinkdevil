# 🚀 GitHub Setup Instructions

Follow these steps to get DinkDevil on GitHub:

## 1. Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `dinkdevil`
3. Description: "Pickleball tournament organizer and score tracker"
4. Choose: **Public**
5. ✅ Check "Add a README file" (we'll replace it)
6. ✅ Choose License: **MIT License**
7. Click "Create repository"

## 2. Upload Files

You have all these files ready:
- `index.html` - Main app file
- `README.md` - Documentation
- `LICENSE` - MIT license
- `.gitignore` - Git ignore rules
- `CONTRIBUTING.md` - Contribution guidelines

### Option A: GitHub Web Interface
1. Click "uploading an existing file"
2. Drag and drop all files
3. Commit message: "Initial commit - DinkDevil v1.0.0"
4. Click "Commit changes"

### Option B: Git Command Line
```bash
git clone https://github.com/YOUR-USERNAME/dinkdevil.git
cd dinkdevil
# Copy all your files here
git add .
git commit -m "Initial commit - DinkDevil v1.0.0"
git push origin main
```

## 3. Enable GitHub Pages

1. Go to repository **Settings**
2. Click **Pages** in left sidebar
3. Source: Deploy from branch
4. Branch: **main** / **root**
5. Click **Save**
6. Wait 1-2 minutes
7. Your site will be live at: `https://YOUR-USERNAME.github.io/dinkdevil/`

## 4. Update README

1. Edit README.md
2. Replace placeholder links:
   - Change `[Live Demo](#)` to your GitHub Pages URL
   - Change `yourusername` to your actual username
3. Add a screenshot if you want
4. Commit changes

## 5. Create First Release (Optional)

1. Go to **Releases**
2. Click "Create a new release"
3. Tag: `v1.0.0`
4. Title: "DinkDevil v1.0.0 - Initial Release"
5. Description: "First public release with rotating/set partners modes, multi-court support, and trophy podium leaderboard"
6. Click "Publish release"

## 6. Share!

Your app is now live! Share the link:
```
https://YOUR-USERNAME.github.io/dinkdevil/
```

---

## Next Steps (Optional)

- Add screenshots to README
- Create GitHub Issues for future features
- Enable GitHub Discussions for community
- Add topics/tags: `pickleball`, `tournament`, `score-tracker`, `pwa`

---

**That's it! You're live on GitHub!** 🎉
