# 🎮 Pokemon Landing Page

A modern, responsive Pokemon showcase landing page featuring Pikachu with an elegant two-column layout design.

## 📋 Project Overview

This project is a CSS-based landing page assignment that showcases Pokemon information with an interactive UI. The page features a clean split-screen design with detailed Pokemon information on the left and navigation elements on the right.

## ✨ Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern Layout**: Two-column flex-based design on desktop that stacks on mobile
- **Pokemon Showcase**: Detailed information display for featured Pokemon
- **Interactive Navigation**: Dot indicators for pagination/carousel navigation
- **Optimized Images**: Centered Pokemon image overlay
- **Clean Typography**: Professional font styling with proper hierarchy

## 🛠 Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Flexbox, media queries, and responsive design
- **Font Awesome 6.7.2**: Icon library for UI elements
- **Responsive Design**: Mobile-first approach with breakpoints at 768px and 480px

## 📁 Project Structure

```
Pokemon/
├── index.html          # HTML markup
├── style.css           # CSS styling and responsive design
├── README.md           # Project documentation
└── assets/
    ├── pngegg.png     # Logo image
    └── pngegg (1).png # Pokemon (Pikachu) image
```

## 🎯 Layout Breakdown

### First Half (60% - Desktop)

- Pokemon logo
- Pokemon generation label
- Pokemon name (Pikachu)
- Detailed description
- Episode counter (01/08)

### Second Half (40% - Desktop)

- Navigation menu (hamburger icon)
- Pagination dots (navigation indicators)

### Center Overlay

- Large centered Pokemon image

## 📱 Responsive Breakpoints

### Desktop (1024px and above)

- 60% / 40% split layout
- Full-size typography
- All elements visible

### Tablet (768px and below)

- Stacked full-width layout
- Reduced font sizes
- Adjusted spacing and margins

### Mobile (480px and below)

- Single column layout
- Optimized images (Pikachu image hidden)
- Compact spacing
- Touch-friendly interface

## 🚀 How to Use

1. **Open the project**: Open `index.html` in your web browser
2. **View responsiveness**: Resize your browser window to see the responsive design in action
3. **Customize**: Edit `style.css` to change colors, fonts, or layout
4. **Update content**: Modify `index.html` to showcase different Pokemon

## 🎨 Color Scheme

- **Primary Yellow**: `rgba(243, 213, 40, 0.884)` - Main background (left)
- **Secondary Cream**: `rgb(253, 231, 171)` - Side panel (right)
- **Accent Red**: Used for icon borders

## 📦 Dependencies

- Font Awesome CDN: Used for icons (hamburger menu and circle indicators)
- No external JavaScript required - pure CSS styling

## 💡 Key CSS Features

- **Flexbox Layout**: Flexible and responsive container
- **Media Queries**: Responsive design implementation
- **Transform Properties**: Image positioning and centering
- **Opacity Effects**: Subtle text styling
- **Border Radius**: Smooth icon styling

## 🔄 Navigation Indicators

- First dot: Solid circle (current page)
- Other dots: Hollow circles (navigation to other pages)
- Icons styled with Font Awesome

## ✅ Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Notes

- All measurements use relative units (%, vh, vw) for better responsiveness
- Images are positioned absolutely for layering effect
- The layout uses `display: flex` for modern browser support

## 🎓 Assignment Purpose

This project demonstrates:

- CSS layout techniques (Flexbox)
- Responsive web design principles
- Media query implementation
- CSS positioning and sizing
- Modern web design patterns

---

**Created for**: Sheriyans Web Development Course  
**Assignment Type**: CSS Assignment - Pokemon Landing Page
