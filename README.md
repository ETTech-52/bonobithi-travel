# Bonobithi — Bangladesh Travel Discovery

A responsive bilingual (English/Bengali) React website concept with a premium editorial travel-magazine visual direction.

## Run locally
Requires Node.js 18+.

```bash
npm install
npm run dev
```

Open the Vite URL printed in the terminal (usually http://localhost:5173).

## Production build
```bash
npm run build
npm run preview
```

## Pages
- `/` — editorial homepage
- `/explore` and `/places` — searchable destination catalogue with type/region filters and sorting
- `/place/:id` — destination details, highlights, suggested itinerary, practical notes, save and add-to-trip actions
- `/plan` — trip planner with selected destinations, dates, traveller count, indicative budget, trip duration, notes and copyable summary
- `/culture` — food, products and craft discovery with category/search filters and saved items
- `/journal` and `/journal/:id` — travel guides and article pages
- `/saved` — saved destinations and culture items
- `/about`, `/contact`, `/privacy`, `/terms` — supporting pages

## Working in this prototype
- Responsive navigation
- English/Bengali interface toggle (some editorial and guide copy remains English)
- Destination search, filters, region filtering and sorting
- Save/unsave places and culture cards
- Add/remove destinations from a trip
- Local browser persistence using `localStorage`
- Trip length and indicative budget calculations
- Date, traveller count and notes in planner
- Copy trip summary to clipboard (browser permissions permitting)
- Contact/newsletter forms show demo confirmations only
- Destination detail and related destination navigation

## Not connected / production work required
- Real booking, payment, hotel, transport or ticket inventory
- User registration, accounts and cloud sync
- Backend/CMS/admin dashboard for editing destinations, images, guides and products
- Contact form delivery and newsletter provider integration
- Live maps, route planning, weather, opening hours and availability
- Verified supplier/guide listings, moderation and reviews
- Analytics, SEO metadata per route, accessibility audit, automated tests and production monitoring

## Photography and content
Images currently use remote Unsplash image URLs for design prototyping. Replace them with licensed and verified Bangladesh-specific images before commercial launch. Destination budgets, seasonal suggestions and descriptions are editorial starting points, not guaranteed quotes or live travel advice; verify them before travelling.

## Deployment
Build with `npm run build`, then deploy the generated `dist/` directory to Vercel, Netlify, Cloudflare Pages or another static host. For SPA routing, configure the host to rewrite unknown paths to `/index.html`.
