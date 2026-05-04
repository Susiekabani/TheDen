# GitHub Setup & Deployment Guide

## Getting Started with GitHub

This guide will help you set up The Den Dragon Package repository on GitHub.

---

## Step 1: Create a New GitHub Repository

1. Go to [github.com](https://github.com) and log in
2. Click **"New"** (top left, next to your profile)
3. Fill in repository details:
   - **Repository name:** `the-den-dragon-package`
   - **Description:** "Professional briefing and evaluation system for The Den inaugural event judges"
   - **Visibility:** Public (so Dragons can access it easily) or Private (if restricted access preferred)
   - **Initialize with:** Don't add a README yet (we have one)

4. Click **"Create repository"**

---

## Step 2: Upload Files to GitHub

### Option A: Using Git Command Line (Recommended)

```bash
# Clone the repository to your local machine
git clone https://github.com/YOUR-USERNAME/the-den-dragon-package.git
cd the-den-dragon-package

# Copy all files from the outputs folder into this directory
# (Files: index.html, README.md, .gitignore, and all Word/Excel/HTML docs)

# Stage all files
git add .

# Create initial commit
git commit -m "Initial commit: Complete Dragon Package for inaugural Den event"

# Push to GitHub
git push origin main
```

### Option B: Using GitHub Web Interface (Easiest)

1. Go to your new repository
2. Click **"Add file"** → **"Upload files"**
3. Drag and drop all files from `/outputs` folder
4. Write commit message: `"Add complete Dragon Package files"`
5. Click **"Commit changes"**

---

## Step 3: Enable GitHub Pages (For Easy Access)

GitHub Pages allows people to view your HTML files directly in their browser.

1. Go to repository **Settings**
2. Scroll to **"Pages"** section
3. Under **"Source"**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **"Save"**

**Your site will be live at:**  
`https://YOUR-USERNAME.github.io/the-den-dragon-package/`

---

## Step 4: Share Access with Dragons

### Public Repository
Send Dragons this link:
```
https://github.com/YOUR-USERNAME/the-den-dragon-package
```

They can:
- View all documents
- Download files individually
- Clone the entire repository

### GitHub Pages Link
For easy browsing without Git knowledge:
```
https://YOUR-USERNAME.github.io/the-den-dragon-package/
```

---

## File Structure on GitHub

Your repository should look like this:

```
the-den-dragon-package/
├── README.md                                    (Main documentation)
├── GITHUB_SETUP.md                              (This file)
├── .gitignore                                   (Git ignore rules)
├── index.html                                   (Master index)
├── The_Den_Dragon_Package.html                  (Website)
├── The_Den_Dragon_Briefing_Pack.docx            (Word doc)
├── The_Den_Scoring_Rubric_Explained.docx        (Word doc)
├── The_Den_Dragon_Scoresheet.xlsx               (Excel file)
├── The_Den_Event_Overview_Dragon_Guide.docx     (Word doc)
└── [Optional] docs/                             (Additional documentation folder)
    └── SCORING_GUIDE.md                         (Optional extra guide)
```

---

## Downloading Files from GitHub

### For Dragons

**To download individual files:**
1. Click the file in the repository
2. Click the **"Download raw file"** button (or right-click "Save as")

**To download everything:**
1. Click the green **"Code"** button
2. Click **"Download ZIP"**
3. Extract on your computer

---

## Updating Files on GitHub

If you need to make changes:

### Small Changes (via Web):
1. Click the file in GitHub
2. Click the **pencil icon** (Edit)
3. Make changes
4. Click **"Commit changes"**

### Large Changes (via Git):
```bash
git pull origin main
# Make local changes
git add .
git commit -m "Update: [describe what changed]"
git push origin main
```

---

## Best Practices

### ✅ Do This

- Use descriptive commit messages: `"Add Dragon Scoresheet with built-in criteria"`
- Update README.md if you add new files
- Keep folder structure simple and flat
- Include file descriptions in README.md

### ❌ Don't Do This

- Don't commit large temporary files
- Don't upload personal notes or drafts
- Don't remove the README.md or .gitignore
- Don't change file names (links will break)

---

## Useful GitHub Features

### Releases
Create a release for the event:

1. Go to **Releases** (right sidebar)
2. Click **"Create a new release"**
3. Tag: `v1.0-inaugural-den`
4. Title: `"Complete Dragon Package - Inaugural Den Event"`
5. Describe: Add event date, contents, notes
6. Upload files or link to repository
7. Publish release

### Collaborators
If others need edit access:

1. Go to **Settings** → **Collaborators**
2. Click **"Add people"**
3. Search for GitHub username
4. Select permission level (maintain or push)

### Issues & Discussions
For Dragons to ask questions:

1. Enable **"Discussions"** (if public repo)
2. Dragons can ask questions in Discussions
3. You respond with clarifications

---

## Creating a Website Landing Page

You already have `index.html` and `The_Den_Dragon_Package.html`.

When GitHub Pages is enabled, visiting:
```
https://YOUR-USERNAME.github.io/the-den-dragon-package/
```

Will automatically serve `index.html` as the home page.

---

## Troubleshooting

### Pages Not Loading
- Wait 1–2 minutes for GitHub to deploy
- Check that `index.html` is in the root folder
- Verify GitHub Pages is enabled in Settings

### Files Not Showing
- Clear browser cache (Ctrl+Shift+Delete or Cmd+Shift+Delete)
- Check file names match exactly (case-sensitive on Linux/Mac)

### Download Issues
- Try downloading as ZIP instead
- Check your browser's download settings

---

## SEO & Discoverability

To help Dragons find your repository:

1. Add descriptive tags (repository topics)
2. In Settings → **"About"** section, add a short description
3. Add keywords like: `entrepreneurship`, `dragons-den`, `dragon-investors`, `startup-evaluation`

---

## Version Control for Future Events

For future Den events, create branches:

```bash
git checkout -b den-2027
# Make updates for 2027 event
git push origin den-2027
```

Keep the `main` branch as the original for reference.

---

## Access & Permissions

### If You Want Public Access
- Repository visibility: **Public**
- Anyone can view and download files
- GitHub Pages: Automatically public

### If You Want Limited Access
- Repository visibility: **Private**
- Add collaborators only
- GitHub Pages: Still available but requires authentication if you prefer
- Share link only with Dragons

---

## Support & Help

**GitHub Help:**
- GitHub Docs: https://docs.github.com
- GitHub Community: https://github.com/orgs/community/discussions

**For This Package:**
- Refer to README.md for content questions
- Review the index.html for usage guidance

---

## Checklist Before Going Live

- [ ] All 6 files uploaded to repository
- [ ] README.md is comprehensive and error-free
- [ ] .gitignore file is present
- [ ] GitHub Pages enabled (if using custom domain)
- [ ] Repository description filled in
- [ ] Topics/tags added
- [ ] Links tested (if you created any)
- [ ] Collaborators added (if applicable)
- [ ] You've tested viewing on mobile and desktop

---

## Next Steps

1. **Create the repository** using steps above
2. **Upload all files** (Option A or B)
3. **Enable GitHub Pages** for easy access
4. **Share the link** with Dragons
5. **Monitor for questions** (via Issues/Discussions if enabled)

---

**Ready to share The Den Dragon Package with the world!** 🎯

Your Dragons will have everything they need, easily accessible, professionally presented, and ready to use.
