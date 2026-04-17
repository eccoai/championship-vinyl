# Chicago Concert Guide 2026 for Joel

A curated concert guide featuring your favorite artists coming to Chicago in 2026, built as a love letter to music discovery in the spirit of High Fidelity.

## Features

✨ **Interactive Concert Cards**
- Add-to-calendar buttons that generate .ics files
- Collapsible Apple Music artist embeds
- Responsive design with dark/light theme toggle

🎵 **Discover Page**
- Hand-curated similar artist recommendations
- Grouped by taste clusters (indie-with-harmonies, singer-songwriter-folk, jam-band, british-alt)
- Written in the voice of Rob Gordon from High Fidelity

🥚 **Easter Eggs**
- Konami code unlocks secret blue theme
- High Fidelity quotes logged to console on page load
- Top 5 shows modal (click "2026" five times) with drag-and-drop ranking
- ASCII boombox (Say Anything reference) on discover page

📱 **GitHub Pages Ready**
- No build step required
- Vanilla HTML/CSS/JS only
- Optimized for sharing with Open Graph meta tags

## GitHub Pages Setup

Follow these exact steps to enable GitHub Pages for this repository:

### Step 1: Push to GitHub
```bash
git add .
git commit -m "Initial concert guide setup"
git push origin main
```

### Step 2: Enable GitHub Pages
1. Go to your repository on GitHub.com
2. Click the **Settings** tab (next to "Insights")
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Under **Branch**, select **main**
6. Under **Folder**, select **/ (root)**
7. Click **Save**

### Step 3: Access Your Site
- Your site will be available at: `https://[username].github.io/championship-vinyl/`
- GitHub will show you the exact URL in the Pages settings
- It may take a few minutes for the site to become available

### Step 4: Update Open Graph Images (Optional)
- Replace the placeholder `og:image` URLs in both `index.html` and `discover.html`
- Update the `og:url` to match your actual GitHub Pages URL

## Design System

**Typography:** Playfair Display (headings) + DM Sans (body)  
**Colors:** Warm amber primary (#e8880f) + teal accent (#3fa8af)  
**Theme:** Dark/light toggle with system preference detection  
**Feel:** Editorial zine meets concert database

## Browser Support

- Modern browsers with CSS custom properties support
- iOS Safari (for Apple Calendar integration)
- Works without JavaScript (graceful degradation)

---

*"The making of a great compilation tape, like breaking up, is hard to do and takes ages longer than it might seem."*