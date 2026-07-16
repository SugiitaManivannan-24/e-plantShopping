# e-plantShopping

e-plantShopping is a React-based online plant store called **Paradise Nursery**. It lets users browse a catalog of plants organized by category (air purifying, aromatic, insect repellent, medicinal, and low maintenance), add items to a shopping cart, and manage their cart in real time.

## Features

- Browse plants by category with images, descriptions, and pricing
- Add plants to the shopping cart with a single click
- Increment or decrement item quantities directly from the cart
- Automatically calculated subtotals per item and a running total for the entire cart
- Remove items from the cart
- Continue shopping or proceed to checkout from the cart view
- Live cart item count displayed in the navigation bar

## Tech Stack

- React
- Redux Toolkit (for cart state management)
- Vite (build tool)
- Deployed with GitHub Pages

## Live Demo

[https://sugiitamanivannan-24.github.io/e-plantShopping/](https://sugiitamanivannan-24.github.io/e-plantShopping/)

## Getting Started

Clone the repository and install dependencies:

```bash
git clone https://github.com/SugiitaManivannan-24/e-plantShopping.git
cd e-plantShopping
npm install
npm run dev
```

## Project Structure

- `src/ProductList.jsx` — displays the plant catalog and handles adding items to the cart
- `src/CartItem.jsx` — displays cart contents and handles quantity updates, item removal, and totals
- `src/CartSlice.jsx` — Redux slice managing cart state (add, remove, update quantity)
- `src/store.js` — Redux store configuration
