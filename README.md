# 🎰 El Cortez Hotel & Casino — Official Website

> **The Original Icon of Downtown Las Vegas** — A fully animated, cinematic single-page website built with pure HTML, CSS & JavaScript. No frameworks. No dependencies. Just stunning Vegas vibes.

---

![El Cortez Banner](https://img.shields.io/badge/Las%20Vegas-Since%201941-gold?style=for-the-badge&labelColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen?style=for-the-badge)

---

## ✨ Live Preview

> Open `el-cortez.html` directly in any modern browser — no build tools, no install, no server needed.

---

## 📁 Project Structure

```
el-cortez/
├── el-cortez.html          ← Entire website (single file)
├── README.md               ← This file
└── imgs/
    ├── screenshot_hero.png
    ├── screenshot_about.png
    ├── screenshot_casino.png
    ├── screenshot_rooms.png
    ├── screenshot_nightlife.png
    ├── screenshot_gallery.png
    ├── screenshot_testimonials.png
    ├── screenshot_location.png
    ├── screenshot_booking.png
    └── screenshot_footer.png
```

---

## 📸 Website Screenshots — Section by Section

### 🎬 1. Hero Section
> Cinematic full-screen background with real interior photography, animated neon title, floating gold particles, and two CTA buttons.

<p align="center">
  <img src="el-cortez/imgs/screenshot_hero.png" alt="Hero Section" width="700"/>
</p>

---

### 🏛️ 2. About / History Section
> Storytelling layout with the iconic **1941** year badge, floating "National Historic Landmark" label, stat counters, and the El Cortez founding story.

<p align="center">
  <img src="imgs/screenshot_about.png" alt="About Section" width="700"/>
</p>

---

### 🎰 3. Casino Experience Section
> Six animated feature cards (Slots, Table Games, Poker, Jackpot Club, High Limit Lounge, Live Entertainment) with hover glow effects and a live scrolling ticker tape.

<p align="center">
  <img src="imgs/screenshot_casino.png" alt="Casino Section" width="700"/>
</p>

---

### 🛏️ 4. Rooms & Suites Section
> Three room cards with real photo backgrounds — Classic Deluxe ($89/night), Vintage Junior Suite ($129/night), and Icon Penthouse Suite ($249/night) — with hover-reveal "Reserve Now" buttons.

<p align="center">
  <img src="imgs/screenshot_rooms.png" alt="Rooms Section" width="700"/>
</p>

---

### 🍸 5. Nightlife & Dining Section
> Five venues listed with animated left-border reveal on hover, alongside a glowing **"Open All Night"** neon sign art panel with hours display and live music schedule.

<p align="center">
  <img src="imgs/screenshot_nightlife.png" alt="Nightlife Section" width="700"/>
</p>

---

### 🖼️ 6. Photo Gallery Section
> A 5-tile mosaic grid using real restaurant photography with different color overlays (red, blue, gold, purple, pink). Section labels slide up on hover.

<p align="center">
  <img src="imgs/screenshot_gallery.png" alt="Gallery Section" width="700"/>
</p>

---

### ⭐ 7. Testimonials Section
> Auto-scrolling infinite carousel with 6 guest reviews. The carousel pauses when you hover over it. Each card has a glowing quote mark and star rating.

<p align="center">
  <img src="imgs/screenshot_testimonials.png" alt="Testimonials Section" width="700"/>
</p>

---

### 📍 8. Location Map Section
> A stylized Downtown Las Vegas map showing Fremont Street with an animated pulsing red pin marking the El Cortez location, alongside full contact details.

<p align="center">
  <img src="imgs/screenshot_location.png" alt="Location Section" width="700"/>
</p>

---

### 📅 9. Booking / Reservation Section
> A full reservation form with date pickers, room type selector, guest count, and name/email fields. Clicking the button triggers a live animated confirmation state.

<p align="center">
  <img src="imgs/screenshot_booking.png" alt="Booking Section" width="700"/>
</p>

---

### 🔻 10. Footer Section
> A four-column footer with the El Cortez brand logo, social media links, hotel/casino/dining navigation columns, address, and responsible gambling notice.

<p align="center">
  <img src="imgs/screenshot_footer.png" alt="Footer Section" width="700"/>
</p>

---

## 🚀 Features

### 🎨 Design & Visual
- **Vintage Las Vegas Neon + Modern Luxury** aesthetic
- Color palette: `#000000` Black · `#8B0000` Deep Red · `#C9A84C` Gold · `#FF2D78` Neon Pink · `#00D4FF` Neon Blue
- Real restaurant/interior photography embedded directly in the page
- Glassmorphism panels and glowing UI card elements
- Decorative neon corner brackets framing the hero

### 💫 Animations & Effects
- **Neon flicker** on the "Open All Night" sign (authentic CSS-only effect)
- **Floating gold/pink/blue particles** drifting upward across the hero
- **Scroll-reveal animations** — fade up, slide left, slide right per section
- **Animated ticker tape** across the casino section
- **Auto-scrolling testimonials** carousel (pauses on hover)
- **Shimmer sweep** on buttons on hover
- **Animated map pin** pulse in the location section
- **Rotating conic gradient** background in the booking section

### 🖱️ Interactivity
- **Custom gold glowing cursor** that morphs to neon pink on hover
- **Sticky navbar** — transparent → frosted glass on scroll
- **Active nav link** highlighting as you scroll
- **Room cards** with hidden "Reserve Now" buttons that slide in on hover
- **Booking form** with date validation and animated confirmation
- **Mobile hamburger menu** with full-screen overlay

### 📱 Responsive Design
- Fully mobile-responsive across all screen sizes
- Fluid typography using `clamp()` for perfect scaling
- Adaptive grid layouts (3-col → 1-col on mobile)

---

## 🛠️ Tech Stack

| Technology | Usage |
|-----------|-------|
| **HTML5** | Semantic page structure, 10 full sections |
| **CSS3** | Animations, keyframes, glassmorphism, grid, custom properties |
| **Vanilla JavaScript** | Scroll reveal, cursor, nav behavior, form logic |
| **Google Fonts** | `Cinzel Decorative`, `Cinzel`, `Cormorant Garamond`, `Playfair Display` |
| **IntersectionObserver API** | Scroll-triggered reveal animations |
| **Base64 Images** | Photos embedded inline — zero external requests |

---

## 🏗️ Getting Started

### Option 1 — Open directly
```bash
# Just double-click el-cortez.html or drag it into any browser
```

### Option 2 — Serve locally
```bash
python -m http.server 8080
# Open: http://localhost:8080/el-cortez.html
```

### Option 3 — VS Code Live Server
Right-click `el-cortez.html` → **Open with Live Server**

---

## 🌐 Deploy to GitHub Pages

1. **Fork or clone** this repository
2. Go to **Settings → Pages → Source → main branch → Save**
3. ⚠️ Rename `el-cortez.html` → `index.html` to load at root URL
4. Your site goes live at:
   ```
   https://your-username.github.io/el-cortez/
   ```

---

## 🎨 Design Tokens

```css
--black:      #050508   /* Deep background */
--red:        #8B0000   /* Historic red accents */
--gold:       #C9A84C   /* Primary brand color */
--neon-pink:  #FF2D78   /* Neon sign accents */
--neon-blue:  #00D4FF   /* Cool contrast neon */
--cream:      #F5EDD6   /* Body text */
```

---

## 🏨 About El Cortez Hotel & Casino

The **El Cortez Hotel & Casino** is the **longest continuously operating hotel and casino** in Las Vegas history, founded in **1941**. In **2013**, it became the **only operating casino listed on the National Register of Historic Places**. Family-owned and independent — the authentic soul of Downtown Las Vegas.

📍 **600 Fremont Street, Las Vegas, NV 89101** · 📞 **(702) 385-5200**

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

**✦ The Original Icon of Downtown Las Vegas ✦**

*Est. 1941 · Still Standing · Still Glowing*

</div>
