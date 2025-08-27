# Trogon IT Solutions - Parallax Website

A modern, responsive parallax website built for Trogon IT Solutions, showcasing software services with beautiful animations and interactive elements.

## 🚀 Features

- **Parallax Scrolling Effects** - Smooth parallax backgrounds for immersive experience
- **Responsive Design** - Mobile-first approach with mobile navigation
- **Modern UI/UX** - Clean, professional design with your brand colors
- **Interactive Elements** - Hover effects, scroll animations, and smooth transitions
- **Contact Form** - Functional contact form with validation and notifications
- **Performance Optimized** - Throttled scroll events and efficient animations
- **Cross-browser Compatible** - Works on all modern browsers

## 🎨 Brand Colors

The website uses your logo's color scheme:
- **Primary**: Purple (#8B5CF6) - Used for main elements and accents
- **Secondary**: Golden Yellow (#F59E0B) - Used for highlights and CTAs
- **Accent**: Light Yellow (#FCD34D) - Used for special elements
- **Dark**: Deep Gray (#111827) - Used for backgrounds and text

## 📁 File Structure

```
new_website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Open the website**: Simply open `index.html` in your web browser
2. **Local development**: Use a local server for best experience:
   - Python: `python -m http.server 8000`
   - Node.js: `npx serve .`
   - VS Code: Use Live Server extension

## 🎯 Customization Guide

### Updating Company Information

Edit the following sections in `index.html`:

#### Contact Information
```html
<!-- Update in the contact section -->
<p>info@trogonit.com</p>
<p>+1 (555) 123-4567</p>
<p>123 Tech Street, Digital City, DC 12345</p>
```

#### Services
```html
<!-- Update in the services section -->
<div class="service-card">
    <h3>Your Service Name</h3>
    <p>Your service description</p>
</div>
```

#### Portfolio Projects
```html
<!-- Update in the portfolio section -->
<div class="portfolio-item">
    <h3>Your Project Name</h3>
    <p>Project description</p>
</div>
```

### Changing Colors

Update CSS variables in `styles.css`:

```css
:root {
    --primary-color: #8B5CF6;    /* Your purple */
    --secondary-color: #F59E0B;  /* Your golden yellow */
    --accent-color: #FCD34D;     /* Your light yellow */
    /* ... other colors */
}
```

### Adding New Sections

1. Add HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Add any JavaScript functionality in `script.js`

## 📱 Mobile Responsiveness

The website is fully responsive with:
- Mobile-first navigation
- Adaptive grid layouts
- Touch-friendly interactions
- Optimized typography for small screens

## 🌟 Animation Features

- **Fade-in animations** on scroll
- **Parallax backgrounds** for depth
- **Hover effects** on interactive elements
- **Smooth scrolling** navigation
- **Counter animations** for statistics
- **Loading animations** for service cards

## 🔧 Technical Details

### CSS Features
- CSS Grid and Flexbox layouts
- CSS Custom Properties (variables)
- Modern CSS animations and transitions
- Backdrop filters and gradients
- Responsive breakpoints

### JavaScript Features
- Intersection Observer API for scroll animations
- Event throttling for performance
- Form validation and handling
- Mobile navigation management
- Parallax effect implementation

### Performance Optimizations
- Throttled scroll events (60fps)
- Efficient DOM queries
- Optimized animations
- Minimal reflows and repaints

## 🚀 Deployment

### Static Hosting
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your GitHub repository
- **GitHub Pages**: Push to a repository and enable Pages
- **AWS S3**: Upload files to S3 bucket

### Custom Domain
1. Purchase domain from your preferred registrar
2. Configure DNS settings to point to your hosting
3. Update any hardcoded URLs in the code

## 📧 Contact Form Setup

The contact form currently shows a success message. To make it functional:

1. **Backend Integration**: Connect to your preferred backend service
2. **Email Service**: Use services like:
   - Formspree
   - Netlify Forms
   - EmailJS
   - Custom backend API

### Example with Formspree
```html
<form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
    <!-- form fields -->
</form>
```

## 🎨 Logo Integration

The current logo uses emoji and text. To use your actual logo:

1. Replace the logo section in `index.html`:
```html
<div class="logo">
    <img src="path/to/your/logo.png" alt="Trogon IT Solutions" class="logo-image">
</div>
```

2. Add CSS for the logo image:
```css
.logo-image {
    height: 40px;
    width: auto;
}
```

## 🔍 SEO Optimization

The website includes:
- Semantic HTML structure
- Meta tags for social sharing
- Proper heading hierarchy
- Alt text for images
- Fast loading times

## 🧪 Testing

Test the website on:
- Different browsers (Chrome, Firefox, Safari, Edge)
- Various screen sizes (mobile, tablet, desktop)
- Different devices (touch and mouse input)
- Slow internet connections

## 📈 Analytics

To add analytics:
1. **Google Analytics**: Add tracking code to `<head>`
2. **Google Tag Manager**: Implement GTM container
3. **Custom tracking**: Add event listeners in `script.js`

## 🚀 Future Enhancements

Potential improvements:
- Blog section
- Team member profiles
- Client testimonials
- Case study details
- Multi-language support
- Dark/light theme toggle
- Advanced animations
- CMS integration

## 📞 Support

For customization help or questions:
- Review the code comments
- Check browser console for errors
- Test on different devices
- Validate HTML/CSS using online tools

## 📄 License

This website template is created for Trogon IT Solutions. Feel free to modify and use for your business needs.

---

**Built with ❤️ for Trogon IT Solutions**

Transform your digital presence with this modern, professional website that showcases your software expertise and attracts potential clients.
