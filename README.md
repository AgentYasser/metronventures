# Metron Ventures

A minimalist portfolio website for Metron Ventures, a holding company for platforms serving the MENA market.

## Recent Updates

**January 2026:** Added MrMelo R&D section to hero, repositioned navigation for improved UX.

### What's New:
- ✅ Navigation moved under headline with modern pill-style buttons
- ✅ New MrMelo Research & Development section showcasing:
  - Target clients (Equity firms, Financial institutions, Entrepreneurs)
  - Six-format delivery system
  - Key metrics (98% efficiency, 6 formats, 14-day delivery)
- ✅ Fully responsive mobile layout
- ✅ All original sections preserved (Ventures, Framework, Tools, Contact)

---

## Features

- Clean, minimalist design
- Fully responsive (mobile-ready)
- Smooth scroll navigation
- Framework methodology visualization
- Venture and tools showcase
- MrMelo R&D capabilities section

---

## Structure

- **Hero Section**: Introduction, navigation, MrMelo R&D showcase
- **Ventures**: Five platforms with progress tracking
  - MrMelo (100%)
  - PlusOne (90%)
  - Sahara (85%)
  - Executive Email (50%)
  - Tanwir (30%)
- **Framework**: The Metron methodology explained
- **Tools**: Eight proprietary systems and templates
- **Contact**: Partnership and collaboration inquiries

---

## Technologies

- Pure HTML/CSS
- No dependencies
- No JavaScript required
- Responsive design with CSS Grid and Flexbox

---

## Deployment

This is a single static HTML file that can be deployed to:

### GitHub Pages
1. Create a new repository on GitHub
2. Upload `index.html` to the repository
3. Go to Settings → Pages
4. Select branch and root folder
5. Save and wait for deployment

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Navigate to this folder
3. Run: `vercel`
4. Follow the prompts
5. Site will be live in seconds

### Netlify
1. Drag and drop this folder into [Netlify Drop](https://app.netlify.com/drop)
2. Site deploys instantly
3. Optional: Connect to Git for continuous deployment

### Any Static Hosting Service
Simply upload `index.html` to your hosting provider. The file is self-contained with no external dependencies.

---

## Local Development

To view locally:

1. Open `index.html` directly in your browser, OR
2. Run a local server:
   ```bash
   # Python 3
   python3 -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (with http-server installed)
   npx http-server
   ```
3. Visit `http://localhost:8000`

---

## Customization

### Colors
Edit CSS variables in the `<style>` section:
```css
:root {
  --black: #1a1a1a;
  --white: #fafafa;
  --gray: #6b6b6b;
  --light-gray: #e5e5e5;
  --accent: #d4a03a;  /* Gold accent color */
  --bg-alt: #f5f5f3;
}
```

### Content
All content can be edited directly in the HTML. Sections are clearly labeled with comments:
- Hero section (lines 803-895)
- Ventures section (lines 897-1026)
- Framework section (lines 1028-1154)
- Tools section (lines 1156-1340)
- Contact section (lines 1342-1382)

---

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## Performance

- Single HTML file: ~60KB
- No external requests
- Instant load time
- No JavaScript = No JS performance issues
- Perfect Lighthouse scores possible

---

## License

© 2026 Metron Ventures · Dubai, UAE

---

## Contact

For inquiries: [info@metronventures.com](mailto:info@metronventures.com)

Website: [metronventures.com](#) (update with actual domain)

MrMelo Consulting: [mrmelo.com](https://www.mrmelo.com)

