# 🐱 Meow Meow Generator

A whimsical web-based cat avatar creator that lets you design and download custom pixel-art style cats with various colors, patterns, and expressions.

## Features

### Two Creation Modes

**Build Mode** - Customize your cat step-by-step:
- Choose from 8 body colors (white, orange, black, gray, brown, cream, ginger, calico)
- Add patterns (stripes, spots, tuxedo, patches) - available only for white cats
- Select from 6 different expressions (happy, sad, angry, surprised, sleepy, playful)

**Chaos Mode** - Discover random cat combinations:
- Use the chaos slider to explore pre-set cat combinations
- Each position reveals a unique cat with a special name
- Perfect for finding unexpected and delightful cat designs

### Additional Features

- **Cat Names**: Each unique combination has its own generated cat name
- **Download**: Export your creation as an 800x800px PNG image
- **Responsive Canvas**: Cats render with crisp pixel-art styling
- **Layer System**: Sophisticated rendering with body color, shadows, patterns, expressions, and outlines

## Usage

Simply open `meow-meow-generator.html` in a modern web browser. No server or additional setup required!

### Creating a Cat

1. **Choose a Mode**: Click "Build Mode" or "Chaos Mode" at the top
2. **Customize Your Cat**:
   - In Build Mode: Select colors, patterns, and expressions
   - In Chaos Mode: Slide the chaos meter to discover combinations
3. **Download**: Click the "Download meow meow" button to save your creation

### Pattern Rules

Patterns are only available when the white body color is selected. This design choice ensures patterns render properly with the multiply blend mode technique used in the app.

## Technical Details

- Pure HTML, CSS, and JavaScript - no dependencies
- Canvas-based rendering with blend modes
- Base64-encoded image data for portability
- Jersey 15 font from Google Fonts for retro aesthetic
- Responsive side panel design

## File Structure

The app is entirely self-contained in a single HTML file, including:
- All styling (CSS)
- Application logic (JavaScript)
- Image assets (Base64-encoded)

## Browser Compatibility

Works best in modern browsers that support:
- HTML5 Canvas
- CSS Grid
- ES6 JavaScript
- Canvas blend modes

## License

Feel free to use and modify for personal or commercial projects.

---

*Made with 😸 for cat lovers everywhere*
