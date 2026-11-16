# 💖 Interactive Date Proposal Web App

A pixel-perfect recreation of the viral *"POV: you gave the IT guy a chance... and he sends this wtf 😭"* date proposal quiz app (`date-proposal-funny.replit.app` / *AskMeOut*).

---

## ✨ Features

- 🫣 **Step 1: The Ask Out** with the runaway **"no"** button that dodges the cursor / touches and displays funny sarcastic remarks.
- 💅 **Glowing "YES obviously 💅"** button with neon pink pulses and Web Audio sound effects.
- 🎉 **Step 2: Ideal Date Activity Picker** (Fancy dinner, Movie night, Picnic outside, Fun & games, Coffee & vibes, Something artsy).
- 📅 **Step 3: Scheduling / Timing** (This weekend, Next week, Pretty soon, Anytime for you).
- 🥳 **Step 4: Celebration Itinerary & Full-screen Confetti Shower**.
- 📲 **Instant Confirmation**: One-click button to send the date plan directly back via WhatsApp, Native Share, or Clipboard copy!
- 🎨 **Aesthetics**: Midnight space glassmorphism, animated top rainbow border, floating emojis, and responsive mobile-first UI.
- ⚡ **Zero-dependency, single-file**: Everything runs directly in `index.html` without needing `node_modules` or build tools.

---

## 🚀 How to Run & Share

### 1. Instant Local Preview
Simply double click `index.html` in your file explorer to open it directly in any browser (Chrome, Edge, Safari, Brave), or run:
```bash
python -m http.server 8089
```
and visit `http://localhost:8089`.

### 2. Personalize with URL Parameters
You can customize the recipient's name and your phone number directly in the link:
* `http://localhost:8089/?name=Sarah`
* `http://localhost:8089/?name=Alex&phone=1234567890` (Automatically pre-fills a WhatsApp message directly to your phone when they complete it!)

---

## 🌐 Instant Free 1-Day Deployment Options

Since this is for a one-day occasion, you can make it accessible on their phone in 30 seconds:

1. **Vercel**: Run `npx vercel` inside this folder, or drop it into [vercel.com/new](https://vercel.com/new).
2. **Netlify Drop**: Drag and drop the `date-proposal` folder onto [app.netlify.com/drop](https://app.netlify.com/drop) to get a live URL in 10 seconds.
3. **GitHub Pages**: Push this repo and enable Pages in repository settings.
