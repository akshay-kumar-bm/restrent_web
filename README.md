# Restaurant and Hotel Website (Next.js)

A front-end-only Next.js website with a restaurant landing page and a hotel page, built with Tailwind CSS and Lucide icons.

## What it does
- `/` : Indian restaurant site with hero, food menu (name, description, price in INR, category, image), chefs, reviews, FAQ accordion, about and contact sections.
- `/hotel` : hotel page with rooms (price, capacity, amenities), and booking/guest-related sections driven by static data in the component.

All content is hard-coded in the page components; there is no backend or database.

## Tech stack
Next.js 15.1.7 (App Router), React 19, Tailwind CSS 3, lucide-react, ESLint.

## Structure
```
src/app/page.js         # restaurant page
src/app/hotel/page.js   # hotel page
src/app/layout.js, globals.css
public/images/          # food and restaurant images
```

## Run
```bash
npm install
npm run dev     # http://localhost:3000
npm run build && npm start
```

## Limitations / future work
- Static data only; no booking, ordering or contact form backend.
- Hotel images referenced (`/images/deluxe-king.jpg`, etc.) are not in `public/images`; some food images hotlink external URLs.
- README was still the create-next-app boilerplate; package name is `frontend`.
