# Lexaglot Landing Page

This is the landing page for the Lexaglot AI language learning app. It's a modern, responsive static website that showcases the app's features and provides links to download from app stores.

## Setup

1. Install Node.js if you haven't already (https://nodejs.org/)
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```
4. Open http://localhost:3000 in your browser

## Project Structure

- `index.html` - Main landing page content
- `styles.css` - All styling and responsive design rules
- `package.json` - Project configuration and dependencies

## Required Assets

The following image assets need to be added to the project:
- `logo_full.jpg` - Lexaglot logo (already present)
- `app-preview.png` - Screenshot or mockup of the app
- `app-store-badge.png` - Apple App Store download badge
- `play-store-badge.png` - Google Play Store download badge

## Customization

### Colors
The color scheme can be modified in the `:root` section of `styles.css`:
```css
:root {
    --primary-color: #4A90E2;
    --secondary-color: #2C3E50;
    --accent-color: #E74C3C;
    --text-color: #333333;
    --light-gray: #F5F5F5;
    --white: #FFFFFF;
}
```

### Content
Edit the content in `index.html` to modify:
- Hero section text and images
- Feature descriptions
- How It Works steps
- Footer links and information

## Development

The site is built with pure HTML and CSS for maximum performance and simplicity. To make changes:

1. Modify the HTML content in `index.html`
2. Update styles in `styles.css`
3. Test responsiveness using browser developer tools
4. Add or update images in the root directory

## License

MIT License - See LICENSE file for details
