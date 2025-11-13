# Koyoyo College Africa Website

A modern, responsive educational institution website built with pure HTML, CSS, and JavaScript. Features glassmorphism design, smooth animations, and comprehensive functionality for a college campus.

## Overview

Koyoyo College Africa is a fully responsive website showcasing a leading educational institution with programs, admissions, student portal, and gallery. The site is optimized for mobile, tablet, and desktop devices with a focus on modern design aesthetics and user experience.

## Features

### Core Pages

- **Homepage (index.html)** - Hero banner, about section, programs showcase, testimonials, and admissions call-to-action
- **Admissions (admissions.html)** - Application requirements, forms integration, payment details, and admission guidelines
- **Contact Us (contact.html)** - Contact information, contact form, location map, and support details
- **Students Portal (students.html)** - Google Classroom access, drive resources, WASSCE appeals, academic calendar, and important documents
- **Gallery (gallery.html)** - Interactive image gallery with category filters, hover effects, and smooth animations

### Design Features

- **Glassmorphism UI** - Frosted glass effects with backdrop blur and transparency
- **Glowing Cards** - Radial glow effects on hover with smooth scale transformations
- **Smooth Animations** - Fade-in, slide-up, and pop-up animations triggered on scroll
- **Responsive Grid System** - 
  - Mobile: 1 column layouts
  - Tablet: 2 column layouts
  - Desktop: 3-4 column layouts
- **Dark Mode Theme** - Beautiful dark gradient backgrounds with vibrant cyan and purple accents
- **Interactive Elements** - Hover states, active states, and smooth transitions throughout

### Responsive Design

- **Mobile First Approach** - Optimized for all screen sizes
- **Breakpoints:**
  - Mobile: 480px and below
  - Tablet: 768px and below
  - Desktop: 1024px and above
- **Hamburger Navigation** - Mobile-friendly collapsible menu
- **Flexible Components** - Cards, grids, and layouts adapt seamlessly

## Technology Stack

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with gradients, animations, and backdrop filters
- **Vanilla JavaScript** - No dependencies or frameworks
- **Google Fonts** - Playfair Display (headings), Inter/Outfit (body)
- **Font Awesome 6** - Icon library for UI elements
- **Google Maps** - Location embeds
- **Tally Forms** - Application form integration
- **Google Classroom** - Student portal integration
- **Google Drive** - Resource sharing

## Project Structure

\`\`\`
koyoyo-college-website/
├── index.html                 # Homepage with programs and testimonials
├── admissions.html            # Admissions page with forms and payment info
├── contact.html               # Contact page with form and map
├── students.html              # Student portal with classroom access
├── gallery.html               # Interactive gallery with filters
├── logo.png                   # College logo (to be uploaded)
└── README.md                  # This file
\`\`\`

## Getting Started

### Prerequisites

No build tools or dependencies required. Just a modern web browser.

### Installation

1. **Clone the repository**
   \`\`\`bash
   git clone https://github.com/koyoyocollege/website.git
   cd website
   \`\`\`

2. **Add your logo**
   - Place your college logo as `logo.png` in the root directory
   - Recommended size: 45x45px
   - The logo will automatically appear across all pages

3. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or serve locally using any static server:
     \`\`\`bash
     python -m http.server 8000
     # Visit http://localhost:8000
     \`\`\`

### Deployment

#### Deploy to GitHub Pages

1. Push your repository to GitHub
2. Enable GitHub Pages in repository settings (Settings → Pages)
3. Select main branch as source
4. Your site will be live at `https://username.github.io/repository`

#### Deploy to Vercel

1. Connect your GitHub repository to Vercel
2. Vercel automatically deploys on push
3. Get a live URL instantly

#### Deploy to Netlify

1. Connect your GitHub repository to Netlify
2. Set build command to empty (no build needed)
3. Set publish directory to root (/)
4. Deploy

## Customization

### Update College Information

**Homepage - About Section:**
\`\`\`html
<!-- In index.html, find the about-section -->
<p>Update with your college mission and vision...</p>
\`\`\`

**Footer - Social Links:**
\`\`\`html
<a href="https://facebook.com/yourpage">Facebook</a>
<a href="https://instagram.com/yourpage">Instagram</a>
\`\`\`

**Contact Page - Location:**
\`\`\`html
<p><i class="fas fa-map-marker-alt"></i>Your Location, City, Country</p>
<p><i class="fas fa-phone"></i>+233 XX XXX XXXX</p>
\`\`\`

### Customize Colors

All colors are defined in CSS. The main color scheme uses:

- **Primary Blue:** `#0066ff`
- **Accent Cyan:** `#06b6d4`
- **Secondary Purple:** `#7c3aed`
- **Background Dark:** `#0f172a`
- **Text Light:** `#f1f5f9`

Modify these values throughout the CSS `<style>` sections to match your brand.

### Update Programs

**Homepage Programs Section:**
\`\`\`html
<div class="program-card">
    <h3>Your Program Name</h3>
    <p>Description of the program...</p>
</div>
\`\`\`

### Customize Gallery

Add new images to the gallery:
\`\`\`html
<div class="gallery-card" data-category="category-name">
    <img src="your-image-url" alt="Description" class="gallery-card-image">
    <div class="gallery-card-overlay">
        <div class="gallery-card-content">
            <div class="gallery-card-title">Title</div>
            <div class="gallery-card-description">Description</div>
        </div>
    </div>
</div>
\`\`\`

## Features Explained

### Hamburger Navigation

- Click the hamburger menu on mobile to toggle navigation
- Automatically closes when a link is clicked
- Smooth animation with rotate and opacity effects

### Gallery Filter System

Click filter buttons to show specific categories:
- **All** - Show all images
- **Campus** - Campus facilities and buildings
- **Events** - College events and celebrations
- **Academics** - Classroom and learning environments
- **Sports** - Sports and athletic activities

### Floating Apply Button

A sticky call-to-action button in the bottom-right corner:
- Fixed position that stays visible while scrolling
- Links to the admissions form
- Responsive positioning on mobile

### Intersection Observer Animations

Cards and content fade in and slide up as they enter the viewport:
- Smooth 0.6s animation
- Staggered delays for visual interest
- Works on all card-based components

### Responsive Images

All images use:
- `object-fit: cover` - Maintains aspect ratio
- `object-position: center` - Centers image within container
- Smooth transitions on hover

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- **Optimized:** No external dependencies except Google Fonts and Font Awesome
- **Fast:** Single-page components with minimal reflows
- **Lightweight:** All CSS and JS inline for single-file pages
- **Images:** Lazy loading via native browser support
- **Animations:** GPU-accelerated CSS transforms

## Best Practices

### Code Organization

- Semantic HTML elements (`<header>`, `<nav>`, `<footer>`, `<section>`)
- Consistent naming conventions for CSS classes
- Modular CSS for easy maintenance
- Vanilla JavaScript with clear function names

### Accessibility

- Proper heading hierarchy (h1, h2, h3)
- Alt text for all images
- ARIA labels where needed
- Keyboard navigation support
- Sufficient color contrast ratios

### SEO

- Meta tags for title and description
- Semantic HTML structure
- Proper heading tags
- Mobile-responsive design
- Fast page load times

## Maintenance

### Updating Links

Update navigation links in header and footer:
\`\`\`html
<a href="admissions.html">Admissions</a>
<a href="contact.html">Contact Us</a>
\`\`\`

### Updating Forms

- Admissions form uses Tally (tally.so)
- Contact form can be connected to your backend
- Update form action and method as needed

### Updating External Resources

- Google Drive: Update folder link in Students Portal
- Google Classroom: Update classroom codes
- Google Maps: Update embed coordinates
- Social links: Update with your profiles

## Troubleshooting

### Images not loading
- Check image URLs are correct and accessible
- Ensure CORS headers are set if using external images
- Use HTTPS URLs for external images

### Navigation menu not working
- Check JavaScript is enabled
- Ensure hamburger ID matches script references
- Clear browser cache and reload

### Forms not submitting
- Verify form action URLs
- Check for JavaScript errors in browser console
- Ensure form fields have proper names

### Animations not working
- Update browser to latest version
- Check CSS is loading correctly
- Verify JavaScript intersection observer is supported

## Contributing

To contribute improvements:

1. Create a feature branch
2. Make your changes
3. Test across devices
4. Submit a pull request with description

## File Size Information

- **Homepage (index.html):** ~45KB
- **Admissions (admissions.html):** ~35KB
- **Contact (contact.html):** ~25KB
- **Students (students.html):** ~40KB
- **Gallery (gallery.html):** ~30KB
- **Total:** ~175KB (all pages combined)

## Security Notes

- All pages are static HTML/CSS/JS
- No backend server required
- External forms (Tally) handle submissions securely
- Use HTTPS when deployed
- Sanitize any user-generated content

## Future Enhancements

- Blog section for news and updates
- Staff directory with profiles
- Event calendar system
- Alumni network section
- Online payment integration
- Chatbot support system

## Support

For issues or questions:
- Email: koyoyocollege@gmail.com
- Phone: +233 59 860 9544
- WhatsApp: https://wa.me/233594860849

## License

This website is proprietary to Koyoyo College Africa. All rights reserved © 2025.

## Credits

- **Design:** Modern glassmorphism with dark theme
- **Icons:** Font Awesome 6
- **Fonts:** Google Fonts (Playfair Display, Inter, Outfit)
- **Images:** Unsplash, Imgur
- **Forms:** Tally
- **Integrations:** Google Services

---

**Last Updated:** November 2025

**Version:** 1.0

For more information, visit [Koyoyo College Africa Website](#)
