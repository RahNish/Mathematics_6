# 🧮 Class 6 & 7 Maths Hub

Interactive maths lessons and games for Class 6 and Class 7 students.  
All games are built as single HTML files — no installation needed!

---

## 🌐 Live Site

Open `index.html` in your browser or visit the GitHub Pages link to play all games.

---

## 🎮 Current Games

| File | Topic | Class |
|------|-------|-------|
| `angles.html` | Understanding Angles — lesson | Class 7 |
| `angle-duel.html` | Angle Duel — guessing game | Class 7 |
| `angle-architect.html` | Angle Architect — building puzzle | Class 7 |
| `number-play.html` | Number Play — neighbours quiz | Class 6 |
| `supercell.html` | Supercell Explorer — grid quiz | Class 6 |

---

## ➕ How to Add a New Game (Step by Step)

### Step 1 — Build your game
- Make your game as a **single `.html` file**
- Example filename: `fractions.html`
- Add the **Home button** inside it (see Step 9 below)

---

### Step 2 — Upload the file to GitHub
1. Go to your GitHub repo page
2. Click **"Add file"** → **"Upload files"**
3. Drag and drop your `.html` file
4. Scroll down and click **"Commit changes"**

---

### Step 3 — Open index.html for editing
1. Click `index.html` in the repo file list
2. Click the **pencil icon ✏️** at the top right to edit

---

### Step 4 — Find the right chapter section
- For **Class 7** games → look for this comment:
  ```
  <!-- ══ CLASS 7 ══ -->
  ```
- For **Class 6** games → look for this comment:
  ```
  <!-- ══ CLASS 6 ══ -->
  ```

---

### Step 5 — Copy this card template

```html
<a href="YOUR-FILE-NAME.html" class="card">
  <div class="card-thumb" style="background:linear-gradient(135deg,#f0f9ff,#dbeafe);">
    <div style="font-size:3rem;">🎮</div>
  </div>
  <div class="card-body">
    <div class="card-tag" style="color:#2563eb;">Chapter Name · Game</div>
    <div class="card-name">Your Game Title</div>
    <div class="card-desc">Short description of what the game teaches in 1 to 2 lines.</div>
    <div class="card-cta" style="color:#2563eb;">Play now →</div>
  </div>
</a>
```

---

### Step 6 — Paste it in the right place
Find this line in `index.html`:
```html
<div class="card-add" id="add-slot">
```
Paste your copied card **just above** that line.

---

### Step 7 — Edit these 4 things in the card

| What to find | What to change it to |
|---|---|
| `YOUR-FILE-NAME.html` | your actual filename e.g. `fractions.html` |
| `🎮` | an emoji that suits your game |
| `Your Game Title` | the real name of your game |
| `Short description...` | what the game teaches (1–2 lines) |

---

### Step 8 — Save your changes
1. Scroll to the bottom of the editor
2. Click the green **"Commit changes"** button
3. Your new card will appear on the hub immediately ✅

---

### Step 9 — Add a Home button to your new game file

Paste this line right after the `<body>` tag in your new game's HTML file:

```html
<a href="index.html" style="position:fixed;top:14px;left:14px;z-index:9999;display:flex;align-items:center;gap:6px;background:#fff;border:1.5px solid #e5e7eb;border-radius:50px;padding:7px 16px 7px 12px;font-family:sans-serif;font-size:.82rem;font-weight:700;color:#6366f1;text-decoration:none;box-shadow:0 2px 10px rgba(0,0,0,.1);">🏠 Home</a>
```

This gives players a button to return to the main hub from any game.

---

## 🎨 Card Colour Options

Change the `background` in `card-thumb` to match your game's theme:

| Colour | Code |
|--------|------|
| Blue | `linear-gradient(135deg,#eff6ff,#dbeafe)` |
| Purple | `linear-gradient(135deg,#faf5ff,#ede9fe)` |
| Green | `linear-gradient(135deg,#f0fdf4,#dcfce7)` |
| Orange | `linear-gradient(135deg,#fff7ed,#fef3c7)` |
| Pink | `linear-gradient(135deg,#fdf2f8,#fce7f3)` |
| Teal | `linear-gradient(135deg,#f0fdfa,#ccfbf1)` |

Also change `color:#2563eb` in `card-tag` and `card-cta` to match:

| Colour | Code |
|--------|------|
| Blue | `#2563eb` |
| Purple | `#7c3aed` |
| Green | `#16a34a` |
| Orange | `#d97706` |
| Pink | `#db2777` |
| Teal | `#0d9488` |

---

## 📁 File Structure

```
repo/
│
├── index.html          ← Main hub (edit this to add new cards)
├── README.md           ← This guide
│
├── angles.html
├── angle-duel.html
├── angle-architect.html
├── number-play.html
├── supercell.html
│
└── your-new-game.html  ← Add new files here
```

---

## 🔒 Is my repo safe?

Yes! Even though the repo is **public**:
- ✅ Anyone can view and play the games
- ✅ Anyone can read the code
- ❌ Nobody can edit or add files except **you**

Only your GitHub account can make changes. Your hub is fully under your control.

---

## 💡 Quick Checklist for Every New Game

- [ ] Game is saved as a single `.html` file
- [ ] Home button added after `<body>` tag
- [ ] File uploaded to GitHub repo
- [ ] Card added to `index.html` in the right chapter section
- [ ] `href`, title, description, and emoji updated in the card
- [ ] Changes committed on GitHub

---

*Made for Class 6 & 7 · Tap a card to begin!*
