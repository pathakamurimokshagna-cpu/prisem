# Prisem

Prisem is a lightweight, responsive web-based auction and marketplace platform built with clean vanilla HTML, CSS, and JavaScript.

## Features

- **Live Bidding Experience**: Place standard bids or use quick increment (+5) bidding on active auctions.
- **Search & Filtering**: Search auction listings in real-time, filter by category, and sort by price or name.
- **Role Switching**: Switch seamlessly between bidder accounts (Alice, Bob) and the Admin account.
- **Shopping Cart & Checkout**: Won auctions automatically populate the user's cart for simulated checkout and shipping order creation.
- **Item Reviews & Ratings**: Submit star ratings and customer reviews on won items.
- **Admin Dashboard**: Manage inventory, add new auction items, end bidding sessions, and mark placed orders as shipped.
- **Responsive Layout**: Clean card and grid layouts styled for both mobile screens and desktop browsers.

## Project Structure

```text
prisem/
├── index.html     # Application entrypoint and shell
├── style.css      # Custom styling and responsive design
├── script.js     # State management, bidding logic, and UI rendering
└── README.md      # Project overview and instructions
```

## Running the Application Locally

Since Prisem uses standard web technologies with no build steps or dependencies, you can run it immediately:

1. **Directly in Browser**: Double-click `index.html` to open it in your default web browser.
2. **Via Local HTTP Server** (recommended):
   ```bash
   # Python 3
   python -m http.server 8000

   # Or Node.js
   npx serve .
   ```
   Then navigate to `http://localhost:8000`.

## Publishing to GitHub

To push this repository to your GitHub account:

1. Create a new empty repository named `prisem` on [GitHub](https://github.com/new).
2. Run the following commands in the project folder:
   ```bash
   git remote add origin https://github.com/<your-username>/prisem.git
   git branch -M main
   git push -u origin main
   ```
