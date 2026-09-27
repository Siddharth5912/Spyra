# SPYRA Studios — Official Portfolio Website

Welcome to the official portfolio website for **SPYRA** (Spira), featuring both creative branches:
- **Spyra Games**: Indie game production showcase (PC, WebGL, Consoles).
- **Spyra Labs**: Game development assets, tools, physics engines, and shaders (featuring **Simple Flags**).

---

## 📁 Project & Folder Structure

This project is built using vanilla **HTML5**, **CSS3**, and **JavaScript** with zero external runtime build dependencies. It is 100% portable, extremely fast, and ready to host immediately on any static web host.

```text
SPYRA Portfolio website/
│
├── index.html                   # Main landing page & portfolio showcase
├── favicon.png                  # Browser tab favicon (Spyra mark)
├── README.md                    # Documentation & hosting guide
│
├── css/
│   ├── style.css                # Obsidian Emerald design system, layouts & tokens
│   └── animations.css           # Micro-interactions, glows, keyframes & pulses
│
├── js/
│   └── main.js                  # Dynamic branch switching, live flag simulator,
│                                # playable arcade mini-game, modals & sound synthesis
│
└── assets/
    ├── icons/
    │   └── favicon.png          # High-resolution favicon icon
    │
    └── images/
        ├── studio-bg.jpg        # Studio HQ ambient background
        │
        ├── branding/            # Official company logos and emblems
        │   ├── spyra-mark.png            # Geometric 'S' mark (original)
        │   ├── spyra-mark-trans.png      # Geometric 'S' mark (transparent background)
        │   ├── spyra-logo-white.png      # White logo on black background
        │   ├── spyra-logo-white-trans.png# White logo (transparent background)
        │   ├── spyra-logo-black.png      # Black logo on white background
        │   └── spyra-logo-black-trans.png# Black logo (transparent background)
        │
        ├── games/               # Spyra Games cover artwork & banners
        │   ├── neon-drift.jpg        # Neon Drift: Overdrive
        │   ├── chrono-weaver.jpg     # Chrono Weaver: Puzzle Island
        │   └── vanguard-protocol.jpg # Vanguard Protocol (Mech Roguelite)
        │
        └── labs/                # Spyra Labs tool banners & showcases
            ├── simple-flags.png      # Simple Flags flagship banner (from your upload!)
            ├── gridmaster-3d.jpg     # GridMaster 3D Procedural Tool
            └── stylized-shaders.jpg  # Stylized Water & Toon Shaders
```

---

## 🎨 Theme & Brand Styling
The visual aesthetic was derived directly from your company's identity:
- **Primary Brand Colors**:
  - **Spyra Emerald**: `#10b981`, `#22c55e`, `#00f59b` (inspired by the green checkerboard isometric grid).
  - **Game Amber / Gold**: `#fcd561`, `#fbbf24` (inspired by the Simple Flags button).
  - **Obsidian Dark Canvas**: `#070a0d`, `#0e1418` (high-contrast AAA studio aesthetic).
  - **Flag Accents**: Neon Magenta `#f43f5e`, Electric Blue `#1e88e5`, Pirate Black `#212121`.
- **Typography**: Google Fonts `Outfit` (matching the geometric modern Spyra wordmark), `Space Grotesk` (tech stats & badges), and `Inter` (body copy).

---

## 🕹️ Interactive Features Included
1. **Dual Branch Switcher**: Instant switching between `All Creations`, `🎮 Spyra Games`, and `⚡ Spyra Labs`.
2. **Simple Flags Live Sandbox**: A real-time HTML5 Canvas cloth & wind physics simulator where visitors can test wind turbulence, swap between 5 fabric colors, and select 4 emblem glyphs (Sword, Crown, Skull, Spyra Mark).
3. **Playable Web Racer Mini-Game**: In-browser playable arcade trial (`Neon Drift: Speed Trial`) with keyboard controls (`A/D` or Arrow Keys), dodging hazard drones and collecting energy cores.
4. **Interactive Deep Dive Modals**: Rich popups displaying technical specs, game engines, platform compatibility, and feature lists.
5. **Futuristic Sound FX Engine**: Built-in Web Audio API synthesizer that produces subtle sci-fi clicks and chimes (with a toggle in the navbar).
6. **Animated Stats Counter**: Counts up dynamically on scroll (+3 Games, +12 Tools, 58K+ Downloads, 99.4% Rating).
7. **Contact & Collaboration Form**: Complete form with validation and instant status feedback.

---

## 🚀 How to Host This Website (Free Options)

Because this website uses standard HTML, CSS, and JavaScript, you can host it for free in under 2 minutes:

### Option 1: Netlify (Easiest — 30 Seconds)
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop the entire `SPYRA Portfolio website` folder onto the webpage.
3. Your website is instantly live with a free SSL certificate! You can connect your custom domain (e.g. `spyragames.com`).

### Option 2: GitHub Pages
1. Create a new repository on [GitHub](https://github.com) named `spyra-portfolio`.
2. Push or upload all files from this folder directly into the repository root.
3. In GitHub, go to **Settings > Pages**.
4. Under **Branch**, select `main` (or `master`) and folder `/ (root)`, then click **Save**.
5. Your website will be live at `https://<your-username>.github.io/spyra-portfolio/`.

### Option 3: Vercel
1. Install Vercel CLI (`npm i -g vercel`) or go to [vercel.com](https://vercel.com).
2. Import the folder or GitHub repository and click **Deploy**.

---

## 💻 How to Run Locally

You can simply double-click `index.html` in your file explorer to open it in any web browser!

Or, run a local preview server:
- **VS Code**: Install the "Live Server" extension, right-click `index.html`, and select **Open with Live Server**.
- **Python** (if installed): `python -m http.server 8000`
- **Node.js** (if installed): `npx serve .`
