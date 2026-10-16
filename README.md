# New Prakash Radio Service — Website

A responsive static website for GitHub Pages. It includes:
- Animated stylized globe and scroll-driven shop card
- Responsive navigation
- Product category filters and search
- Enquiry dialog
- Optional WhatsApp enquiry (requires shop number configuration)
- CSS-drawn product artwork (no image assets or build tools required)

## Preview locally
Open `index.html` in a modern browser. For a local server, use VS Code Live Server or:
`python -m http.server 8000`
Then visit `http://localhost:8000`.

## Configure WhatsApp
Open `script.js` and replace:
`const SHOP_WHATSAPP = "";`
with your verified WhatsApp number including country code, digits only. Example format: `919876543210`. Do not use that example unless it is your actual shop number.

## Publish with GitHub Pages
1. Create a public GitHub repository.
2. Upload `index.html`, `styles.css`, `script.js`, and `README.md` to the repository root.
3. Go to Settings → Pages.
4. Select Deploy from a branch, branch `main`, folder `/ (root)`, then Save.
5. Wait for the deployment and open the URL GitHub Pages shows.

## Customize
- Edit shop address text in `index.html`.
- Update the Google Maps search URL with your exact verified Google Maps pin.
- Product cards describe categories, not confirmed inventory or prices. Update them to match the shop's actual stock.
- Globe is a decorative animation, not a real geographic map or GPS zoom.
