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

## 📸 Screenshots

| Section | Description |
|--------|-------------|
| 🎬 Hero | Cinematic full-screen background with neon animated typography |
| 🏛️ About | Storytelling section with 1941 legacy badge and floating stats |
| 🎰 Casino | Feature cards with hover glow effects and live ticker tape |
| 🛏️ Rooms | Three room cards with real photo backgrounds and hover reveal |
| 🍸 Nightlife | Animated neon sign art + dining & entertainment listings |
| 🖼️ Gallery | 5-tile mosaic photo grid with color-overlay hover effects |
| ⭐ Testimonials | Auto-scrolling guest review carousel |
| 📍 Location | Stylized Downtown Las Vegas map with animated pin |
| 📅 Booking | Reservation form with live availability confirmation animation |

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
- **Animated ticker tape** across the casino section (open 24/7 info)
- **Auto-scrolling testimonials** carousel (pauses on hover)
- **Parallax-ready** hero with layered depth
- **Shimmer sweep** on buttons on hover
- **Animated map pin** pulse in the location section
- **Rotating conic gradient** background in the booking section

### 🖱️ Interactivity
- **Custom gold glowing cursor** that morphs to neon pink on hover targets
- **Sticky navbar** that transitions from transparent → frosted glass on scroll
- **Active nav link** highlighting as you scroll through sections
- **Room cards** with hidden "Reserve Now" buttons that slide in on hover
- **Booking form** with live date validation and animated confirmation state
- **Gallery tiles** with color-overlay labels that slide up on hover
- **Mobile hamburger menu** with full-screen overlay navigation

### 📱 Responsive Design
- Fully mobile-responsive across all screen sizes
- Fluid typography using `clamp()` for perfect scaling
- Adaptive grid layouts (3-col → 1-col on mobile)
- Touch-friendly tap targets throughout

---

## 📁 Project Structure

```
el-cortez/
│
├── el-cortez.html          # The entire website — one self-contained file
└── README.md               # This file
```

> All images are base64-encoded directly inside the HTML file, so the project is truly self-contained — no external assets folder needed.

---

## 🛠️ Tech Stack

| Technology | Usage |
|-----------|-------|
| **HTML5** | Semantic page structure, 10 full sections |
| **CSS3** | Animations, keyframes, glassmorphism, grid, custom properties |
| **Vanilla JavaScript** | Scroll reveal, cursor, nav behavior, form logic |
| **Google Fonts** | `Cinzel Decorative`, `Cinzel`, `Cormorant Garamond`, `Playfair Display` |
| **CSS Keyframes** | 15+ custom animations (flicker, float, pulse, ticker, shimmer…) |
| **IntersectionObserver API** | Scroll-triggered reveal animations |
| **Base64 Images** | Photos embedded inline — zero external requests |

---

## 🏗️ Getting Started

### Option 1 — Open directly (simplest)
```bash
# Just double-click el-cortez.html in your file explorer
# OR drag it into any browser window
```

### Option 2 — Serve locally
```bash
# Using Python (built into most systems)
python -m http.server 8080

# Then open: http://localhost:8080/el-cortez.html
```

### Option 3 — VS Code Live Server
1. Install the **Live Server** extension in VS Code
2. Right-click `el-cortez.html` → **Open with Live Server**

---

## 🌐 Deploy to GitHub Pages

1. **Fork or clone** this repository
2. Go to your repo → **Settings** → **Pages**
3. Under *Source*, select `main` branch → `/ (root)`
4. Click **Save**
5. Your site will be live at:
   ```
   https://your-username.github.io/el-cortez/
   ```

> ⚠️ GitHub Pages serves `index.html` by default. If you want the site to load at the root URL, **rename** `el-cortez.html` → `index.html` before pushing.

---

## 📋 Page Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | **Hero** | Cinematic background, neon title, CTA buttons, floating particles |
| 2 | **About / History** | 1941 founding story, stats, historic badge, floating labels |
| 3 | **Casino Experience** | 6 feature cards + scrolling ticker, 24/7 casino highlights |
| 4 | **Rooms & Suites** | Classic Deluxe ($89), Junior Suite ($129), Penthouse ($249) |
| 5 | **Nightlife & Dining** | 5 venues listed + neon sign art + hours display |
| 6 | **Photo Gallery** | 5-panel mosaic grid with real interior photography |
| 7 | **Testimonials** | Infinite auto-scrolling carousel with 6 guest reviews |
| 8 | **Location Map** | Stylized Fremont Street map with animated pin |
| 9 | **Booking / Reservation** | Full form with date pickers, room & guest selectors |
| 10 | **Footer** | Social links, nav columns, contact info, legal notice |

---

## 🎨 Design Tokens

```css
/* Core Color Palette */
--black:      #050508   /* Deep background */
--red:        #8B0000   /* Historic red accents */
--red-bright: #CC0000   /* Button highlights */
--gold:       #C9A84C   /* Primary brand color */
--gold-light: #F0D080   /* Glow highlights */
--neon-pink:  #FF2D78   /* Neon sign accents */
--neon-blue:  #00D4FF   /* Cool contrast neon */
--cream:      #F5EDD6   /* Body text */

/* Typography */
--display:  'Cinzel Decorative'   /* Titles & logo */
--heading:  'Cinzel'              /* Section labels & nav */
--body:     'Cormorant Garamond'  /* Paragraphs */
--accent:   'Playfair Display'    /* Quotes & pull text */
```

---

## 🏨 About El Cortez Hotel & Casino

The **El Cortez Hotel & Casino** is one of the most iconic landmarks in Downtown Las Vegas. Founded in **1941**, it holds the distinction of being the **longest continuously operating hotel and casino** in Las Vegas history. In **2013**, it became the **only operating casino listed on the National Register of Historic Places**, preserving its legacy as a true American cultural landmark.

Unlike modern mega-resorts, El Cortez has remained **family-owned and independent** — free from corporate ownership, keeping the authentic spirit of classic Las Vegas alive for over 80 years.

📍 **600 Fremont Street, Las Vegas, NV 89101**
📞 **(702) 385-5200**
🌐 [elcortezhotelcasino.com](https://www.elcortezhotelcasino.com)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

```
MIT License — feel free to use, modify, and distribute.
Credit appreciated but not required.
```

---

## 🙌 Credits

- **Design & Development** — Built with love for vintage Vegas aesthetics
- **Photography** — Restaurant & interior photography embedded in site
- **Fonts** — Google Fonts (Cinzel Decorative, Cormorant Garamond, Playfair Display)
- **Inspiration** — The legendary El Cortez Hotel & Casino, Downtown Las Vegas

---

<div align="center">

**✦ The Original Icon of Downtown Las Vegas ✦**

*Est. 1941 · Still Standing · Still Glowing*

</div>
