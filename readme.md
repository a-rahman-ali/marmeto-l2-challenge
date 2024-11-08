# Marmeto L2 Challenge

## Overview
Marmeto Cart is a simple e-commerce shopping cart web application built with HTML, CSS, and JavaScript. It allows users to view, manage, and checkout items in their cart. The application fetches cart data from an API and supports local storage for persistent cart management.

## Features
- View items in the cart with images, titles, prices, quantities, and subtotals.
- Update item quantities dynamically with input fields.
- Remove items from the cart with confirmation modals.
- Display cart totals (subtotal and total).
- Responsive design for mobile and tablet views.
- Loader animation while fetching cart data.
- Checkout confirmation modal.

## Technologies Used
- HTML5
- CSS3 (with media queries for responsive design)
- JavaScript (ES6+)
- Fetch API for asynchronous data retrieval

## Installation
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/a-rahman-ali/marmeto-cart.git

2. Open the index.html file in your web browser.

## File Structure
    marmeto-cart/
    │
    ├── images                # resources(images) used in the UI
    ├── index.html            # Main HTML file
    ├── styles.css            # Stylesheet for the application
    └── script.js             # JavaScript file for functionality

## Usage

- **Loading Cart Data**: The cart data is fetched from a public API. If no data is found in local storage, it will call the API to load the cart items.
- **Updating Quantities**: Users can change the quantity of each item in the cart, and the subtotal will update automatically.
- **Removing Items**: Clicking the delete button prompts a confirmation modal to remove the item from the cart.
- **Checkout**: A checkout modal is displayed when the "Check Out" button is clicked.

## Styling

- The application uses a combination of Montserrat and Poppins fonts for a modern look.
- Responsive styles ensure a smooth experience across devices.

## Acknowledgements

- Thanks to the creators of the API used for cart data.
- Inspiration from various e-commerce platforms.
- Special thanks to Marmeto for providing this opportunity to learn through this small challenge.
  
For any questions or feedback, feel free to reach out!
