# BounceUp Website — Netlify Deployment

## Folder Structure

```
bounceup-netlify/
├── index.html          ← Homepage (with hero video)
├── shop.html           ← Shop page
├── formula.html        ← Formula page
├── benefits.html       ← Benefits page
├── our-story.html      ← Our Story page
├── netlify.toml        ← Netlify config (auto-routing, caching, headers)
├── images/
│   └── product_image.jpg     ← PUT YOUR PRODUCT PHOTO HERE
└── videos/
    └── background_video.mp4  ← PUT YOUR HERO VIDEO HERE
```

## How to Deploy on Netlify

### Option A — Drag & Drop (Easiest)
1. Add your files to the `images/` and `videos/` folders
2. Go to https://app.netlify.com
3. Click **"Add new site"** → **"Deploy manually"**
4. Drag and drop this entire `bounceup-netlify` folder onto the Netlify drop zone
5. Your site will be live in seconds!

### Option B — GitHub (Recommended for updates)
1. Create a free GitHub account at https://github.com
2. Create a new repository and upload this folder
3. Go to https://app.netlify.com → **"Add new site"** → **"Import from Git"**
4. Connect your GitHub repo
5. Every time you push changes, Netlify auto-deploys

## Before You Deploy
Make sure you have placed:
- `images/product_image.jpg` — your BounceUp shampoo product photo
- `videos/background_video.mp4` — your homepage background video

The site works without them (fallback colors are used), but adding them makes it look complete.

## Your Live URL
After deploying, Netlify gives you a free URL like:
`https://bounceup-abc123.netlify.app`

You can also connect a custom domain (e.g. www.bounceup.pk) in Netlify settings.
