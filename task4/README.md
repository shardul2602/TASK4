# Task 4: Mobile-Friendly Website with CSS Media Queries

## Project Overview
This project demonstrates converting a desktop-only website to a mobile-friendly layout using CSS media queries. The website includes multiple sections that adapt responsively to different screen sizes.

## Files Created
- `index.html` - Main HTML structure with navigation, hero section, about, services, and contact sections
- `styles.css` - CSS with desktop-first design and mobile media queries
- `script.js` - JavaScript for mobile navigation functionality
- `README.md` - This documentation file

## Features Implemented

### Desktop Design (Default)
- Fixed-width container (1200px max-width)
- Horizontal layout with flexbox and grid
- Large images and text sizes
- Horizontal navigation menu
- Side-by-side content sections

### Mobile Responsiveness (max-width: 768px)
- **Navigation**: Hamburger menu that collapses vertically
- **Layout**: Content stacks vertically instead of horizontally
- **Typography**: Reduced font sizes for mobile readability
- **Spacing**: Adjusted padding and margins for mobile
- **Images**: Scale properly within containers
- **Grid**: Services change from 3 columns to 1 column

### Small Mobile (max-width: 480px)
- Further reduced font sizes and spacing
- Optimized button and form element sizes

## How to Test

### 1. Open in VS Code
- Open the `index.html` file in VS Code
- Right-click and select "Open with Live Server" or open in a browser

### 2. Test with Chrome DevTools
1. Open Chrome DevTools (F12 or right-click → Inspect)
2. Click the "Toggle device toolbar" button (mobile icon)
3. Test different device sizes:
   - Desktop (default)
   - Tablet (768px and below)
   - Mobile (480px and below)

### 3. Test Responsive Features
- **Navigation**: On mobile, click the hamburger menu to see the collapsible navigation
- **Layout**: Watch how sections stack vertically on mobile
- **Images**: Ensure images scale properly without overflow
- **Forms**: Check that form elements are properly sized for mobile

## Key CSS Media Query Breakpoints

```css
/* Tablet and small desktop */
@media (max-width: 768px) {
    /* Major layout changes */
}

/* Small mobile devices */
@media (max-width: 480px) {
    /* Further optimizations */
}
```

## Responsive Design Principles Applied

1. **Mobile-First Approach**: Base styles for desktop, then override for mobile
2. **Flexible Layouts**: Using flexbox and grid that adapt to screen size
3. **Responsive Images**: Images scale within containers using `max-width: 100%`
4. **Touch-Friendly**: Proper button sizes and spacing for mobile interaction
5. **Readable Typography**: Adjusted font sizes for mobile screens
6. **Collapsible Navigation**: Mobile-friendly hamburger menu

## Testing Checklist

- [ ] Website loads properly on desktop
- [ ] Navigation collapses to hamburger menu on mobile
- [ ] Content stacks vertically on mobile devices
- [ ] Images scale properly without horizontal scrolling
- [ ] Forms are usable on mobile devices
- [ ] Text is readable on all screen sizes
- [ ] No horizontal overflow issues
- [ ] Touch targets are appropriately sized

## Browser Compatibility
- Chrome (recommended for DevTools testing)
- Firefox
- Safari
- Edge

## Next Steps
You can further customize this website by:
- Adding more content sections
- Implementing additional breakpoints
- Adding animations and transitions
- Customizing colors and typography
- Adding more interactive features
