# The Den Dragon Package - GitHub Deployment Guide

## 🚀 Quick Setup (5 minutes)

### Step 1: Upload Files to GitHub

1. Go to your repository: `https://github.com/Susiekabani/TheDen`
2. Click **"Add file" → "Upload files"**
3. Select ALL files from your outputs folder:
   - ✅ `dragon-complete-package.html`
   - ✅ `The_Den_Dragon_Scoresheet.xlsx`
   - ✅ `The_Den_Scoring_Rubric_Explained.docx`
   - ✅ `The_Den_Master_Print_Pack.docx`
   - ✅ `The_Den_Dragon_Briefing_Pack.docx`
   - ✅ `The_Den_Event_Overview_Dragon_Guide.docx`
   - ✅ `README.md`
   - ✅ `index.html`
   - ✅ (and any other reference HTML files)

4. Click **"Commit changes"**

### Step 2: Enable GitHub Pages

1. Go to your repository **Settings** (top right)
2. Click **"Pages"** (left sidebar)
3. Under "Build and deployment":
   - **Source:** Select "Deploy from a branch"
   - **Branch:** Select "main" 
   - **Folder:** Select "/ (root)"
4. Click **"Save"**

GitHub will now build your site. In 1-2 minutes, your site will be live at:
```
https://Susiekabani.github.io/TheDen/
```

### Step 3: Share with Dragons

Send Dragons this link:
```
https://Susiekabani.github.io/TheDen/dragon-complete-package.html
```

---

## 📥 How Downloads Work

When Dragons click the download buttons in `dragon-complete-package.html`, files will download directly from your GitHub repository:

- **Scoresheet Download:** Links to `The_Den_Dragon_Scoresheet.xlsx`
- **Files on GitHub:** All `.docx` and `.xlsx` files are stored in your root folder

**This works because:**
- GitHub allows direct file downloads from the root directory
- The HTML links use relative paths: `href="filename.xlsx"`
- When on GitHub Pages, these resolve to the correct file location

---

## 🎯 Dragons' Journey

1. **Before Event:** Dragons visit the site
   ```
   https://Susiekabani.github.io/TheDen/dragon-complete-package.html
   ```

2. **They can:**
   - ✅ Read all content online (no download needed)
   - ✅ Click navigation to jump between sections
   - ✅ Download Scoresheet (Excel) to familiarize themselves
   - ✅ Download other documents as needed

3. **On Event Night:**
   - ✅ They receive printed `The_Den_Master_Print_Pack.docx`
   - ✅ They receive `The_Den_Dragon_Scoresheet.xlsx` (printed or digital)
   - ✅ They have the Scoring Rubric in hand

---

## 📋 Files Included in Your Repository

### Primary Files (Dragons Use These)
| File | Purpose |
|------|---------|
| `dragon-complete-package.html` | Interactive guide (view in browser) |
| `The_Den_Dragon_Scoresheet.xlsx` | Scoring template |
| `The_Den_Scoring_Rubric_Explained.docx` | Detailed scoring guide |

### Supporting Files (For Reference)
| File | Purpose |
|------|---------|
| `The_Den_Master_Print_Pack.docx` | Print this on event night |
| `The_Den_Dragon_Briefing_Pack.docx` | Complete briefing document |
| `The_Den_Event_Overview_Dragon_Guide.docx` | Event playbook |
| `README.md` | Landing page content |
| `index.html` | Master index |

---

## ✅ Verification Checklist

- [ ] All files uploaded to GitHub
- [ ] GitHub Pages enabled (Settings → Pages)
- [ ] Site builds successfully (check GitHub Actions)
- [ ] Visit your site: `https://Susiekabani.github.io/TheDen/`
- [ ] Click a download button to verify files download
- [ ] Share link with Dragons

---

## 🔧 Troubleshooting

### Downloads Not Working?
1. Make sure files are in the **root** of your repository (not in a subfolder)
2. Check file names match exactly in HTML links (case-sensitive on GitHub)
3. Wait 2-3 minutes for GitHub Pages to rebuild after uploading

### Site Not Live?
1. Check **Settings → Pages** - should show "Your site is live at..."
2. Check **Actions** tab - any build errors?
3. Try clearing your browser cache and reloading

### Still Issues?
- Verify all files are in your main branch
- Make sure `.html` files are in root directory
- Document files (`.docx`, `.xlsx`) should also be in root

---

## 📧 Quick Links to Share

**Dragons:** Send them this link to view everything online:
```
https://Susiekabani.github.io/TheDen/dragon-complete-package.html
```

**Repository:** 
```
https://github.com/Susiekabani/TheDen
```

---

## 🎉 You're Ready!

Once deployed:
- ✅ Dragons can access the complete guide online
- ✅ Downloads work smoothly
- ✅ Everything is on GitHub (no external hosting needed)
- ✅ Printed packs ready for event night

**That's it! You're live!** 🚀
