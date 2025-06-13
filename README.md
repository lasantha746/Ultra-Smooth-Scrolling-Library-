# GSAP ScrollSmoother Project
A simple smooth scrolling website using GSAP ScrollSmoother library for effortless smooth animations.

## Features
- GSAP ScrollSmoother library integration
- Ultra smooth scrolling with minimal code
- Customizable smoothness levels
- Built-in scroll effects support
- Lightweight and fast performance

## Demo

[![Watch Demo](https://img.shields.io/badge/🎬-Play%20Demo-red?style=for-the-badge&logo=youtube)](Preview.mp4)

## Quick Start
1. Clone the repo:
   ```bash
   git clone https://github.com/lasantha746/Ultra-Smooth-Scrolling-Library-.git
   ```
2. Open `index.html` in your browser

## How to Use
- Scroll to see the smooth effect
- Automatic smooth scrolling on all devices
- No additional setup required

## Customization
Change smoothness in the JavaScript:
```javascript
ScrollSmoother.create({
    smooth: 3, // 1 = default, higher = smoother & slower
    effects: true // enable data-speed animations
});
```

## Add Scroll Effects
Add parallax effects to elements:
```html
<div data-speed="0.5">Slow parallax element</div>
<div data-lag="0.5">Lag behind element</div>
```

## Browser Support
Works on all modern browsers (Chrome, Firefox, Safari, Edge)

## Dependencies
- GSAP 3.13.0
- ScrollTrigger plugin
- ScrollSmoother plugin

## License
MIT License
