# 5K Run Tracker

A simple Progressive Web App to track your weekly 5K runs.

## Features

- **Weekly tracking**: 4 run slots per week
- **Progress comparison**: See if each run is faster/slower than your last
- **Weekly averages**: Compare week-over-week performance
- **Visual chart**: Track your improvement over time
- **Works offline**: Data saved locally on your device

## Install on iPhone

### Step 1: Upload to GitHub

1. Create a new repository on GitHub (e.g., `5k-tracker`)
2. Upload all these files to the repository:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`

### Step 2: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**
6. Wait a minute, then your site will be live at:
   `https://YOUR-USERNAME.github.io/5k-tracker/`

### Step 3: Add to iPhone Home Screen

1. Open **Safari** on your iPhone
2. Go to your GitHub Pages URL
3. Tap the **Share** button (square with arrow)
4. Scroll down and tap **Add to Home Screen**
5. Name it "5K Tracker" and tap **Add**

The app will now appear on your home screen and work like a native app!

## How to Use

1. **Tap a week** to expand it
2. **Enter your time** (minutes : seconds)
3. **Tap Log** to save the run
4. **Track your progress** in the stats at the top

Your data is stored locally in your browser - it persists between sessions but stays on your device.

## Notes

- Data is stored in your browser's localStorage
- The app works offline once loaded
- Weeks are pre-generated starting from December 16, 2024
