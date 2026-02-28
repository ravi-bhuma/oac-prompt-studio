# OAC AI Agent — Prompt Engineering Resources

Public-facing guides for writing effective Oracle Analytics Cloud AI Agent Supplementary Instructions.

## 📂 Structure

```
├── index.html                              # Landing page (hub)
├── guides/
│   ├── quick-start.html                    # 10-min Quick Start Guide
│   └── prompt-engineering-studio.html      # Full 40-technique reference
└── README.md
```

## 🚀 Setup — GitHub Pages (5 minutes)

### Step 1: Create the Repository on GitHub

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `oac-prompt-studio`
3. Set to **Public**
4. Do NOT initialize with README (we already have files)
5. Click **Create repository**

### Step 2: Push This Folder

```bash
cd oac-prompt-studio
git add .
git commit -m "Initial release: Quick Start + Prompt Engineering Studio"
git remote add origin https://github.com/YOUR_USERNAME/oac-prompt-studio.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repo on GitHub → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `/ (root)`
4. Click **Save**
5. Wait ~60 seconds

### Step 4: Share Your Links

Your site will be live at:

| Page | URL |
|------|-----|
| **Landing Hub** | `https://YOUR_USERNAME.github.io/oac-prompt-studio/` |
| **Quick Start** | `https://YOUR_USERNAME.github.io/oac-prompt-studio/guides/quick-start.html` |
| **Full Studio** | `https://YOUR_USERNAME.github.io/oac-prompt-studio/guides/prompt-engineering-studio.html` |

## 🔄 Updating Content

```bash
# Edit any HTML file, then:
git add .
git commit -m "Updated quick start guide"
git push
# GitHub Pages auto-deploys in ~30 seconds
```

## 📝 Notes

- All files are self-contained HTML — no build step, no dependencies
- Works offline if downloaded, but designed for browser access via URL
- No authentication required for viewers
- Free hosting via GitHub Pages (no bandwidth limits for reasonable traffic)
