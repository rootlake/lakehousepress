# Lakehouse Press

**A mom & pop indie publisher that supports indie authors**

Website for our indie publishing company and author services. A simple, modern, and cozy website showcasing our publishing services, books, and design work.

🌐 **Live Site**: [View on GitHub Pages](https://rootlake.github.io/lakehousepress/)

## Features

- **Light/Dark Mode**: Toggle between day and night themes with a beautiful blue color palette
- **Responsive Design**: Works beautifully on all devices
- **Six Pages**: Home, Services, Books, Design Samples (gallery), Contact, and About
- **GitHub Pages**: Deployed automatically on push to main branch

## File Structure

```
/
├── index.html              # Home page
├── services.html           # Services page
├── books.html              # Books listing page
├── design-samples.html     # Gallery page
├── contact.html            # Contact form page
├── about.html              # About page
├── css/
│   └── styles.css          # Main stylesheet with light/dark themes
├── js/
│   └── theme-toggle.js     # Theme switching functionality
├── images/
│   └── mainlogo.png        # Logo image
└── README.md               # This file
```

## Setup

1. Your logo (`mainlogo.png`) is already in the `images/` folder
2. Replace placeholder content with your actual content
3. Add design sample images to the `images/` folder (sample-1.jpg through sample-6.jpg) or update the gallery section

## GitHub Pages Deployment

This site is configured for GitHub Pages deployment:

1. **Enable GitHub Pages**:
   - Go to repository Settings > Pages
   - Select "Deploy from a branch"
   - Choose `main` branch and `/ (root)` folder
   - Click Save

2. **Your site will be live at**: `https://rootlake.github.io/lakehousepress/`

The site will automatically rebuild when you push changes to the main branch.

## Future Enhancements

- Payment integration for book sales
- Backend form handling for contact form
- Blog section
- Book preview pages
- Shopping cart functionality

## Customization

### Colors
Edit the CSS variables in `css/styles.css` to change the color scheme:
- Light mode colors are in `:root`
- Dark mode colors are in `[data-theme="dark"]`

### Content
All pages use placeholder content that can be easily replaced with your actual content.

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge).

## License

MIT License - See LICENSE file for details.
