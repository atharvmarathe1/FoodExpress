# FoodExpress
This project, **FoodExpress**, is a Swiggy-style food delivery web application built using **HTML, CSS, and vanilla JavaScript**. It demonstrates core front-end development skills through a modern dark-themed UI, responsive restaurant listings, interactive menu pages, and a dynamic cart system with `localStorage` support 
## FoodExpress – Swiggy-Style Food Delivery Clone

FoodExpress is a **front-end only** Swiggy-style food delivery demo built with **HTML, CSS and vanilla JavaScript**.  
It focuses on layout, UI polish, and simple client-side logic to showcase web development skills.

### Features

- **Modern dark UI**
  - Radial-gradient background and elevated `main` container on every page.
  - Consistent typography and orange/yellow accent color system.
  - Subtle hover and entrance animations on cards and sections.

- **Landing page (`index.html`)**
  - Sticky header with navigation (`Home`, `Offers`, `Help`) and login modal.
  - Hero section with high-quality food imagery and CTA.
  - Location bar with **geolocation-based “Detect location”** button (uses the browser Geolocation API).
  - Search bar that **filters restaurants live** by name or cuisine.
  - “Explore restaurants” button smoothly scrolls to the restaurant list.

- **Restaurant listing**
  - Responsive grid of restaurant cards with real food photos.
  - Each card links into a dedicated restaurant menu page.

- **Restaurant menu + cart (`restaurant.html`)**
  - Restaurant header with rating, ETA, and cost for two.
  - Menu items with name, description, price, Veg/Non‑veg badge.
  - **Add to cart** buttons implemented with vanilla JS.
  - Live cart panel summarizing items, quantities and total.
  - On “Proceed to billing”, cart is persisted to **`localStorage`** and the user is redirected to billing.

- **Billing and payment (`billing.html`)**
  - Reads order data from `localStorage` and renders an order summary.
  - Calculates item total, adds a flat delivery fee, and shows grand total.
  - Payment methods: UPI, Card, Wallet, Cash on Delivery (radio buttons).
  - “Place order” validates that a payment method is selected.
  - Shows a **success message** plus a **modal popup** explaining this is only a demo and no real payment happens.

- **Offers page (`offers.html`)**
  - Modern offers grid with bank, UPI and wallet offers.
  - Hover-lifted cards to emphasize interactivity.

- **Help & AI chatbot (`help.html`)**
  - Two clear options: **Call helpline** or **Chat with SupportBuddy (AI-style chatbot)**.
  - Chat UI component with bot and user bubbles.
  - Chatbot summarizes the user’s text and guides them to call the helpline with a clear summary.

### Tech & concepts demonstrated

- Semantic HTML5 layout: `header`, `main`, `section`, `footer`, and accessible form controls.
- **Vanilla JavaScript**:
  - DOM querying and event handling (`addEventListener`).
  - Dynamic rendering of cart items and totals.
  - Basic state management in memory plus persistence with `localStorage`.
  - Smooth scrolling, search filtering, and simple modal logic.
- **CSS skills**:
  - Responsive layouts with Flexbox and CSS Grid.
  - Custom animations (`@keyframes fadeUp`) and hover transitions.
  - Theming with gradients, shadows, and reusable utility styles.

### How to run

1. Clone or download this folder.
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox).
3. Recommended: use a simple static server (e.g. VS Code Live Server or `npx serve .`) so all pages behave like a small web app.

### Possible future improvements

- Add multiple real restaurants with separate menu pages.
- Add routing with a client-side framework (React/Vue) while keeping the same design.
- Connect to a simple backend API for real menu and order data.
- Add authentication flow and persistent user profiles.

This project is intentionally framework-free to highlight **core front-end fundamentals** and UI design skills without relying on heavy tooling.

