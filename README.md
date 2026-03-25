# 📸 PECO — Event Documentary Builder

> **P**laces · **E**vents · **C**elebrations · **O**ccasions

**PECO** is a free, browser-based tool for creating beautiful, self-contained event documentary cards — no account, no server, no installation required. Fill in the details, add your photos, and download a single `.html` file you can share with anyone, open on any device, and view completely offline.

🔗 **Live App:** https://peco-app-baggi.netlify.app

---

## ✨ What Is PECO?

PECO lets you document and share moments that matter — a family celebration, a trip abroad, a cultural festival, a graduation — as a polished, portable web card. Everything is generated entirely in your browser: your photos never leave your device.

The output is a **single self-contained `.html` file** with all images embedded. No links to external servers. No expiry. Works offline forever.

---

## 🆓 It's Completely Free

- No sign-up or login
- No subscription
- No ads
- No data sent to any server — everything runs in your browser
- Download and keep your files permanently

---

## 🗂️ Event Categories

Choose the category that best fits your occasion:

| Category | Use For |
|---|---|
| 📸 Photography | Photo walks, shoots, visual projects |
| 🎉 Celebration | Birthdays, Eid, parties, anniversaries |
| 🌍 Travel | Trips, road trips, city explorations |
| 🎪 Event | Conferences, gatherings, community events |
| 🕌 Cultural | Heritage, traditions, religious occasions |
| 🎓 Ceremony | Graduations, weddings, award ceremonies |
| 🌿 Nature | Outdoor adventures, parks, landscapes |
| 🏛️ Documentary | History, places, storytelling projects |

---

## 🛠️ Features

### 📋 Event Details
Fill in the core information about your event:
- **Title** and **Subtitle / Tagline**
- **Description / Story** — a free-text narrative about the occasion
- **Date** — displayed in the output card in your language's locale format
- **Location / Place** — city, country, or venue name
- **Photographer / Author** name or handle
- **Google Maps link** — optional, embeds a one-tap map button in the output

### 🖼️ Cover Photo
- Upload a single hero image from your camera or gallery
- Displayed as a full-width banner at the top of the card
- Compressed automatically for a good balance of quality and file size

### 🗂️ Photo Gallery
- Add up to **12 photos** from your camera or gallery (multi-select supported)
- Each photo shows a **✏️ caption bar** — tap it to open a popup and type a caption
- Captions appear below each photo in the output card
- Remove any photo by hovering (desktop) or tapping the × button (mobile)
- **Per-photo size warning**: photos over 500 KB show a red ⚠️ badge and appear in a warning list, suggesting you switch to a lower quality preset

### ✏️ Caption Popup
Tap the bar at the bottom of any gallery photo to open the **caption editor**:
- The full photo is shown at the top so you know which one you're captioning
- A large, easy-to-type input field — designed for mobile screens
- **Save** with the button or press Enter
- **Clear** to remove the caption
- Tap outside or press Escape to dismiss

### ⚙️ Output Quality & File Size
Choose a compression preset before or after adding photos. Changing preset automatically re-compresses all your images:

| Preset | Cover Width | Gallery Width | JPEG Quality | Best For |
|---|---|---|---|---|
| 🟢 Small | 600 px | 480 px | 50% | WhatsApp / Telegram sharing |
| 🟡 Balanced | 900 px | 700 px | 72% | Default — good quality + size |
| 🔴 High Quality | 1400 px | 1000 px | 88% | Archiving / desktop viewing |

**Live size meter** — shows estimated output file size in real time with a colour-coded bar:
- ✅ Under 1 MB — easy to share
- ⚠️ 1–3 MB — consider switching to Medium
- 🔴 Over 3 MB — switch to Small

### 💬 Share Message
Before sharing, compose the message that goes alongside your file. A default message is pre-filled — it includes the event title and a link to PECO so recipients can make their own. You can edit it freely. The message:
- Updates automatically when you change the event title (as long as you haven't manually edited it)
- Switches language with the EN/AR toggle
- Is copied to your clipboard automatically when you tap Share, so you can paste it into WhatsApp after sending the file

### 🔗 Share
Tap **Share** to send the `.html` file directly from your browser's native share sheet (WhatsApp, Telegram, email, etc.). Works on Android and iOS. On desktop, the file is downloaded instead and the message is copied to your clipboard.

### 💾 Download
Download the final self-contained `.html` file. The filename is generated automatically in the format:

```
<category>-<ddmmyy>.html
```

Examples: `phot-230326.html`, `cele-010125.html`, `trav-150724.html`

The category prefix is always in English, even when the app is in Arabic.

---

## 🌐 Bilingual — English & Arabic

PECO fully supports both **English (LTR)** and **Arabic (RTL)**:
- All UI labels, placeholders, and hints switch instantly with the language toggle
- The output card respects the selected language — RTL layout, Arabic locale dates
- Category names, captions, share messages, and the map button all adapt
- Toggle at any time during editing — your content is preserved

---

## 🔒 Privacy

PECO is entirely **client-side**. This means:
- Your photos are processed using the browser's Canvas API and never uploaded
- All image compression happens locally on your device
- The generated `.html` file is created in memory and downloaded directly
- No analytics, no tracking, no cookies

---

## 📱 How to Use — Step by Step

1. **Open the app** at https://peco-app-baggi.netlify.app
2. **Choose a category** by tapping one of the 8 chips at the top
3. **Fill in Event Details** — title, description, date, location, photographer name
4. **Add a Cover Photo** — tap the banner area or use Camera / Gallery buttons
5. **Add Gallery Photos** — tap ＋ or use the Camera / Gallery buttons (up to 12)
6. **Add captions** — tap the ✏️ bar under each photo, type in the popup, tap Save
7. **Choose quality preset** — 🟢 Small for sharing, 🟡 Balanced for most cases
8. **Watch the size meter** — stay under 1 MB for easy sharing
9. **Edit the share message** if you want a custom note
10. **Tap Share** to send via WhatsApp / Telegram, or **Download** to save the file
11. **Send the `.html` file** to anyone — they open it in any browser, no internet needed

---

## 📤 Output File

The downloaded file is a fully self-contained HTML document:
- All photos embedded as Base64 (no external image links)
- Works offline on any device with a browser
- Renders correctly on mobile and desktop
- Includes: cover image, title, subtitle, description, date, location, photo grid with captions, Google Maps button, photographer credit, and a PECO footer link

---

## 🧰 Technical Notes

- **No build step** — single `.html` file, no dependencies to install
- **No server required** — can be hosted on any static host (Netlify, GitHub Pages, etc.)
- **Canvas API** used for image compression and Base64 encoding
- **Web Share API** used for native sharing on Android/iOS
- **Clipboard API** used to copy the share message automatically
- All compression presets and photo warnings run entirely in the browser

---

## 📬 Feedback & Support

Made with ❤️ by Baggi.
Share your thoughts or report issues by visiting the app and using the share/contact options.

🔗 https://peco-app-baggi.netlify.app
