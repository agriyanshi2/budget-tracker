# Sunny & Riya — Budget Tracker

A real-time shared budget tracker. One HTML file, no server needed.

## How to host (free, 5 minutes)

### Option A: Netlify (easiest, recommended)
1. Go to **netlify.com** → sign up free
2. Drag and drop the `index.html` file onto the Netlify dashboard
3. You'll get a URL like `https://random-name.netlify.app` — share it with your husband
4. Both of you bookmark that URL

### Option B: GitHub Pages
1. Create a GitHub account → New repository → name it `budget-tracker`
2. Upload `index.html`
3. Go to Settings → Pages → Source: main branch → Save
4. Your URL: `https://yourusername.github.io/budget-tracker`

### Option C: Just use the file locally
- Open `index.html` in any browser on your computer
- For real-time sharing with husband, you both need the same hosted URL

---

## First-time Firebase setup (one person does this once)

1. Go to **console.firebase.google.com**
2. Click **Add project** → give it any name → Continue
3. In left sidebar: **Build → Realtime Database → Create database**
4. Choose **Start in test mode** → Next → Done
5. Go to **Project Overview (gear icon) → Project settings**
6. Scroll to **Your apps** → click the Web icon `</>` → Register app → copy the `firebaseConfig` object
7. Paste it into the app when prompted

**Share the same Firebase config** with your husband — he pastes it once and you're both connected.

---

## Features
- Real-time sync — changes appear instantly on both devices
- Month-by-month tracking (navigate with ‹ ›)
- Sunny / Riya split view with individual amounts
- Budget vs actual with % over/under badges
- Full activity log — who changed what, when
- Add & delete expense / investment rows
- Works on mobile and desktop
