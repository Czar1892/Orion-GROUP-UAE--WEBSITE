# Orion Corporate Service Provider Website

A professional, static corporate website for Orion Corporate Service Provider, designed for GitHub Pages deployment.

## Project Structure

```
orion-website/
├── index.html                      # Home page
├── style.css                       # Main stylesheet
├── legal-services.html             # Legal Services page
├── corporate-services.html         # Corporate Services page
├── digital-marketing.html          # Digital Marketing page
├── travel-tourism.html             # Travel & Tourism page
├── banking-services.html           # Banking Services page
├── insurance-services.html         # Insurance Services page
├── attestation-services.html       # Attestation Services page
└── README.md                       # This file
```

## Features

- **Pure HTML5 & CSS3** - No frameworks or JavaScript dependencies
- **Fully Responsive** - Optimized for desktop, tablet, and mobile devices
- **Dark Theme** - Black background with red neon constellation accents
- **SEO Optimized** - Semantic HTML, meta tags, Open Graph tags, and Schema.org structured data
- **GEO Targeting** - Optimized for UAE/Dubai local search
- **AEO Ready** - Content optimized for AI search engines
- **Smooth Animations** - Fade-in and slide-up effects throughout
- **Accessibility** - Proper ARIA landmarks and semantic HTML structure

## Deployment to GitHub Pages

### Option 1: Via GitHub Web Interface

1. Create a new repository on GitHub (e.g., `orion-website`)
2. Upload all files from the `orion-website` folder to your repository
3. Go to repository Settings → Pages
4. Under "Source", select "Deploy from a branch"
5. Select the `main` branch and `/ (root)` folder
6. Click Save
7. Your site will be available at `https://[your-username].github.io/orion-website/`

### Option 2: Via Git Command Line

```bash
# Navigate to the orion-website folder
cd orion-website

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Orion Corporate Service Provider website"

# Add remote repository (replace with your GitHub repo URL)
git remote add origin https://github.com/[your-username]/orion-website.git

# Push to GitHub
git branch -M main
git push -u origin main

# Enable GitHub Pages via repository Settings → Pages
```

## Customization

### Update Contact Information

The contact details are currently set to:
- **Phone**: +971 58 530 3871
- **Email**: info@oriongroupuae.com

To update these, search and replace across all HTML files.

### Update Domain

Replace all instances of `https://oriongroupuae.com` in meta tags with your actual domain once deployed.

### Add Logo

If you want to add a logo image:
1. Add your logo file (e.g., `logo.png`) to the root folder
2. Update the Schema.org logo URL in each HTML file
3. Optionally, replace the text logo in the navigation with an image

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- **No external dependencies** - All code is self-contained
- **Minimal CSS** - Optimized for fast loading
- **No JavaScript** - Pure CSS animations for maximum performance
- **Semantic HTML** - Fast parsing and rendering

## SEO Features

- Proper heading hierarchy (H1, H2, H3)
- Meta descriptions on all pages
- Open Graph tags for social sharing
- Schema.org structured data (Organization + Services)
- Geographic targeting for UAE/Dubai
- Descriptive URLs
- Alt text ready (for when images are added)

## License

All rights reserved © 2026 Orion Corporate Service Provider

## Support

For questions or support, contact:
- Email: info@oriongroupuae.com
- Phone: +971 50 584 0771
