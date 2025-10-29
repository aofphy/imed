# How to Host This Presentation on GitHub Pages

## Quick Steps:

### 1. Create a GitHub Repository
- Go to https://github.com and sign in
- Click "New Repository"
- Name it (e.g., `dr-presentation`)
- Make it Public
- Click "Create repository"

### 2. Upload Your Files
You can use either method:

#### Method A: Using GitHub Web Interface
1. Click "uploading an existing file"
2. Drag and drop the entire `FF69` folder contents
3. Commit the changes

#### Method B: Using Git Command Line
```bash
cd /Users/aof_mac/Documents/FF69
git init
git add .
git commit -m "Initial commit: DR presentation"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

### 3. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings"
3. Click "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"

### 4. Access Your Presentation
After 1-2 minutes, your presentation will be live at:
```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/presentation.html
```

## Folder Structure Required:
```
your-repo/
├── presentation.html
├── PPTiMEDEV_2025-01 Present/
│   ├── Slide1.svg
│   ├── head.svg
│   └── bottom.svg
├── images/
│   ├── dr_fundus.jpg
│   ├── ai_growth_chart.svg
│   ├── chatgpt.svg
│   ├── claude.svg
│   ├── gemini.svg
│   └── perplexity.svg
└── Gemini_Generated_Image_7ald7f7ald7f7ald (1).png
```

## Tips:
- All image paths are now relative, so it will work on any server
- The presentation works offline too (just needs internet for fonts)
- You can share the GitHub Pages URL with anyone
- No server setup needed!

## Navigation:
- **Arrow Right** or **Space**: Next slide
- **Arrow Left**: Previous slide
- **Click arrows**: Navigate slides
