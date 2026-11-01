# Cashier & Payment Tracker 🛒💳

A lightweight, single-file Point of Sale (POS) and payment tracking web application built with **HTML, Tailwind CSS, and Vanilla JavaScript**. Designed for simplicity and quick testing (runs directly in your browser or online environments like JDoodle).

## Features

- **Quick Catalog & Cart Management:** Add items like Coffee, Sandwiches, and Pastries to an active order with quantity tracking and item removal.
- **Functional Payment Workflows:**
  - **Cash:** Calculates exact change due and updates the cash drawer.
  - **Card (Swipe/Chip):** Simulated secure reader handshake with processing delay and approval state.
  - **NFC (Tap):** Simulated contactless payment tap workflow.
- **Register Drawer Tracking:** Real-time updates for cash, card, and NFC totals.
- **Transaction Ledger:** Logs all completed transactions with timestamps.

## Getting Started

### Option 1: Run Locally
1. Clone the repository or download the `index.html` file.
2. Double-click `index.html` (or open it in any modern web browser like Chrome, Safari, or Firefox).

### Option 2: Test Online
- Drop the contents of `index.html` into an online runner like [JDoodle](https://www.jdoodle.com/) under the HTML/JS tab.

## Live Demo
*(Optional)* If you enable **GitHub Pages** on this repository (under Settings > Pages), paste your live link here:
[View Live App](https://YOUR_USERNAME.github.io/cashier-tracker/)

## Built With
- **HTML5**
- **Tailwind CSS** (via CDN for rapid styling)
- **Vanilla JavaScript** (for interactive cart, modals, and drawer logic)
