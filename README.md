# San Marcos Jr. Rattlers Cheer Camp 2026 — 20% Off Landing Page

Static, mobile-first co-branded landing page for the **San Marcos Jr. Rattlers Cheer Camp 2026**, sponsored by **CustomPrint.it**. Visitors scan a QR code on sponsored shirts, land here, and submit a form to claim **20% off** their first custom order.

## Shape
- Single self-contained `index.html` — no build step, no framework.
- Logos: `customprint-logo.png` (sponsor) and `jr-rattlers-logo.png` (camp), shown in the co-brand header and footer.
- Conversion form embedded via the CustomPrint.it (LeadConnector) iframe + `form_embed.js`. This iframe is the entire conversion mechanism — leave it intact.
- Fonts via Google Fonts. Confetti / scroll-reveal / sparkle animations are inline JS/CSS and respect `prefers-reduced-motion`.

## Local preview
```
npx serve .
```
Then open the printed `http://localhost:...` URL.

## Deploy
Static site on Vercel (root directory `./`, no build command).
