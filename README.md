# 📚 README.md

### *YouTube Filter Blocker — because sometimes you just want peace.*

## 🚀 What Even Is This

This Chrome extension is digital noise‑cancelling for YouTube. It removes the clutter and recommended content you never asked for, keeping you focused on the video you actually intended to watch.

## ✨ Features (What it hides)

* **Sidebars & Recommendations**: No more distraction loops.
* **Guide Sections**: Simplifies the main navigation menu.
* **YouTube Music Clutter**: Keeps the music interface clean.
* **Pure CSS**: No tracking, no data harvesting, just style overrides.

## 🖼️ Visual Proof (The "Results")

### 1. The Clean Slate (Home Feed)

When you first open YouTube, the entire "Recommended" grid is gone, leaving you with a distraction-free search bar.

### 2. Focused Search

Search results are displayed clearly without the usual "People also watched" or "Related to your search" shelves cluttering the view.

### 3. The "Video Only" Experience

While watching a video, the entire sidebar of related videos and the comment section below are hidden.

## 🛠️ Installation

1. Download or clone this repository.
2. Open Chrome and navigate to `chrome://extensions`.
3. Turn on **Developer Mode** in the top right.
4. Click **Load unpacked** and select this folder.

## 🧠 Technical Overview

This extension uses a `manifest.json` to inject `filters.css` at `document_start`. By using `!important` declarations in the CSS, we ensure our "hidden" state overrides the default YouTube styles even as the page loads.

## 🤝 Contributing

Feel free to open a PR if you find a new UI element that needs to be "yeeted" out of existence.

## ⚠️ Disclaimer

This extension may cause increased productivity and a sense of inner peace. Use responsibly.

## ⚖️ License

Licensed under the **GNU General Public License v3.0**.