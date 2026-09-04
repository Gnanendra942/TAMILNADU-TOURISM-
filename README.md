# 🏛️ Tamil Nadu Tourism — Web Application

> **Discover the Soul of Tamil Nadu** — An immersive, interactive travel discovery platform showcasing ancient living temples, mist-clad Nilgiri hill stations, golden coastal towns, wildlife reserves, and rich cultural heritage.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_Website-2ea44f?style=for-the-badge&logo=githubpages&logoColor=white)](https://gnanendra942.github.io/TAMILNADU-TOURISM-/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen?style=for-the-badge)](https://en.wikipedia.org/wiki/Vanilla_software)
[![Responsive](https://img.shields.io/badge/Design-Responsive-blueviolet?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)

🔗 **Live Website**: [https://gnanendra942.github.io/TAMILNADU-TOURISM-/](https://gnanendra942.github.io/TAMILNADU-TOURISM-/)

---

## 📖 Overview

**Tamil Nadu Tourism** is a modern conceptual redesign and high-performance travel web application. Designed with an editorial aesthetic, smooth micro-interactions, and rich multimedia storytelling, the platform invites travellers to experience the cultural heart of Southern India.

Built entirely using **Vanilla HTML5, CSS3, and JavaScript**, the application delivers app-like interactivity with **zero external dependencies or build steps**.

---

## ✨ Key Features

### 🔍 1. Smart Predictive Search
- **Real-Time Autocomplete**: Instant search filter by destination name, district, or category.
- **Matched Query Highlighting**: Search terms are dynamically highlighted using custom `<mark>` tags.
- **Keyboard Navigation**: Full support for `Arrow Up`, `Arrow Down`, `Enter`, and `Escape` keys.
- **Smart Out-of-State Detection**: Detects queries for locations outside Tamil Nadu (e.g., Goa, Munnar, Kerala) and intelligently recommends equivalent Tamil Nadu alternatives.
- **Popular Search Suggestions**: Displays curated recommendations when the search bar is activated.

### 🏞️ 2. Curated Destinations Carousel & Detail Modal
- **Horizontal Scroll Snap**: Fluid card carousel featuring iconic destinations.
- **Interactive Card Elements**: Dynamic gradient border beam, idle image floating motion, and hover-triggered descriptions.
- **Comprehensive Detail View**: Fullscreen slide-up view with:
  - High-resolution hero imagery
  - Regional overview & historical background
  - Best visiting seasons
  - Tagged highlights & nearby destinations
  - Curated photo gallery
  - Quick action to launch the trip planner

### 🧭 3. Experience Categorization
Browse Tamil Nadu through six curated travel styles:
1. **Spiritual & Heritage** — Ancient Chola, Pallava, and Pandyan architectural marvels.
2. **Hills & Valleys** — The misty peaks of Ooty, Kodaikanal, Yercaud, and Valparai.
3. **Beaches & Coast** — From Marina Beach to the confluence at Kanyakumari.
4. **Wildlife & Nature** — Tiger reserves, mangrove forests, and sacred waterfalls.
5. **Food & Culture** — Classical Bharatanatyam, Carnatic music, and authentic Tamil cuisine.
6. **Adventure** — Trekking trails, mountain railways, camping, and watersports.

### 🗺️ 4. Interactive Regional SVG Map
- **Custom Vector Map**: Stylized vector map of Tamil Nadu with interactive district nodes.
- **Interactive District Tooltips**: Hover over districts (Chennai, Madurai, Coimbatore, Nilgiris, etc.) to view notable highlights.
- **Synchronized Region Tabs**: Filter cities across the 5 distinct cultural and geographic zones:
  - **North**: Chennai, Mahabalipuram, Kanchipuram, Vellore, Tiruvallur
  - **South**: Madurai, Rameswaram, Kanyakumari, Tirunelveli, Tenkasi, Thoothukudi
  - **Central**: Trichy, Karur, Perambalur, Pudukkottai
  - **West**: Coimbatore, Ooty, Erode, Salem, Valparai, Yercaud
  - **Delta**: Thanjavur, Kumbakonam, Nagapattinam, Mayiladuthurai

### 📅 5. Algorithmic Custom Trip Planner
- **Customized Itinerary Generation**: Users choose:
  - **Duration**: 3, 5, 7, or 10 Days
  - **Travel Pace**: Relaxed, Balanced, or Packed
  - **Budget Tier**: Comfort, Premium, or Luxury
  - **Interests**: Multi-select tags (Temples, Nature, Food, Beaches, Adventure, Photography, Culture)
- **Dynamic Matching Engine**: Generates a tailored, day-by-day travel plan matching destination scores to user preferences.

### 🎒 6. Curated Tour Packages
Handcrafted travel circuits with durations, destination counts, transparent pricing, and descriptions:
- *Temple Trails of the South* (6 Days)
- *Nilgiri Escape* (4 Days)
- *Coastal Honeymoon* (5 Days)
- *Western Ghats Wild* (5 Days)
- *Family Heritage Circuit* (7 Days)
- *Weekend in the Hills* (3 Days)

### 📸 7. Dynamic Attractions Gallery
- Alternating masonry layout with lazy-loaded high-resolution photography.
- Quick filter chips for temples, beaches, waterfalls, hill stations, wildlife, and forts.

### ⚡ 8. Dynamic Ambient Theme Engine & Micro-Interactions
- **Cycling Ambient Palette**: Automatically transitions accent colors across authentic regional hues (deep temple maroon, warm gold, terracotta).
- **Interactive Canvas Constellation**: Interactive particle network following cursor movement on desktop devices.
- **Smooth Page Veil Transitions**: Sweeping transition veil between section anchors.
- **Hero Ken Burns Slideshow**: Background imagery transitions smoothly with slow zoom effects.
- **Floating Quick Navigation (FAB)**: One-click floating dock providing fast access to Search, Destinations, Planner, and Contact.
- **Reduced Motion Support**: Full compliance with `prefers-reduced-motion` for accessibility.

---

## 🎨 Design System & Aesthetics

| Component | Design Choice | Description |
| :--- | :--- | :--- |
| **Typography** | `Fraunces` & `Manrope` | Editorial serif for elegant headings paired with a clean geometric sans-serif for body copy. |
| **Color Scheme** | Deep Maroon (`#8a1538`), Terracotta (`#c17a3d`), Warm Gold (`#d4a24a`) | Rooted in South Indian temple architecture, silk textiles, and natural landscapes. |
| **Backdrop** | Glassmorphism (`backdrop-filter: blur(18px)`) | Translucent pill-shaped navigation bars and floating controls. |
| **Motion** | Cubic-bezier easing (`cubic-bezier(.22, 1, .36, 1)`) | Natural, spring-like reveals, card tilts, and smooth scrolling. |

---

## 🗂️ Project Structure

```text
TAMILNADU-TOURISM-/
├── .github/
│   └── workflows/
│       └── deploy.yml                 # Automated GitHub Pages deployment workflow
├── .nojekyll                          # Disables Jekyll processing for raw static file hosting
├── index.html                         # Root entry point for GitHub Pages / web servers
├── tamil-nadu-tourism (3) (1).html    # Complete standalone single-page web application
├── README.md                          # Project documentation and guide
└── .git/                              # Git version control repository
```

> **Note**: The web application is bundled as a self-contained single-page file containing structure, styling, embedded assets, and client logic. `index.html` serves as the root document for web servers and GitHub Pages.

---

## 🚀 Getting Started

No build tools, compilation, or package installations are required!

### Option 1: Direct File Launch
Simply double-click `tamil-nadu-tourism (3) (1).html` or run in your terminal:

**macOS**:
```bash
open "tamil-nadu-tourism (3) (1).html"
```

**Linux**:
```bash
xdg-open "tamil-nadu-tourism (3) (1).html"
```

**Windows**:
```cmd
start "tamil-nadu-tourism (3) (1).html"
```

---

### Option 2: Run with Local HTTP Server

Running via a local HTTP server ensures full compatibility with browser security policies:

**Using Python 3**:
```bash
python3 -m http.server 8000
```
Then visit [`http://localhost:8000/tamil-nadu-tourism%20(3)%20(1).html`](http://localhost:8000/tamil-nadu-tourism%20(3)%20(1).html).

**Using Node (`npx serve`)**:
```bash
npx -y serve .
```

---

### Option 3: Automatic GitHub Pages Deployment

The repository includes a GitHub Actions workflow (`.github/workflows/deploy.yml`) configured to deploy to GitHub Pages automatically:

1. Push changes to the `main` branch.
2. In your repository on GitHub, navigate to **Settings** > **Pages**.
3. Under **Build and deployment** > **Source**, select **GitHub Actions**.
4. The site will automatically build and publish to `https://<your-username>.github.io/<repo-name>/`.

---

## 📱 Browser Compatibility

The application utilizes modern web standards supported across all major contemporary browsers:
- **Google Chrome** / Chromium (v88+)
- **Apple Safari** (v14+)
- **Mozilla Firefox** (v85+)
- **Microsoft Edge** (v88+)
- **Mobile Browsers** (iOS Safari, Chrome for Android)

---

## 🏛️ Destinations Featured

- **Ooty (Udhagamandalam)** — Doddabetta Peak, Tea Plantations, Nilgiri Mountain Railway
- **Kodaikanal** — Kodai Lake, Pillar Rocks, Coaker's Walk
- **Madurai** — Meenakshi Amman Temple, Thirumalai Nayakkar Palace
- **Chennai** — Marina Beach, Kapaleeshwarar Temple, Fort St. George
- **Kanyakumari** — Vivekananda Rock Memorial, Thiruvalluvar Statue, Triveni Sangam
- **Rameswaram** — Ramanathaswamy Temple Corridor, Pamban Bridge, Dhanushkodi
- **Thanjavur** — Brihadeeswarar Great Living Chola Temple, Saraswathi Mahal Library
- **Mahabalipuram (Mamallapuram)** — Shore Temple, Pancha Rathas, Arjuna's Penance
- **Yercaud** — Shevaroy Hills, Emerald Lake, Killiyur Falls
- **Valparai** — Anamalai Tiger Reserve, Sholayar Dam, Tea Plateaus
- **Coimbatore** — Marudamalai Temple, Perur Pateeswarar Temple
- **Courtallam (Kutralam)** — Main Falls, Five Falls, Spa of South India

---

## 📜 Credits & Acknowledgements

- **Photography**: High-resolution licensed imagery sourced via [Wikimedia Commons](https://commons.wikimedia.org/) under Creative Commons licenses.
- **Typography**: [Google Fonts](https://fonts.google.com/) (`Fraunces` and `Manrope`).
- **Inspiration**: Tamil Nadu Tourism Development Corporation (TTDC) & the living heritage of Tamil Nadu.

---

<div align="center">
  <sub>Built with ❤️ celebrating the rich culture, history, and natural beauty of Tamil Nadu, India.</sub>
</div>