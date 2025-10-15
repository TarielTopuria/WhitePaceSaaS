# WhitePace — SaaS Landing Page

A clean, responsive landing page for a SaaS product named WhitePace. Built with semantic HTML5 and modern CSS. No frameworks, no build steps — just open and run.

## Features
- Responsive layout optimized for desktop and mobile
- Hero section with clear call-to-action
- Product/feature highlight sections (Work management, App integrations, etc.)
- Social proof and brand logos (Google, Microsoft, Slack)
- Pricing visuals and icons
- Favicon included
- Simple structure that’s easy to customize

## Tech Stack
- HTML5
- CSS3 (Flexbox/Grid)
- No JavaScript required
- No build tooling required

## Project Structure
```
WhitePaceSaaS/
├─ index.html        # Main page markup
├─ style.css         # Global styles
└─ img/              # Static assets (logos, icons, illustrations, favicons)
   ├─ apple.png
   ├─ apps.png
   ├─ avater1.png
   ├─ avater2.png
   ├─ avater3.png
   ���─ btn.png
   ├─ data_element.png
   ├─ element.png
   ├─ favicon-icon.png
   ├─ favicon.ico
   ├─ google.png
   ├─ hero-bg.png
   ├─ hero-image.png
   ├─ icon.png
   ├─ logo.png
   ├─ management-image.png
   ├─ microsoft.png
   ├─ price-icon.png
   ├─ slack.png
   └─ work-image.png
```

## Quick Start
- Option 1: Double-click index.html to open it in your browser.
- Option 2: Serve locally with a simple HTTP server for better routing/asset behavior:

Using Python (Windows):
```bash
py -m http.server 5500
# then open http://localhost:5500 in your browser
```
Using Python (generic):
```bash
python -m http.server 5500
```
Using Node (if installed):
```bash
npx http-server -p 5500
```
Using VS Code: install the “Live Server” extension and click “Go Live”.

## Customization
- Content: Edit text and structure in index.html
- Styles: Edit colors, spacing, typography in style.css
- Assets: Replace images in img/ with your own (keep file names or update paths in index.html/style.css)
- Favicon: Replace img/favicon.ico and/or img/favicon-icon.png

## Deployment (GitHub Pages)
1. Push this repository to GitHub
2. In your GitHub repo: Settings → Pages → Build and deployment → Source: Deploy from a branch
3. Select the main branch and root folder (/), then Save
4. After it builds, your site will be available at the Pages URL shown in the settings

Alternative hosting: Netlify, Vercel, or any static host — point it to the repository root.

## Accessibility & Performance Notes
- Use alt attributes on images (update text to be descriptive)
- Keep contrast in mind when adjusting colors
- Optimize images if you replace them with larger assets (e.g., compress PNG/JPG or use WebP)

## License
No license is provided by default. If you intend to open-source this, add a LICENSE file (e.g., MIT, Apache-2.0) and update this section accordingly.

## Acknowledgements
- Brand logos and illustrations in img/ are included as placeholders for demonstration. Ensure you have rights/permissions for any assets you publish.
- Favicon and icon assets are included for convenience; replace them to match your branding as needed.

---
Made for a simple, fast, and portable SaaS landing page workflow. Open, edit, deploy.
