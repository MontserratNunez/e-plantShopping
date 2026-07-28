# e-plantShopping

**e-plantShopping**, is a React-based e-commerce web application for **Paradise Nursery**. This application allows users to browse various categories of house plants, add them to a shopping cart, and manage their selections seamlessly using Redux Toolkit.

---

## Repository Information

- **Repository Name:** e-plantShopping
- **Project Name:** Paradise Nursery Shopping Application
- **Tech Stack:** React, Redux Toolkit, React-Redux, JavaScript (ES6+), CSS3

---

## Features

- **Landing Page:** Welcoming interface with an introduction to Paradise Nursery and a call-to-action button to start shopping.
- **Plant Catalog (ProductList):**
  - Categorized display of plants (Air Purifying, Aromatic, Insect Repellent, Medicinal, Low Maintenance).
  - Dynamic "Add to Cart" button that updates to "Added to Cart" and disables upon selection.
  - Navbar showing the total number of items currently in the cart in real-time.
- **Shopping Cart (CartItem):**
  - Displays selected items with thumbnail images, unit prices, and quantities.
  - Options to increment (`+`), decrement (`-`), or delete (`Delete`) items.
  - Calculates subtotal per plant and overall cart total automatically.
  - Functional "Continue Shopping" button to return to the catalog.
  - Placeholder alert for "Checkout".

---

## Redux State Management

The application manages global cart state through a Redux slice (`CartSlice.jsx`) featuring three primary reducers:
1. **`addItem`**: Adds a new plant to the cart or increments its quantity if it already exists.
2. **`removeItem`**: Removes an item completely from the cart array by name.
3. **`updateQuantity`**: Updates the quantity of a specific plant item directly.

---

## Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MontserratNunez/e-plantShopping.git
