# V-Shop

A modern e-commerce storefront built with React. Browse products by category, add items to your cart, and view order totals — all in a responsive single-page application.

## Features

- **Home** — Hero banner with trending products and quick category filters
- **Shop** — Full product catalog with category-based filtering
- **Cart** — Add and remove items with live cart count and total price
- **Contact** — Contact page for customer inquiries
- **Navigation** — Persistent navbar with search bar and cart badge

## Tech Stack

- [React](https://react.dev/) 19
- [Vite](https://vitejs.dev/) — fast dev server and build tool
- [Redux Toolkit](https://redux-toolkit.js.org/) — cart state management
- [React Router](https://reactrouter.com/) — client-side routing
- [React Icons](https://react-icons.github.io/react-icons/) — UI icons

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- npm

### Installation

```bash
git clone <repository-url>
cd Ecommerce
npm install
```

### Development

Start the local dev server:

```bash
npm run dev
```

Open the URL shown in the terminal (typically `http://localhost:5173`).

### Build

Create a production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

### Lint

Run ESLint:

```bash
npm run lint
```

## Available Scripts

| Script    | Description              |
| --------- | ------------------------ |
| `npm run dev`     | Start development server |
| `npm run build`   | Build for production     |
| `npm run preview` | Preview production build |
| `npm run lint`    | Run ESLint               |

## Project Structure

```
Ecommerce/
├── src/
│   ├── assets/          # Images and static assets
│   ├── components/      # Reusable UI components
│   │   ├── CartCard.jsx/
│   │   ├── Footer/
│   │   ├── nav/
│   │   └── Product/
│   ├── pages/           # Route-level page components
│   │   ├── cart/
│   │   ├── contact/
│   │   ├── home/
│   │   └── shop/
│   ├── redux/           # Redux store and cart slice
│   ├── App.jsx          # Root component and routes
│   ├── Category.js      # Product categories
│   ├── dummydata.js     # Sample product data
│   └── main.jsx         # Application entry point
├── index.html
├── package.json
└── vite.config.js
```

## Routes

| Path       | Page    |
| ---------- | ------- |
| `/`        | Home    |
| `/shop`    | Shop    |
| `/cart`    | Cart    |
| `/contact` | Contact |

## License

This project is private.
