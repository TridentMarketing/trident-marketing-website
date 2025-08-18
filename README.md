# Trident Marketing Website

A modern, responsive single-page website for Trident Marketing, optimized for Vercel deployment.

## Features

- **Modern Design**: Clean, professional layout with gradient backgrounds and smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Fast Loading**: Minimal dependencies, optimized for performance
- **SEO Friendly**: Proper meta tags and semantic HTML structure
- **Accessible**: WCAG compliant with proper contrast ratios and keyboard navigation

## Sections

1. **Header**: Fixed navigation with contact information and social links
2. **Hero**: Eye-catching call-to-action section
3. **About**: Company overview with visual gallery
4. **Services**: Four core service areas (Marketing, Sales, Technology, People)
5. **Vision**: Company vision and values
6. **Team**: Leadership team showcase
7. **Contact**: Location, contact details, and map placeholder
8. **Footer**: Copyright information

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Inter)
- Intersection Observer API for animations

## Deployment

### Deploy to GitHub Pages

1. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Update website"
   git push origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your GitHub repository
   - Click "Settings" tab
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

3. **Your site will be available at**:
   `https://YOUR_USERNAME.github.io/REPOSITORY_NAME/`

### Alternative: Deploy to Vercel

1. **Install Vercel CLI** (optional):
   ```bash
   npm i -g vercel
   ```

2. **Deploy via Vercel Dashboard**:
   - Go to [vercel.com](https://vercel.com)
   - Create a new project
   - Import your GitHub repository or upload files
   - Vercel will automatically detect the static site configuration

3. **Deploy via CLI**:
   ```bash
   vercel
   ```

## Customization

### Colors
The site uses a purple gradient theme. To change colors, update these CSS variables in the `<style>` section:

```css
/* Primary gradient */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Secondary colors */
color: #333; /* Text color */
background: #f8f9fa; /* Light background */
```

### Content
Update the content in the HTML file to match your business information:

- Company name and tagline
- Contact information
- Service descriptions
- Team member details
- Address and business hours

### Images
Replace the placeholder gallery items with actual company images by updating the `.gallery-item` elements in the About section.

## Performance

The site is optimized for performance with:

- Minimal external dependencies
- Optimized CSS and JavaScript
- Efficient animations using Intersection Observer
- Responsive images and layouts
- Fast loading times

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This project is created for Trident Marketing. All rights reserved.

## Contact

For questions about this website, contact:
- Email: info@tridentmarketing.com
- Phone: (910) 693-4000
- Address: 1930 North Poplar Street, Southern Pines, NC 28387
