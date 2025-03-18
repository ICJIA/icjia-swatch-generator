# Color Swatch Generator

A web application for generating color palettes based on color theory principles.

![Color Swatch Generator Screenshot](https://via.placeholder.com/800x450.png?text=Color+Swatch+Generator)

## Features

- Generate harmonious color palettes from a base color
- Multiple color harmony patterns:
  - Monochromatic
  - Complementary
  - Analogous
  - Triadic
  - Split Complementary
  - Tetradic (Rectangle)
  - Shades & Tints
  - Golden Ratio Harmony
- Copy color hex codes with a single click
- Responsive design for all device sizes
- Modern UI with subtle animations
- Dynamic theming based on selected color

## Usage

1. Set your base color using the color picker or by entering a hex code
2. Click "Generate Swatches" to create color palettes
3. Click on any color swatch to copy its hex code to clipboard
4. Use the generated color schemes in your design projects

## Color Theory Principles & Patterns

This application implements several established color theory principles used by designers to create harmonious color combinations. Each pattern is based on the relationships between colors as positioned on the traditional color wheel.

### Monochromatic

Variations of the same hue with different lightness values. This creates a cohesive, unified look.

- Example: Various shades of blue from light sky blue (#87CEEB) to navy (#000080)
- Use case: Creating depth without introducing new colors

### Complementary

Base color paired with its opposite on the color wheel (180° apart). This creates high contrast and vibrant combinations.

- Example: Blue (#0000FF) and Yellow (#FFFF00)
- Use case: Call-to-action buttons, emphasis elements

### Analogous

Colors adjacent to each other on the color wheel (within 30° on either side). This creates harmonious combinations with low contrast.

- Example: Green (#00FF00), Yellow-Green (#80FF00), and Yellow (#FFFF00)
- Use case: Background elements, natural-feeling designs

### Triadic

Three colors equally spaced around the color wheel (120° apart). This provides visual contrast while maintaining color harmony.

- Example: Red (#FF0000), Yellow (#FFFF00), and Blue (#0000FF)
- Use case: Balanced, vibrant designs with multiple accent colors

### Split Complementary

Base color plus two colors adjacent to its complement (150° and 210° from base). This provides high contrast with less tension than complementary schemes.

- Example: Blue (#0000FF) with Yellow-Orange (#FFCC00) and Red-Orange (#FF6600)
- Use case: When you need contrast but pure complementary feels too harsh

### Tetradic (Rectangle)

Four colors arranged in two complementary pairs (90° apart). This offers rich color possibilities with balanced contrast.

- Example: Blue (#0000FF), Orange (#FF7F00), Green (#00FF00), and Red (#FF0000)
- Use case: Complex designs requiring multiple accent colors

### Shades & Tints

Variations of lightness while maintaining the same hue and saturation. This creates a range of options within a single color.

- Example: A pure hue mixed with varying amounts of white (tints) or black (shades)
- Use case: UI component states, data visualization

### Golden Ratio Harmony

Colors spaced around the color wheel according to the golden ratio (φ ≈ 0.618). This creates mathematically balanced, aesthetically pleasing combinations.

- Example: Starting with blue, adding colors at intervals of 0.618 × 360° around the wheel
- Use case: Sophisticated, balanced multi-color designs

## Sources & Further Reading

The color theory principles implemented in this application are based on established design concepts from:

1. Itten, Johannes. "The Art of Color: The Subjective Experience and Objective Rationale of Color."
2. Wong, Wucius. "Principles of Color Design: Designing with Electronic Color."
3. Adobe Color: [https://color.adobe.com/create/color-wheel](https://color.adobe.com/create/color-wheel)
4. Paletton: [https://paletton.com](https://paletton.com)
5. Color theory on Wikipedia: [https://en.wikipedia.org/wiki/Color_theory](https://en.wikipedia.org/wiki/Color_theory)
6. Albers, Josef. "Interaction of Color"
7. Munsell, Albert H. "A Color Notation"
8. Kuler (now Adobe Color): Originally introduced concepts of harmony rules
9. Birren, Faber. "Principles of Color: A Review of Past Traditions and Modern Theories of Color Harmony"

## Installation

This is a standalone HTML/CSS/JavaScript application with no dependencies. Simply open the `index.html` file in a web browser.

### Development

For local development:

1. Clone the repository

```bash
git clone https://github.com/yourusername/color-swatch-generator.git
cd color-swatch-generator
```

2. Open `index.html` in your browser or use a local development server:

```bash
# Using Python
python -m http.server

# Using Node.js (with http-server package)
npx http-server
```

## Demo

https://<the_site+here>

## License

MIT License. See `LICENSE` file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
