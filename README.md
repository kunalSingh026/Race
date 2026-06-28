# 🏁 RaceCar — Interactive Sports Car Showcase

A premium, visually stunning single-page web experience showcasing high-performance sports cars. Built using modern frontend technologies, custom HSL color palettes, and immersive animations.

---

## ✨ Features

- **🏎️ Dynamic Swiper.js Showcase**: A fluid, full-screen slider transition with custom fade effects that switches between different sports car profiles (Orange, Green, and Blue editions).
- **⚡ GSAP-Powered Micro-Animations**: Smooth entry animations on page load, including sliding split panels, floating car elements, and staggered title entries.
- **🎨 Modern Aesthetics**: Uses elegant typography (Montserrat), custom HSL CSS custom properties for theme-swapping, dark-mode elements, and a frosted glass-like scrolling header blur.
- **📱 Fully Responsive**: Optimized with mobile-first styling to ensure a seamless experience on smartphones, tablets, and high-resolution desktops.
- **💬 Social Media Integration**: Quick links to active profiles wrapped in polished interactive UI components.

---

## 🛠️ Tech Stack

- **Core**: HTML5, Vanilla JavaScript (ES6)
- **Styling**: Vanilla CSS3 (CSS Variables, Flexbox, Grid)
- **Animations**: [GSAP (GreenSock Animation Platform)](https://gsap.com/)
- **Slider Component**: [Swiper.js](https://swiperjs.com/)
- **Icons**: [Remix Icon](https://remixicon.com/)

---

## 📂 Project Structure

```text
Race/
├── assest/                    # Project Assets
│   ├── css/
│   │   ├── gsap-public/       # Local GSAP distribution library
│   │   ├── style.css          # Main stylesheet containing layout and styling
│   │   ├── swiper-bundle.min.css
│   │   └── swiper-bundle.min.js
│   ├── img/
│   │   └── favicon.png        # Shortcut icon
│   ├── car-1.png              # Sports Car (Orange)
│   ├── car-2.png              # Sports Car (Green)
│   └── car-3.png              # Sports Car (Blue)
├── index.html                 # Main markup and DOM structure
├── main.js                    # Navigation toggles, Swiper initialization, and GSAP scroll/timeline animations
└── README.md                  # Project documentation (this file)
```

---

## 🚀 Getting Started

To run the project locally, choose one of the following methods:

### Method 1: Using a Local Web Server (Recommended)
Because this project utilizes local script assets and resources, running it through a local development server ensures proper performance and routing:
1. **VS Code Live Server**: If using VS Code, install the **Live Server** extension, open the project folder, and click **"Go Live"** in the bottom-right corner.
2. **Npx HTTP-Server**: Alternatively, run the following command in your terminal within the project directory:
   ```bash
   npx http-server .
   ```
   Then open `http://localhost:8080` in your web browser.

### Method 2: Direct Execution
Simply double-click the [index.html](file:///d:/web-Deveopment/Race/index.html) file to open it directly in any modern web browser.

---

## 🔧 Customization & Configuration

- **Color Schemes**: All major colors are mapped using CSS Variables in the `:root` pseudo-class inside [style.css](file:///d:/web-Deveopment/Race/assest/css/style.css). You can easily update `--orange-color`, `--green-color`, or `--blue-color` to match different brand requirements.
- **Animation Timings**: Edit the GSAP animations at the bottom of [main.js](file:///d:/web-Deveopment/Race/main.js) to fine-tune the transition durations and delay timings.
- **Transition Effects**: Swiper's configuration is fully adjustable in [main.js](file:///d:/web-Deveopment/Race/main.js) (e.g. changing `speed`, transition `effect`, or modifying paginations).
