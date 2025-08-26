# Sri Vidya High School Website

A modern, responsive school website built with HTML, CSS, and JavaScript. This website showcases the school's information, facilities, curriculum, and provides a platform for parents and students to learn more about the institution.

## Features

### 🎯 Core Features
- **Responsive Design**: Fully mobile-friendly across all devices
- **5 Complete Pages**: Home, About, Gallery, Curriculum, and Contact
- **Announcement Scroll Bar**: Dynamic scrolling announcement for admissions
- **Interactive Gallery**: Filterable photo gallery with lightbox functionality
- **Contact Form**: Functional contact form with validation
- **FAQ Section**: Expandable FAQ with smooth animations
- **Sports Section**: Dedicated sports information with relevant icons

### 🎨 Design Features
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Color Scheme**: Dark blue (#1e3a8a) and yellow (#fbbf24) theme
- **Typography**: Poppins font family for excellent readability
- **Animations**: Smooth scroll animations, hover effects, and transitions
- **Icons**: Font Awesome icons throughout the website

### 📱 Mobile Responsiveness
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Responsive Grid**: Flexible layouts that adapt to screen sizes
- **Touch-Friendly**: Optimized for touch interactions
- **Fast Loading**: Optimized images and performance

## Pages Overview

### 1. Home Page (`index.html`)
- Hero section with school introduction
- Features highlighting school benefits
- School levels overview
- Sports and activities section
- Call-to-action buttons

### 2. About Page (`about.html`)
- School history and mission
- Salient features and achievements
- Parent communication details
- Recognition and accreditation
- 10 years of excellence celebration

### 3. Gallery Page (`gallery.html`)
- Filterable photo gallery (All, Activities, Events, Campus, Sports)
- Lightbox functionality for image viewing
- Keyboard navigation (arrow keys, escape)
- Responsive image grid

### 4. Curriculum Page (`curriculum.html`)
- Educational approach overview
- School levels (Play Group, Pre School, High School)
- Subjects and activities breakdown
- Special programs (IIT/Medical Foundation, Quiz competitions)
- Teaching methodology
- Academic calendar

### 5. Contact Page (`contact.html`)
- Contact information cards
- Interactive contact form
- Location and directions
- FAQ section
- School hours and office information

## File Structure

```
sri-vidya-high-school/
├── index.html          # Home page
├── about.html          # About page
├── gallery.html        # Gallery page
├── curriculum.html     # Curriculum page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
├── README.md           # This file
└── images/             # Image assets
    ├── logo.jpg
    ├── school_building.jpg
    ├── gallery1.jpg - gallery40.jpg
    └── 2025_results.jpg
```

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation
1. Download or clone the project files
2. Ensure all files are in the same directory
3. Open `index.html` in your web browser
4. The website should load with all functionality working

### Local Development
1. Use a local server (like Live Server in VS Code) for best experience
2. All features will work locally without any external dependencies

## Customization Guide

### Changing Colors
The main color scheme is defined in `styles.css`:
```css
/* Primary Colors */
--primary-blue: #1e3a8a;
--primary-yellow: #fbbf24;
--secondary-yellow: #f59e0b;
```

### Updating Content
1. **School Information**: Edit the content in each HTML file
2. **Images**: Replace images in the `images/` folder
3. **Contact Details**: Update phone numbers and address in all pages
4. **Announcements**: Modify the announcement text in the scroll bar

### Adding New Pages
1. Create a new HTML file
2. Copy the structure from existing pages
3. Update the navigation menu in all pages
4. Add corresponding styles in `styles.css`

### Modifying Animations
Animations are defined in `styles.css` and controlled by `script.js`:
```css
@keyframes fadeInUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
}
```

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- **Lazy Loading**: Images load as they come into view
- **Optimized Animations**: Smooth 60fps animations
- **Debounced Scroll Events**: Performance-optimized scroll handling
- **Minimal Dependencies**: Only Font Awesome for icons

## SEO Features

- Semantic HTML structure
- Meta tags for better search engine visibility
- Alt text for all images
- Proper heading hierarchy
- Mobile-friendly design (Google ranking factor)

## Accessibility Features

- Keyboard navigation support
- Screen reader friendly
- High contrast color scheme
- Proper ARIA labels
- Focus indicators

## Contact Information

The website includes the following contact details:
- **Phone**: 7032844031, 7337058032
- **Address**: Nandhi hills, Road no 8, Near anjaneya swamy temple, meerpet, hyderabad
- **Email**: info@srividyahighschool.com, admissions@srividyahighschool.com

## License

This project is created for Sri Vidya High School. All rights reserved.

## Support

For any questions or customization requests, please contact the development team.

---

**Note**: This website is designed to be a complete, professional school website that can be easily customized and maintained. All the content is based on the provided school information and images. 