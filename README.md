# Julio Arana Cortes Real Estate Website

A professional, modern landing page for Julio Arana Cortes Real Estate in Santa Ana, California.

## Features

✅ **Responsive Design** - Mobile-first approach, works on all devices
✅ **Hero Section** - Eye-catching introduction with CTA buttons
✅ **Services Showcase** - 4 key services with icons and descriptions
✅ **About Section** - Business story and values
✅ **Statistics** - Trust-building metrics and ratings
✅ **Client Testimonials** - Real reviews from satisfied clients
✅ **Contact Form** - Email-based inquiry system
✅ **Modern Aesthetics** - Clean design with premium color scheme
✅ **Fast Performance** - No dependencies, pure HTML/CSS/JS

## File Structure

```
julio-real-estate/
├── index.html       # Main HTML structure
├── styles.css       # All styling and responsive layouts
├── script.js        # Interactive features and form handling
└── README.md        # This file
```

## Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yashsalave42-dev/julio-real-estate.git
   cd julio-real-estate
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - No build process or dependencies required

3. **Deploy**
   - Upload files to any web hosting service
   - Works with GitHub Pages, Vercel, Netlify, or any static host

## Customization

### Update Contact Information
Edit these fields in `index.html`:
- Phone number: `(949) 415-6305`
- Address: `206 W 4th St Ste 433, Santa Ana, CA 92701`
- Email: Update the `mailto:` link in `script.js`

### Modify Colors
Update CSS variables in `styles.css`:
```css
:root {
  --primary: #0f172a;      /* Dark blue */
  --accent: #c89b3c;       /* Gold */
  --text: #1f2937;         /* Dark gray */
  --bg: #f8fafc;           /* Light background */
}
```

### Change Images
Update image URLs in `styles.css`:
- Hero background: `.hero` section
- About section: `.about-image` section

### Edit Text Content
All text is directly in `index.html` - simply find and replace:
- Testimonials
- Service descriptions
- About section content
- Stats and metrics

## Form Handling

The contact form uses the `mailto:` protocol to send inquiries via email. To set up automatic email forwarding:

1. Update the email address in `script.js`:
   ```javascript
   const mailtoLink = `mailto:your-email@example.com?subject=...`
   ```

2. **Better option:** Integrate with a backend service:
   - Formspree (https://formspree.io)
   - EmailJS (https://www.emailjs.com)
   - Netlify Forms (if deployed on Netlify)

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Android)

## Performance

- **No dependencies** - Pure HTML, CSS, and vanilla JavaScript
- **Fast loading** - Optimized images and minimal CSS
- **Mobile optimized** - Responsive design, touch-friendly
- **SEO friendly** - Semantic HTML, meta tags included

## License

Free to use and modify for personal or commercial purposes.

## Support

For questions or modifications, contact the developer or create an issue in the repository.
