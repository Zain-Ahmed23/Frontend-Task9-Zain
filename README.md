# ExploreNow - Travel Landing Page

A modern, responsive travel landing page for ExploreNow travel agency built with HTML5, CSS3, and Vanilla JavaScript.

## Features

### 🎨 Design & UI/UX
- **Modern Design**: Clean, professional interface with beautiful imagery
- **Responsive Layout**: Fully responsive across mobile, tablet, and desktop
- **Dark Mode**: Toggle between light and dark themes
- **Smooth Animations**: CSS animations and transitions for enhanced user experience
- **Professional Typography**: Modern font stack with proper hierarchy

### 🚀 Functionality
- **Interactive Search**: Functional search form with validation
- **Smooth Scrolling**: Navigation links with smooth scroll behavior
- **Mobile Menu**: Responsive mobile navigation
- **Scroll to Top**: Button appears when scrolling down
- **Form Validation**: Client-side validation for search and newsletter forms
- **Theme Persistence**: Dark mode preference saved in localStorage

### 📱 Responsive Features
- **Mobile-First Design**: Optimized for all screen sizes
- **Flexible Grid Layouts**: CSS Grid and Flexbox for responsive layouts
- **Touch-Friendly**: Optimized for touch devices
- **Performance Optimized**: Fast loading with optimized images

## Sections

### Header
- Logo and navigation menu
- Dark mode toggle
- "Book Now" call-to-action button
- Mobile-responsive hamburger menu

### Hero Section
- Full-width background image
- Compelling tagline
- Interactive search form with destination, date, and budget fields
- Form validation with user feedback

### Destinations
- 6 popular destinations in responsive grid
- High-quality destination images
- Hover effects with image zoom
- Descriptive content for each destination

### Travel Packages
- 3 travel packages with pricing
- Featured package highlighting
- Package details and features
- Call-to-action buttons

### Testimonials
- Customer reviews with profile images
- Professional testimonial layout
- Hover effects for engagement

### Footer
- Company information and social links
- Quick navigation links
- Contact information
- Newsletter subscription form

## Technical Implementation

### HTML5
- Semantic HTML structure
- Proper accessibility attributes
- Meta tags for SEO
- Font Awesome icons integration

### CSS3
- CSS Custom Properties (variables) for theming
- Flexbox and CSS Grid for layouts
- CSS animations and transitions
- Media queries for responsive design
- Dark mode implementation

### JavaScript
- Vanilla JavaScript (no frameworks)
- Form validation and error handling
- Local storage for theme persistence
- Intersection Observer for scroll animations
- Event delegation and handling

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Getting Started

1. **Clone or download** the project files
2. **Open `index.html`** in your web browser
3. **No build process required** - it's ready to use!

## File Structure

```
explorenow-travel/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## Customization

### Colors
Modify CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --accent-color: #f59e0b;
    /* ... other variables */
}
```

### Content
- Update destination images and descriptions in `index.html`
- Modify package details and pricing
- Change testimonials and contact information

### Styling
- Adjust spacing, fonts, and colors in `styles.css`
- Modify animations and transitions
- Update responsive breakpoints

## Features in Detail

### Search Form Validation
- Required field validation
- Date validation (future dates only)
- User-friendly error messages
- Success confirmation

### Dark Mode
- Toggle between light and dark themes
- Persistent preference storage
- Smooth theme transitions
- Proper contrast ratios

### Mobile Responsiveness
- Breakpoints: 768px (tablet), 480px (mobile)
- Flexible grid layouts
- Touch-optimized interactions
- Mobile-first approach

### Performance
- Optimized images from Unsplash
- Minimal JavaScript footprint
- Efficient CSS animations
- Fast loading times

## Future Enhancements

- Backend integration for form submission
- Image lazy loading
- Advanced search filters
- Booking system integration
- Multi-language support
- Progressive Web App features

## Credits

- **Images**: [Unsplash](https://unsplash.com/)
- **Icons**: [Font Awesome](https://fontawesome.com/)
- **Fonts**: Inter font family

## License

This project is open source and available under the [MIT License](LICENSE).

---

Built with ❤️ for modern web development best practices.
