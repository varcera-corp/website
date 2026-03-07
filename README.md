# Varcera - Digital & Technology Services

A modern, elegant static website for Varcera that can be hosted on GitHub Pages.

## Features

- **System Theme Support**: Automatically adapts to user's system light/dark preference
- **Manual Theme Toggle**: Users can override system preference
- **Responsive Design**: Works on all devices (desktop, tablet, mobile)
- **Smooth Animations**: Subtle scroll animations and hover effects
- **Modern UI**: Clean, professional design with gradient accents
- **Accessible**: Semantic HTML, aria labels, and keyboard navigation

## Sections

- Hero with animated graphics
- Services showcase
- About with statistics
- Portfolio/Projects gallery
- Contact form
- Footer with social links

## Deploying to GitHub Pages

### Option 1: Deploy from main branch

1. Push this code to a GitHub repository
2. Go to **Settings** > **Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose `main` branch and select `/ (root)` folder
5. Click **Save**

Your site will be live at: `https://<username>.github.io/<repository-name>/`

### Option 2: Using as user/organization site

1. Create a repository named `<username>.github.io`
2. Push this code to the repository
3. The site will automatically be live at `https://<username>.github.io`

## Local Development

Simply open `index.html` in a browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve
```

## Customization

### Colors
Edit CSS custom properties in `styles.css`:
```css
:root {
    --color-primary: #6366f1;
    --color-secondary: #0ea5e9;
    /* ... */
}
```

### Content
Edit `index.html` to update:
- Company information
- Services offered
- Portfolio projects
- Contact details

### Contact Form
The contact form currently shows a success message on submit. To make it functional:
- Use a service like [Formspree](https://formspree.io/) or [Netlify Forms](https://www.netlify.com/products/forms/)
- Add your form endpoint to the form action

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2026 Varcera. All rights reserved.
