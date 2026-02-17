# Inkwell — Real-time Notes App

A beautiful dark note-taking app hosted on GitHub Pages that syncs across all your devices using GitHub as the backend.

## 🚀 Setup in 5 minutes

### 1. Fork / Create your repo
Create a new GitHub repo (e.g. `my-notes`). Upload both `index.html` and `notes.json` to it.

### 2. Enable GitHub Pages
- Go to your repo → **Settings** → **Pages**
- Source: **Deploy from a branch**
- Branch: `main` / `root`
- Save — your app will be live at `https://YOUR_USERNAME.github.io/REPO_NAME`

### 3. Create a Personal Access Token
- Go to [github.com/settings/tokens](https://github.com/settings/tokens)
- Click **Generate new token (classic)**
- Give it a name like `inkwell-notes`
- Check the **`repo`** scope (or just `public_repo` if your repo is public)
- Generate and **copy the token** — you only see it once!

### 4. Configure the app
- Open your GitHub Pages URL
- Click **⚙ Config** in the bottom-left
- Enter your GitHub username, repo name, branch (`main`), and the token
- Click **Save & Sync**

That's it! Now open the same URL on your phone and it'll sync automatically.

## ✨ Features
- 📓 Multiple notebooks with custom icons
- ✍️ Markdown editor with live preview
- 🔄 Real-time sync via GitHub API (auto-saves every 2.5s after changes)
- 📱 Fully responsive — works on mobile
- 🌙 Dark, classy UI with smooth transitions
- 🔍 Search across all notes
- 📊 Word & character count

## 🔒 Security
Your GitHub token is stored in `localStorage` on each device — it never leaves your browser except to authenticate with the GitHub API. For best security, use a fine-grained token scoped to only this repository.

## 🛠 Tech Stack
- Pure HTML + CSS + JavaScript (no build step!)
- GitHub Contents API for sync
- marked.js for Markdown rendering
- Hosted on GitHub Pages (free)
