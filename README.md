# Kuthodaw Inscription Tipitaka  
### *The World’s Largest Book — Interactive Web Viewer*

☸️ **Kuthodaw Inscription Tipitaka** is a fully client-side web application for exploring the **729 marble stelae inscriptions** of the Kuthodaw Pagoda in Mandalay, Myanmar — widely recognized as *the world’s largest book*.

This project combines **map-based navigation**, **high-resolution manuscript viewing**, and **modern reading aids** to provide an elegant, scholarly-friendly experience for studying the Tipitaka inscriptions in digital form.

---

## ✨ Features

### 🗺️ Map-Based Manuscript Navigation
- Built on **Leaflet.js** using a custom `CRS.Simple` coordinate system
- Each stela (slab) is treated as a navigable “page”
- Smooth pan & zoom with URL hash state support (deep linking)

### 📚 Complete Canonical Structure
- Covers all **729 slabs**, including:
  - Cover & historical inscriptions
  - **Vinaya Pitaka**
  - **Suttanta Pitaka**
  - **Abhidhamma Pitaka**
- Hierarchical tree navigation mirrors the traditional Tipitaka structure
- Quick jump by slab number (including special prefatory slabs)

### 🎨 Reading Modes & Visual Filters
- **Light** (original)
- **Sepia** (vintage manuscript tone)
- **Dark / Inverted** (night reading)
- CSS-based image filtering for performance and clarity

### 🧭 Reading Aids
- Page boundary overlays
- Half-page split guides
- Multi-density line rulers for palaeographic reading
- Toggleable overlays without reloading images

### 🔍 Deep Zoom Mode
- Powered by **OpenSeadragon**
- Pixel-level inspection of inscriptions
- Seamless toggle between map mode and deep zoom
- Optimized for high-resolution `.webp` images

### 🧠 Smart Performance Design
- Lazy loading of images
- Neighbor preloading for smooth navigation
- Client-side only (no backend required)
- Designed for large datasets with minimal memory overhead

### 📱 Responsive, Touch-Friendly UI
- Elegant modern UI inspired by manuscript aesthetics
- Mobile-friendly floating navigation dock
- Slide-in control panel with contextual tools
- Keyboard navigation support

---

## 🛠️ Technology Stack

- **HTML5 / CSS3 / Vanilla JavaScript**
- **Leaflet.js** – spatial navigation & overlays
- **Leaflet Layers Tree** – hierarchical Tipitaka structure
- **OpenSeadragon** – deep zoom image viewer
- **Google Fonts** (Noto Serif, Sarabun)
- **Material Symbols** for iconography

No frameworks. No build step. Just open and read.

---

## 📂 Project Structure (Simplified)

/
├── index.html
├── images/
│ └── clean/
│ ├── 000.webp
│ ├── 001.webp
│ └── ...
├── assets/
│ ├── leaflet.js
│ ├── leaflet.css
│ ├── L.Control.Layers.Tree.min.js
│ └── openseadragon.min.js
└── KIT729.pdf

yaml
Copy code

---

## 🎯 Design Philosophy

- **Respect the source**: preserve the physical logic of the inscriptions  
- **Zero abstraction barrier**: slabs behave like real objects, not “pages”  
- **Scholarly usability**: reading aids over visual gimmicks  
- **Longevity**: static, portable, and archive-friendly  

This project is intended not just as a viewer, but as a **digital preservation interface** for sacred textual heritage.

---

## 🚀 Usage

1. Open `index.html` in any modern browser  
2. Select a slab using:
   - Tree navigation
   - Page number input
   - Keyboard shortcuts
3. Toggle reading aids or visual modes as needed  
4. Switch to **Deep Zoom Mode** for detailed study  

No server, no installation, no dependencies.

---

## 📜 Attribution & Cultural Context

The inscriptions originate from **Kuthodaw Pagoda**, Mandalay, Myanmar  
Commissioned during the reign of **King Mindon Min (1857–1878)**  

This project is a **digital visualization tool** and does not claim ownership of the original texts or inscriptions.

---

## ⚖️ License

This project is intended for **educational, research, and cultural preservation purposes**.  
Please verify image source licensing before redistribution.

---

## 🙏 Acknowledgement

Dedicated to:
- The preservation of the Tipitaka
- Open cultural heritage
- Readers who value slow, careful reading

☸️ *Sabba-dānaṃ dhamma-dānaṃ jināti*  
> “The gift of Dhamma excels all gifts.”
