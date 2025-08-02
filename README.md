# Furniro - Beautiful Rooms Inspiration Section

This project contains a modern, responsive inspiration section for a furniture website that matches the design from the provided reference images.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Carousel**: Smooth slide transitions with navigation arrows and dots
- **Modern UI**: Clean design with golden accent colors (#b88e2f)
- **Accessibility**: Keyboard navigation and focus states
- **Auto-play**: Automatically advances slides every 5 seconds
- **Hover Effects**: Enhanced interactions with smooth animations

## Structure

### HTML Structure
- `inspiration-section`: Main container
- `inspiration-content`: Left side text content
- `inspiration-carousel`: Right side image carousel
- `slide-overlay`: Semi-transparent cards overlaid on images
- `carousel-nav`: Navigation arrows
- `carousel-dots`: Slide indicators

### Required Assets

Place your images in the following directories:

```
assest/
├── images/
│   ├── bedroom.jpeg
│   ├── living_room.jpeg
│   └── Dining_room.jpeg
└── icons/
    ├── next_icon_sq.png
    └── next_icons.png
```

## Customization

### Colors
- Primary accent: `#b88e2f` (golden brown)
- Text dark: `#3a3a3a`
- Text light: `#616161`
- Background: `#fcf8f3`

### Typography
Uses Google Fonts 'Poppins' with weights: 300, 400, 500, 600, 700

### Carousel Settings
- Auto-play interval: 5 seconds
- Transition duration: 0.5 seconds
- Number of slides: 3 (easily expandable)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Usage

1. Ensure all image assets are in the correct directories
2. Open `index.html` in a web browser
3. The carousel will automatically start playing
4. Users can navigate using:
   - Arrow buttons on the sides
   - Dot indicators at the bottom
   - Touch/swipe on mobile devices

## Responsive Breakpoints

- Desktop: 1024px and above
- Tablet: 768px - 1023px
- Mobile: 767px and below
- Small mobile: 480px and below

## File Structure

```
├── index.html          # Main HTML file
├── style.css           # Complete CSS styles
├── assest/
│   ├── images/         # Room images
│   └── icons/          # Navigation icons
└── README.md           # This file
```

## Development Notes

- The carousel uses CSS transforms for smooth animations
- JavaScript handles slide navigation and auto-play
- All animations are CSS-based for optimal performance
- Images use object-fit: cover for consistent sizing
- Backdrop blur effects for modern glass-morphism look

## Installation

No installation required. Simply:

1. Clone or download the files
2. Add your images to the `assest/` directories
3. Open `index.html` in a web browser

The section is completely self-contained and ready to use!