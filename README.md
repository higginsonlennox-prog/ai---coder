# 💻 AI Coder

A personal AI coding assistant you can host for free on GitHub Pages. Ask it to write, fix, or explain code in any language — and upload screenshots or mockups to turn them into working code.

![AI Coder preview](https://img.shields.io/badge/Powered%20by-Claude%20Sonnet-7c6af7?style=flat-square)
![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-222?style=flat-square&logo=github)

---

## 🚀 Deploy in 3 steps

### 1. Fork or push this repo to GitHub

If you downloaded the zip, create a new repo on GitHub and push the files:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ai-coder.git
git push -u origin main
```

### 2. Enable GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Set branch to `main`, folder to `/ (root)`
5. Click **Save**

Your app will be live at:
```
https://YOUR_USERNAME.github.io/ai-coder/
```

### 3. Get your API key

1. Go to [console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys)
2. Sign up (free) and create an API key
3. Paste it into the sidebar of your app and click **Save**

Your key is stored in your browser only — it never leaves your device.

---

## ✨ Features

- **Any language** — Python, JavaScript, TypeScript, Rust, Go, C/C++, Java, SQL, Bash, and more
- **Image uploads** — screenshot an error, draw a mockup, or show a diagram and get working code back
- **Full chat history** — conversations are saved in your browser across sessions
- **Multiple sessions** — create separate chats for different projects
- **Syntax highlighting** — all code blocks are coloured with one-click copy
- **Unlimited questions** — no usage caps beyond your Anthropic account limits

---

## 🔑 About the API key

- You need an [Anthropic API key](https://console.anthropic.com/settings/keys) (free to sign up)
- Anthropic gives free credits when you sign up — enough for hundreds of coding sessions
- Your key is saved in `localStorage` in your browser and is **never sent anywhere except directly to Anthropic**
- Paid usage is cheap — roughly $0.003 per message

---

## 🛠 Running locally

No build tools needed. Just open `index.html` in any browser:

```bash
# Option 1: just double-click index.html

# Option 2: use a local server
npx serve .
# or
python -m http.server 8080
```

---

## 📁 Project structure

```
ai-coder/
├── index.html        # The entire app (single file)
├── README.md         # This file
└── .github/
    └── workflows/
        └── deploy.yml  # Auto-deploy to GitHub Pages
```

---

## License

MIT — do whatever you want with it.
