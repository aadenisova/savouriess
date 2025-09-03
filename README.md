# Personal Website Template

A beautiful, elegant personal website template with a dark theme and bright accent colors. Perfect for researchers, scientists, and creative professionals.

## Features

- **Elegant Dark Theme**: Sophisticated dark color palette with bright accent colors
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern Typography**: Uses Inter and Playfair Display fonts for a refined look
- **Smooth Animations**: Subtle animations and transitions for a polished experience
- **Easy to Customize**: Well-structured code that's easy to modify
- **GitHub Pages Ready**: Configured for easy deployment

## Color Palette

- **Background**: Deep blacks and dark grays (#0a0a0a, #1a1a1a, #2a2a2a)
- **Text**: Clean whites and light grays (#ffffff, #b0b0b0, #808080)
- **Accents**: Bright coral (#ff6b6b), teal (#4ecdc4), mint (#a8e6cf), gold (#ffd93d)

## Quick Start

1. **Clone or download** this repository
2. **Edit the content** in `index.html` (simple template) or `aleksandra.html` (full example)
3. **Customize colors** in `styles.css` if desired
4. **Deploy to GitHub Pages** (see instructions below)

## File Structure

```
├── index.html          # Simple template version
├── aleksandra.html     # Full example with content
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization Guide

### 1. Personal Information
Edit the following in your HTML file:
- Name in navigation and hero section
- Professional title and description
- About section content
- Contact information

### 2. Sections
The template includes these sections:
- **Hero**: Introduction and main title
- **About**: Personal background and story
- **Projects/Research**: Your work and achievements
- **Writing**: Articles, stories, or publications
- **Photography**: Visual content
- **Contact**: Ways to get in touch

### 3. Colors
To change colors, edit the CSS variables in `styles.css`:
```css
:root {
    --bg-primary: #0a0a0a;        /* Main background */
    --accent-coral: #ff6b6b;      /* Primary accent */
    --accent-blue: #4ecdc4;       /* Secondary accent */
    /* ... other colors */
}
```

### 4. Typography
The template uses:
- **Inter**: For body text and UI elements
- **Playfair Display**: For headings and display text

To change fonts, update the Google Fonts link in the HTML head and the CSS variables.

## GitHub Pages Deployment

### Method 1: Automatic (Recommended)
1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Method 2: GitHub Actions
1. Create a `.github/workflows/deploy.yml` file
2. Use GitHub Actions to build and deploy your site
3. More control over the deployment process

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Optimized CSS with minimal dependencies
- Lightweight JavaScript for smooth interactions
- Fast loading times with efficient code structure

## License

This template is free to use for personal and commercial projects. Feel free to modify and adapt it to your needs.

## Support

If you have questions or need help customizing the template, feel free to reach out or create an issue in the repository.

---

**Note**: Remember to replace placeholder content with your actual information before publishing your site.
