# aespainaunion Portfolio

Portfolio website for aespainaunion projects - showcasing aespa fan union activities in Indonesia.

## 📁 Folder Structure

Your GitHub repository should look like this:

```
your-repo-name/
├── index.html          (Grid layout - main page)
├── scattered.html      (Scattered layout - alternative)
└── images/
    ├── nama-MYne.gif
    ├── aespa-nabati.gif
    ├── aespa-handbanner.gif
    ├── annivcake.jpg
    ├── fankit-nabati.jpg
    ├── fankit-HPL.jpg
    ├── fanpro-flashlight.gif
    ├── aiu-twi.jpg
    ├── aiu-kanjuruhan.jpg
    ├── aiu-adopsi.jpg
    ├── karina-bday2021.gif
    └── aiu-cafeevent.gif
```

## 🚀 How to Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and log in
2. Click the **"+"** icon → **"New repository"**
3. Name it: `your-username.github.io` (replace with your actual GitHub username)
   - Example: `aespainaunion.github.io`
4. Make it **Public**
5. Click **"Create repository"**

### Step 2: Download Your Images from ImgBB

You need to download all 12 images from your ImgBB links:

1. Visit each ImgBB link in your browser
2. Right-click on the image → **"Save Image As..."**
3. Save with these exact filenames:
   - `nama-MYne.gif`
   - `aespa-nabati.gif`
   - `aespa-handbanner.gif`
   - `annivcake.jpg`
   - `fankit-nabati.jpg`
   - `fankit-HPL.jpg`
   - `fanpro-flashlight.gif`
   - `aiu-twi.jpg`
   - `aiu-kanjuruhan.jpg`
   - `aiu-adopsi.jpg`
   - `karina-bday2021.gif`
   - `aiu-cafeevent.gif`

### Step 3: Upload Files to GitHub

**Option A: Using GitHub Web Interface (Easiest)**

1. Go to your repository on GitHub
2. Click **"Add file"** → **"Upload files"**
3. Upload `index.html` (grid version)
4. Click **"Add file"** → **"Create new file"**
5. Type `images/.gitkeep` in the filename box (this creates the images folder)
6. Click **"Commit changes"**
7. Go into the `images` folder
8. Click **"Add file"** → **"Upload files"**
9. Upload all 12 images
10. Click **"Commit changes"**
11. (Optional) Upload `scattered.html` if you want both versions

**Option B: Using Git Command Line**

```bash
# Navigate to your folder
cd /path/to/your/folder

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: Add aespainaunion portfolio"

# Connect to GitHub
git remote add origin https://github.com/your-username/your-username.github.io.git

# Push
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. Go to your repository **Settings**
2. Scroll to **"Pages"** in the left sidebar
3. Under "Source", select **"Deploy from a branch"**
4. Under "Branch", select **"main"** and **"/ (root)"**
5. Click **"Save"**

### Step 5: View Your Live Site! 🎉

Your site will be live at: `https://your-username.github.io`

It may take 1-2 minutes to deploy.

## 🎨 Two Versions Available

### Grid Layout (index.html)
- Clean 3x4 grid
- Professional and organized
- Desktop: 3 columns
- Tablet: 2 columns
- Mobile: 1 column

### Scattered Layout (scattered.html)
- Artistic, random positioning
- Rotated cards for creative feel
- Desktop: Scattered with overlaps
- Mobile: Clean vertical stack

Access scattered version at: `https://your-username.github.io/scattered.html`

## 📝 Image Naming Reference

| Original ImgBB URL | Filename to Save As |
|--------------------|---------------------|
| i.ibb.co/qFVb3m12/nama-MYne.gif | `nama-MYne.gif` |
| i.ibb.co/vCFHC2p1/aespa-nabati.gif | `aespa-nabati.gif` |
| i.ibb.co/hxGRnwYv/aespa-handbanner.gif | `aespa-handbanner.gif` |
| i.ibb.co/Ng8KDcmZ/annivcake.jpg | `annivcake.jpg` |
| i.ibb.co/DfrXmxtH/fankit-nabati.jpg | `fankit-nabati.jpg` |
| i.ibb.co/zh77Ft4H/fankit-HPL.jpg | `fankit-HPL.jpg` |
| i.ibb.co/5grM7Jwp/fanpro-flashlight.gif | `fanpro-flashlight.gif` |
| i.ibb.co/d0z2rPz8/aiu-twi.jpg | `aiu-twi.jpg` |
| i.ibb.co/Xx4xx5m4/aiu-kanjuruhan.jpg | `aiu-kanjuruhan.jpg` |
| i.ibb.co/nsjycXVy/aiu-adopsi.jpg | `aiu-adopsi.jpg` |
| i.ibb.co/JRQ4C1R8/Karina-bday2021.gif | `karina-bday2021.gif` |
| i.ibb.co/VWX2Z6rk/aiu-cafeevent.gif | `aiu-cafeevent.gif` |

## 🔧 Troubleshooting

**Images not loading?**
- Check that filenames match exactly (case-sensitive!)
- Ensure images are in the `images/` folder
- Clear your browser cache
- Wait a few minutes for GitHub Pages to update

**Site not showing up?**
- Make sure GitHub Pages is enabled in Settings
- Check that the main file is named `index.html`
- Verify the repository is public

## 📧 Support

For issues or questions about aespainaunion projects, contact the team through official channels.

---

Made with ❤️ for MYne (aespa fans Indonesia)