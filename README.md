# DimbaLabs Website

Clean, modern landing page for DimbaLabs — the team building Dimba D1, a diffusion-based language model on Mamba-2.

## Deploy to Netlify

1. Push this folder to a GitHub repo
2. Go to [netlify.com](https://netlify.com) → "Add new site" → "Import an existing project"
3. Connect your GitHub account and select the repo
4. Build settings (should auto-detect):
   - Build command: (leave empty, it's static HTML)
   - Publish directory: `/` (root)
5. Click "Deploy site"

That's it! Netlify will give you a `.netlify.app` URL. You can add a custom domain in site settings.

## Structure

```
.
├── index.html    # Main landing page (single file, all styles inline)
└── README.md     # This file
```

## Customization

- **Colors**: Edit the `:root` CSS variables at the top of the `<style>` block
- **Content**: Edit the HTML directly — all sections are clearly marked with comments
- **Links**: Update GitHub, Twitter, and email links throughout
- **Badge**: Change "Currently Training D1-Base" to whatever status you want

## Fonts

Uses Google Fonts (Inter + Space Grotesk) loaded via CDN.

## Contact

DimbaLabs — Abu Dhabi, UAE
