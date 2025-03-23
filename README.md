# Masonry Image Gallery with Lightbox

A modern, responsive image gallery implementation featuring a masonry layout and lightbox preview functionality. Built with vanilla JavaScript, CSS, and HTML.

## Features

- **Masonry Layout**: Dynamic grid layout that optimally arranges images based on their dimensions
- **Lightbox Preview**: Click any image to view it in a full-screen lightbox modal
- **Responsive Design**: Adapts seamlessly to different screen sizes and devices
- **Smooth Animations**: Includes hover effects and smooth transitions
- **Modern UI**: Clean and intuitive user interface with minimal design

## Demo

The gallery displays images in a Pinterest-style masonry layout. When you click an image:
1. A lightbox modal opens
2. The selected image appears in full view
3. The background dims for focus
4. Close the preview using the X button

## Installation

1. Clone or download this repository
2. Place your images in the `images` folder
3. Update the image sources in `index.html` to match your image filenames
4. Open `index.html` in a web browser

## Technical Implementation

### HTML Structure
- Main gallery container with masonry layout
- Lightbox modal for image preview
- Responsive image elements

### CSS Features
- CSS Grid with `columns` property for masonry layout
- Flexbox for centering and alignment
- Smooth transitions and transforms
- Media queries for responsive design

### JavaScript Functionality
- Event listeners for image clicks
- Lightbox modal control
- Dynamic image source updates
- Scroll management during preview

## Dependencies

- [Unicons](https://iconscout.com/unicons) - Icon library for UI elements
- [Google Fonts (Poppins)](https://fonts.google.com/specimen/Poppins) - Main font family

## Browser Compatibility

Tested and working in:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Customization

You can customize the gallery by:
- Adjusting the number of columns in `style.css`
- Modifying transition timings
- Changing colors and styling
- Updating the lightbox behavior

## Credits

Designed and developed by Hasnain Arif

## License

Feel free to use this project for personal and commercial purposes.