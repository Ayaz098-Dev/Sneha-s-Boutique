# Sneha's Boutique

A responsive boutique storefront built with React, Vite and Tailwind CSS.

## Features
- Premium cream, rose and wine colour palette with responsive layout
- Responsive navigation with collection dropdown and mobile menu
- Product cards with product features, prices, quantity controls and hover states
- Category filters and live product search
- Shopping bag with quantity edits, item removal and subtotal calculation
- WhatsApp order enquiry links and direct call links
- Login / sign-up demo modal using browser localStorage
- Boutique story, address, Google Maps directions and contact section
- Component-based project structure and accessible labels

## Requirements
- Node.js 18 or newer
- npm

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite.

## Production build
```bash
npm run build
npm run preview
```

## Project structure
```text
src/
  components/
    AuthModal.jsx
    CartDrawer.jsx
    Header.jsx
    ProductCard.jsx
  data/
    products.js
  App.jsx
  main.jsx
  styles.css
```

## Important before going live
1. Product names, prices and stock are demo catalogue content. Replace them with confirmed boutique inventory.
2. Product photography uses remote Unsplash image URLs and requires an internet connection. Replace with licensed product photos for a commercial launch.
3. The login/sign-up flow is a front-end demo stored in localStorage. It is not secure authentication and must be replaced with a backend/auth provider before collecting real customer accounts.
4. The cart is session-only and does not process payments. WhatsApp links create an enquiry message; the shop confirms availability, delivery and final price.
5. Confirm the address, phone number and opening hours before launch.
