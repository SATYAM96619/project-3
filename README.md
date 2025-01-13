# PROJECT-3

## E-Commerce Product Page - README

### Overview

This project implements a simple e-commerce product page where users can browse products, add them to a cart, and view the total price dynamically. The page provides an interactive shopping experience with a clean and responsive design, ensuring compatibility across devices.

### Features

- **Product Catalog**: Displays a grid of products with images, names, and prices.
- **Add to Cart**: Allows users to add products to their shopping cart.
- **Cart Functionality**:
  - Displays all added items with their quantities and prices.
  - Calculates and displays the total price dynamically.
  - Option to clear the cart.
- **Responsive Design**: Adapts the layout for different screen sizes using CSS Grid and Flexbox.
- **Hover Effects**: Provides visual feedback when interacting with products.

### Technologies Used

- **HTML**: For structuring the page.
- **CSS**: For styling and layout.
- **JavaScript**: For interactivity and dynamic content updates.

### How It Works

#### Product Display:

- Each product is represented as a card with an image, name, price, and "Add to Cart" button.
- Products are defined in HTML with `data-id`, `data-name`, and `data-price` attributes for easy identification.

#### Adding Products to the Cart:

- When the "Add to Cart" button is clicked, the product details (ID, name, price) are retrieved.
- The cart is updated:
  - If the product is already in the cart, its quantity increases.
  - If it is a new product, it is added with an initial quantity of 1.

#### Cart Display:

- The cart displays a list of all added products with their quantities and individual total prices.
- The total price of all items is calculated and displayed.

#### Clearing the Cart:

- Clicking the "Clear Cart" button empties the cart and resets the total price.

### Functions

1. **Add to Cart**:

   - Retrieves product details and updates the cart.
   - If the product exists, increments its quantity; otherwise, adds a new entry.

2. **Clear Cart**:

   - Resets the cart and clears all displayed items.

3. **Update Cart**:

   - Dynamically updates the cart display and recalculates the total price.

### Example Usage

#### Adding a Product:

1. A user clicks "Add to Cart" for Product 1.
2. The cart updates to include Product 1 with a quantity of 1 and its price.

#### Clearing the Cart:

1. The user clicks the "Clear Cart" button.
2. The cart is emptied, and the total price is reset to \$0.00.

### Requirements

- A modern web browser (e.g., Chrome, Firefox, Safari).
- No external libraries are required; all functionality is implemented using native HTML, CSS, and JavaScript.

### How to Run

1. Save the code to a file, for example, `index.html`.
2. Open the file in any modern web browser.

### Conclusion

This e-commerce product page is a basic yet functional implementation of an online shopping cart system. It demonstrates the use of HTML, CSS, and JavaScript to create a responsive and interactive user interface. The project can be extended to include features like:

- Product search and filtering.
- User authentication.
- Backend integration for persistent cart storage.

This project is a great starting point for learning front-end web development and understanding how dynamic web applications work.

