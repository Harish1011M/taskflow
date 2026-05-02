# 📲 TaskFlow — Install on Android

## How to Install on Your Android Phone

### Method 1: Using GitHub Pages (FREE & Easy — Recommended)

1. **Create a free GitHub account** at github.com
2. **Create a new repository** named `taskflow`
3. **Upload all 3 files**: `index.html`, `manifest.json`, `sw.js`
4. Go to **Settings → Pages → Source: main branch**
5. Your app URL will be: `https://yourusername.github.io/taskflow`
6. **Open this URL in Chrome on your Android phone**
7. Tap the **"Install"** banner that appears, OR tap ⋮ menu → **"Add to Home Screen"**
8. Done! 🎉 The app icon appears on your home screen just like a real app!

---

### Method 2: Using Netlify (Also FREE)

1. Go to **netlify.com** and sign up
2. Drag and drop the **taskflow folder** onto Netlify
3. You'll get a URL like `https://taskflow-abc123.netlify.app`
4. Open on Android Chrome → Install from the banner

---

### Method 3: Local Network (No internet needed)

1. Install **VS Code** + **Live Server extension** on your PC
2. Open the taskflow folder, right-click `index.html` → **Open with Live Server**
3. Find your PC's local IP (e.g., `192.168.1.5`)
4. On your phone (same WiFi): open `http://192.168.1.5:5500`
5. Install from Chrome

---

## Features

- ✅ **Task management** with categories, priorities & emoji
- ⏰ **In-app reminders** with motivating messages
- 🔔 **Push notifications** (allow when prompted)
- 📊 **Stats dashboard** to track your progress
- 🔥 **Streak counter** to stay motivated
- 💪 **Rotating motivational quotes**
- 🎉 **Confetti celebrations** when tasks are done
- 📱 **Offline support** — works without internet
- 🌙 **Beautiful dark theme** — easy on the eyes

## Files Included

| File | Purpose |
|------|---------|
| `index.html` | The complete app |
| `manifest.json` | Makes it installable as an app |
| `sw.js` | Service Worker for offline + notifications |
