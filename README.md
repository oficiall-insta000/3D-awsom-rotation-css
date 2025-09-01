# 3D Image Gallery with Interactive Menu
**PERVIEW** : [**CLICK HERE**](https://oficiall-insta000.github.io/3D-awsom-rotation-css/)
A visually stunning 3D image gallery that displays images in a rotating 3D carousel with an interactive navigation menu.

## Features

- **3D Image Carousel**: Images arranged in a circular 3D layout that rotates continuously
- **Interactive Navigation Menu**: Hover effects with text animations and background elements
- **Responsive Design**: Adapts to different screen sizes
- **Smooth Animations**: CSS transitions and 3D transformations
- **Visual Effects**: Glowing borders, shadows, and gradient effects

## Project Structure

```
project/
├── index.html          # Main HTML file
├── style.css           # Stylesheet with all CSS rules
└── images/             # Directory containing all images
    ├── Desert.jpg
    ├── Tulips.jpg
    ├── Penguins.jpg
    ├── Lighthouse.jpg
    ├── Hydrangeas.jpg
    ├── Jellyfish.jpg
    ├── Koala.jpg
    ├── Chrysanthemum.jpg
    ├── download.jpg
    ├── 7d1jxsc8.jpeg
    └── images.jpg      # Background image
```

## HTML Structure

The project consists of:
- A container with a 3D slider for images
- A navigation section with interactive menu items
- Custom attributes for dynamic content

## CSS Features

- **3D Transformations**: Using `preserve-3d` and `perspective` for the carousel
- **CSS Variables**: Custom properties (`--quantity`, `--classing`) for dynamic calculations
- **Advanced Selectors**: Attribute selectors, pseudo-elements (`::before`, `::after`)
- **Animations**: Keyframe animation for continuous rotation
- **Hover Effects**: Interactive menu with transitions
- **Responsive Design**: Media queries for smaller screens

## How to Use

1. Clone or download the project files
2. Ensure all images are in the `images/` folder with the correct filenames
3. Open `index.html` in a web browser
4. Hover over menu items to see interactive effects
5. Watch the 3D carousel rotate automatically

## Customization

- Add more images by adding new `.item` divs in the slider and updating the `--quantity` value
- Modify colors by changing the CSS custom properties
- Adjust animation speed by changing the `animation-duration` in the `.slider` class
- Customize the menu items by updating the HTML list and corresponding CSS

## Browser Compatibility

This project uses modern CSS features including:
- CSS 3D Transforms
- CSS Variables (Custom Properties)
- CSS Grid and Flexbox
- CSS Animations and Transitions

For best results, use modern browsers that support these features.

## License

This project is open source and available under the MIT License.
