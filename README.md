# Spark Mastery Arena — PWA

A gamified Staff Data Engineer interview prep tool. Works as a native-feeling app on iPhone, Android, and desktop.

## Quick Deploy to GitHub Pages (3 minutes)

### 1. Create a GitHub repo
Go to https://github.com/new
- Name: `spark-mastery` (or anything)
- Public (required for free GitHub Pages)
- Don't add README (we already have one)
- Click "Create repository"

### 2. Push this code

```bash
cd spark-mastery-pwa
git init
git add .
git commit -m "Spark Mastery Arena PWA"
git branch -M main
git remote add origin git@github.com:YOUR_USERNAME/spark-mastery.git
git push -u origin main
```

### 3. Enable GitHub Pages
- Go to your repo → **Settings** → **Pages**
- Source: **Deploy from a branch**
- Branch: **main** / **/ (root)**
- Click **Save**
- Wait ~30 seconds, your site is live at: `https://YOUR_USERNAME.github.io/spark-mastery/`

### 4. Install on iPhone
1. Open `https://YOUR_USERNAME.github.io/spark-mastery/` in **Safari**
2. Tap the **Share** button (square with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add**

Done. It now has its own icon on your home screen, opens fullscreen (no browser bar), and works offline.

## Features
- 120 questions across 5 domains × 3 tiers
- XP system, streak tracking, mastery badges
- localStorage persistence (progress survives restarts)
- Export/Import progress between devices
- Works offline after first load (service worker caching)
- Optimized for iPhone (safe areas, standalone mode)
