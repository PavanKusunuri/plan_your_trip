# 🇮🇳 Explore India — Travel Landing Page

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)

A fully responsive travel landing page for exploring iconic destinations across **Himachal Pradesh, India**. Built with modern HTML5, CSS3, and Sass — showcasing advanced front-end development techniques including CSS animations, 3D card flips, custom navigation, and a mobile-first responsive grid system.

🔗 **Live Demo:** [pavankusunuri.github.io/plan_your_trip](https://pavankusunuri.github.io/plan_your_trip/)

---

## ✨ Features

- **Animated Hero Section** — Full-viewport header with a clip-path polygon and smooth CSS keyframe animations
- **Responsive Grid System** — Custom-built fluid grid with breakpoints for mobile, tablet, and desktop
- **3D Flip Tour Cards** — 8 Himachal Pradesh destination cards with smooth `rotateY` 3D flip on hover, each with a unique image and gradient
- **Sticky Hamburger Navigation** — Pure CSS hamburger menu with a radial-gradient animated background overlay
- **Floating Composition Photos** — Overlapping image layout with hover zoom and outline effects
- **Skewed Features Section** — CSS `skewY` transform with counter-skew children for a dynamic layout
- **Video Background Section** — HTML5 `<video>` background in the stories section
- **Animated Booking Form** — Floating label inputs, custom radio buttons, and focus state animations
- **CSS Popup Modal** — Pure CSS popup (no JavaScript) triggered by anchor hash links
- **India-Inspired Colour Theme** — Custom Sass palette built around saffron, golden amber, ocean teal, festival rose, and royal indigo

---

## 🗺️ Tour Destinations Covered

| Destination | Highlights |
|---|---|
| **Shimla** | Queen of Hills, heritage colonial architecture |
| **Manali** | Snow peaks, adventure sports, Rohtang Pass |
| **Dharamshala** | McLeod Ganj, Tibetan culture, Dalai Lama temple |
| **Spiti Valley** | Cold desert, ancient monasteries, stargazing |
| **Kasol** | Backpacker trails, Parvati River, pine forests |
| **Dalhousie** | Scottish-era colonial charm, Dainkund Peak |
| **Khajjiar** | India's "Mini Switzerland", meadow landscapes |
| **Kullu** | Valley of Gods, river rafting, Beas River |

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Semantic markup, accessibility-focused structure |
| **Sass (SCSS)** | 7-1 architecture pattern — abstracts, base, components, layout, pages |
| **CSS3** | Animations, transforms, clip-paths, 3D perspective, Flexbox |
| **Node.js / npm** | Sass compilation toolchain |
| **GitHub Pages** | Static site hosting and deployment |

---

## 📁 Project Structure

```
plan_your_trip/
├── index.html              # Main HTML file
├── css/
│   ├── style.css           # Compiled CSS (output)
│   └── icon-font.css       # Custom icon font styles
├── sass/
│   ├── main.scss           # Sass entry point
│   ├── abstracts/          # Variables, mixins, functions
│   ├── base/               # Reset, typography, animations, utilities
│   ├── components/         # Cards, buttons, forms, popup, navigation
│   ├── layout/             # Header, footer, grid, navigation
│   └── pages/              # Home page-specific styles
├── img/                    # All images and video assets
└── package.json            # npm scripts for Sass compilation
```

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher)

### Installation & Run

```bash
# Clone the repository
git clone https://github.com/PavanKusunuri/plan_your_trip.git

# Navigate into the project
cd plan_your_trip

# Install dependencies
npm install

# Compile Sass once
npm run start

# Compile Sass and watch for changes
npm run compile:sass
```

Then open `index.html` in your browser, or use the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) VS Code extension.

---

## 🎨 Colour Palette

| Role | Colour | Hex | Inspiration |
|---|---|---|---|
| Primary | 🟠 Saffron Orange | `#E8511A` | India's national colour |
| Secondary | 🟡 Golden Amber | `#FFD166` | Temples & spices |
| Tertiary | 🩵 Ocean Teal | `#0CB8B6` | Kerala backwaters |
| Quaternary | 🩷 Festival Rose | `#E91E8C` | Holi & Rajasthan |
| Quinary | 💙 Royal Indigo | `#4A90D9` | Kashmir lakes |

---

## 📸 Sass Architecture (7-1 Pattern)

The Sass codebase follows the **7-1 architecture pattern**, keeping styles modular and maintainable:

- `abstracts/` — Variables (colour palette, grid settings), mixins (responsive breakpoints), and functions
- `base/` — Global reset, typography scale, keyframe animations, and utility classes
- `components/` — Isolated, reusable UI components (cards, buttons, forms, popup, stories, feature boxes)
- `layout/` — Page-level structural styles (header, footer, grid columns, navigation)
- `pages/` — Page-specific overrides for the home page sections

---

## 🌐 Deployment

The site is deployed via **GitHub Pages** directly from the `main` branch.

Live URL: [https://pavankusunuri.github.io/plan_your_trip/](https://pavankusunuri.github.io/plan_your_trip/)

---

## 👨‍💻 Author

**Pavan Kusunuri**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PavanKusunuri)

---

## 📄 License

This project is licensed under the **ISC License**.
