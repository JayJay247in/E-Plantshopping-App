# Paradise Nursery E-Plantshop App

Welcome to the Paradise Nursery e-plantshop app! This application allows users to browse and purchase various types of plants, add them to a shopping cart, and manage their orders.

## Features

*   **Landing Page:**
    *   A visually appealing landing page with a background image sets the tone for the application.
    *   A brief paragraph about Paradise Nursery, our mission, and values.
    *   A "Get Started" button that navigates users to the product listing page.
*   **Product Listing Page:**
    *   A catalog of various houseplants categorized for ease of browsing.
    *   Each plant displays its thumbnail image, name, and price.
    *   An "Add to Cart" button for each plant, which:
        *   Increases the shopping cart count when selected.
        *   Disables the button after selection to prevent multiple adds.
        *   Adds the selected plant to the shopping cart.
*   **Header:**
    *   A consistent header displayed on both the product listing and shopping cart pages.
    *   A shopping cart icon that displays the total number of items in the cart.
    *   Navigation links to switch between the product listing page and the shopping cart.
*   **Shopping Cart Page:**
    *   A display of all items added to the shopping cart.
    *   The total number of plants in the cart.
    *   The total cost of all items in the cart.
    *   A "Checkout" button that provides a placeholder message (“Coming Soon”).
    *   A "Continue Shopping" button that navigates users back to the product listing page.
    *   Each plant in the cart displays its thumbnail, name, and unit price.
    *   Increase and decrease buttons for each plant to manage item quantity.
    *   A delete button for removing plants from the cart.

## Technologies Used

*   **React:** A JavaScript library for building user interfaces.
*   **Redux:** A state management library for managing application state.
*   **CSS:** For styling the application.

## Getting Started

Follow these instructions to run the application on your local machine.

### Prerequisites

*   [Node.js](https://nodejs.org/) and npm (or yarn) installed on your system.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/JayJay247in/E-Plantshopping-App.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd E-Plantshopping-App
    ```
3.  **Install dependencies:**
    ```bash
    npm install
    ```
    or
    ```bash
    yarn install
    ```

### Running the App

1.  **Start the development server:**
    ```bash
    npm run dev
    ```
    or
    ```bash
    yarn dev
    ```
2.  **Open the app**: Open your browser and navigate to `http://localhost:5173/` (or whichever port the console shows after you run the command)

## Project Structure

Here’s a brief overview of the main project files:

*   `src/`: Contains all source code
    *   `src/App.jsx`: The main application component.
    *   `src/components/`: Holds various react components.
        * `src/components/AboutUs.jsx`: Component for displaying About Us content.
        * `src/components/CartItem.jsx`: Component for displaying individual cart items.
        * `src/components/ProductList.jsx`: Component for displaying the product list.
    *   `src/store.js`:  Redux store configuration.
    *   `src/CartSlice.js`: Redux slice for managing cart state.
    *   `src/index.css`: Global styles for the project.
    *   `src/*.css`: Component specific CSS files
    * `src/main.jsx`: Entry file to render the App
    
*   `package.json`: Project metadata, dependencies, and scripts.
*   `README.md`: Project documentation

## Additional Notes
This application has been built using React with the power of Redux for managing state and CSS for styling. The goal was to create a functional e-plantshop application that follows best practices and is responsive across different screen sizes.

## Author

Ikechukwu Faithful

Feel free to customize this `README.md` with more information specific to your development process or additional features.