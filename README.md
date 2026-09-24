# TMPL MVP

Working front-end MVP for tmpl.es.

## Included
- Responsive homepage
- No registration/account flow
- TMPL Builder: company, logo upload, 1–6 colors, palettes, fonts, live preview
- $99 order summary
- Checkout placeholder ready for Stripe

## Run locally
npm install
npm run dev

## Vercel
Import the project/repository into Vercel. No environment variables are needed yet.

## Next
1. Connect a 3–5 layout PowerPoint test master
2. Build PowerPoint generation + validation
3. Add Stripe Checkout
4. Store order data
5. Download + transactional email

## v3 preview fixes
- Uploaded logo is shown on all three preview slides.
- Dark preview slide adds a light logo backing so dark logos remain visible.
- PowerPoint-safe font stacks prevent Aptos/Calibri from falling back to browser-default Times New Roman.
- Aptos headings prefer Aptos Display when available.
- Live preview sizing is constrained so all three 16:9 previews fit the builder better.
