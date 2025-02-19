# Future Dev Portfolio 🌌

A modern, interactive portfolio landing page with mesmerizing visual effects and smooth animations. Built with Tailwind CSS and vanilla CSS/JS.


## Features ✨

- **Stellar Background**: Dark gradient backdrop with floating cyan shapes
- **Dynamic Effects**:
  - Mouse-triggered water ripple animation
  - Floating circular elements with smooth transitions
  - Neon glow text and button effects
- **Responsive Design**: Mobile-friendly layout using Tailwind CSS
- **Smooth Interactions**: Hover animations and click effects
- **Modern Aesthetics**: Cyberpunk-inspired color scheme (cyan/magenta)

## Installation 🛠️

1. Clone repository:
   ```bash
   git clone https://github.com/yourusername/future-dev-portfolio.git
   ```
2. Open in browser:
   ```bash
   cd future-dev-portfolio && open index.html
   ```

## Technologies Used 💻

- **HTML5**: Semantic structure
- **Tailwind CSS**: Utility-first styling
- **CSS3**: Custom animations and keyframes
- **JavaScript**: Mouse interaction handling

## Customization 🎨

### Change Colors
Modify the gradient colors in `body` background:
```css
background: radial-gradient(circle, rgba(18,18,18,1) 0%, rgba(9,9,9,1) 100%);
```

### Add Floating Shapes
Insert new shape divs with custom positions:
```html
<div class="shape" style="top: 30%; left: 70%; animation-duration: 4s;"></div>
```

### Adjust Ripple Effect
Modify ripple animation properties:
```css
@keyframes ripple {
  0% { transform: scale(0); opacity: 1; }
  100% { transform: scale(4); opacity: 0; } /* Increase scale value */
}
```

## License 📄
MIT License - Feel free to modify and use for your own projects!

---

**Craft the future with code** 🚀  
[Live Demo](#) | [Contact Me](#) | [View Projects](#)
