# Tavola Cooking Website

A beautiful, responsive static HTML website for recipes and cooking tips.

## Features

- 📱 Fully responsive design
- 🎨 Modern gradient UI with smooth animations
- 👨‍🍳 Recipe showcase with cards
- 📧 Contact form
- ⚡ Fast performance (static HTML)

## Local Development

Simply open `index.html` in your browser:

```bash
# Option 1: Double-click index.html in file explorer
# Option 2: Use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

Or with Node.js:
```bash
npx http-server
```

## Deployment

### GitHub Pages

1. Ensure repository is set to public
2. Go to Settings → Pages
3. Select `main` branch as source
4. Site will be available at `https://username.github.io/Tavola-cooking-website`

### Vercel

1. Connect your GitHub repository to Vercel
2. Click "Deploy" - Vercel automatically detects static HTML
3. Site will be live in seconds at a Vercel URL

## File Structure

```
├── index.html       # Main page
├── styles.css       # Styling
├── script.js        # JavaScript functionality
├── vercel.json      # Vercel configuration
├── .gitignore       # Git ignore rules
└── README.md        # This file
```

## Customization

- **Colors**: Edit `:root` variables in `styles.css`
- **Recipes**: Add more recipe cards in the recipes section
- **Content**: Update text in `index.html`

## License

© 2026 Tavola. All rights reserved.