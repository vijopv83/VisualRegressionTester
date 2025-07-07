# Visual Regression Tester

A playground for visual regression testing—simulate UI states, edge cases, and accessibility scenarios for login flows. Ideal for automated/manual testing, QA, design review, and evaluating visual regression tools.

---

## 🚀 Features

- **SPA Login Experience:**  
  Seamless login/logout flow with instant panel updates—no reloads.

- **About Us Overlay:**  
  Modern, responsive card with a feature table and a visually rich comparison of popular visual regression tools (Applitools, Percy, BackstopJS, etc.). Scroll—content is curated and always readable.

- **Visual Regression Parameters Panel:**  
  All parameters are grouped in a right-side accordion panel. Toggle UI states (typography, layout, effects, form, image, Canvas/WebGL, etc.) with instant UI and URL sync for reproducibility.

- **Canvas/WebGL Demo:**  
  Replace the right-side image with a live 3D WebGL cube for advanced rendering tests.

- **Multi-language Support:**  
  Header language switcher (globe icon/modal) with instant UI translation.  
  **Supported languages:**  
  English, Arabic, Bengali, Chinese, Japanese, Korean, Russian, Greek, Hebrew, Thai, Dutch, French, German, Hindi, Italian, Malayalam, Marathi, Spanish, Telugu

- **Dark Mode:**  
  Header sun/moon toggle and URL param support. All About Us and tool cards are fully readable and themed for both light and dark mode.

- **Accessibility & Responsiveness:**  
  RTL support, keyboard/screen reader friendly, fully responsive.

- **System Info Panel:**  
  Device, browser, network, and display info for context-aware testing.

- **Realistic UI Overlays:**  
  Cookie banner, popups, toasts, and social login simulations.

- **Image & Form Edge Cases:**  
  Blurred, grayscale, high-contrast, hidden, broken, or distorted images; robust form validation; custom subheadings.

- **Alternate Button Style:**  
  Visually distinct button style toggle that does not affect button position or layout.

- **Visual Regression Tools Comparison:**  
  Dedicated section in About Us comparing Applitools Eyes, Percy, BackstopJS, Katalon Studio, Kobiton, Chromatic, PhantomCSS, Galen Framework, AyeSpy, SikuliX, and more.

---

## 🌐 Online Demo

No setup, view live on GitHub Pages:

[https://vijopv83.github.io/VisualRegressionTester/](https://vijopv83.github.io/VisualRegressionTester/)

---

## 🎛️ Visual Regression Parameters

Open the panel (cog icon in header) to toggle features for robust visual testing. All options update the UI and URL in sync.

**Accordion Sections & Options:**

- **Typography** (Font, Font Size, Bold, Font Colour, Fallback Font, Subheading Style)
- **Layout** (Offset Vertical, Offset Horizontal, Border, No Shadow, Skeleton Loader, Grid, Ruler)
- **Effects** (Invert Colors, Animate Elements, Banner, Toast, Popup, Cookie Banner, Floating Box)
- **Form & UX** (Hide Form, Alternate Button Style, Hide Social Button, Countdown, Disable Login, Input Error, Hide Footer)
- **Image** (Blur, Grayscale, Overlay, High Contrast, Hide Image, Image Slider, Broken Image, Random Pixel, Distorted Image, SVG Icons, Canvas/WebGL)

> **Tip:** Share/bookmark any visual state via the URL.

---

## 💡 Usage

- Toggle parameters for instant UI changes and regression scenarios.
- Switch languages and test RTL/Unicode.
- Simulate login, signup, forgot password, and social logins.
- Open About Us overlay for a feature table and visual regression tools comparison.

---

## 🗂️ File Structure

```
├── index.html         # Main SPA playground
├── public/
│   └── output.css     # Styles (Tailwind/custom)
├── favicon.ico
└── README.md
```

---

## 🤝 Contributing

Open issues or pull requests for features, bug fixes, or new visual scenarios.

---

## 📬 Questions & Support

Connect on [LinkedIn](https://www.linkedin.com/in/vijopv83/).

---

## 🔑 License

MIT © [Vijo Varghese](https://github.com/vijopv83)
