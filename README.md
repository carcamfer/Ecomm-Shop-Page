# EComm Shop

EComm Shop is an e-commerce web application built with Node.js and Express. This application allows users to browse products, add them to a cart, and manage authentication.

## File Structure

The application has a modular directory structure, organized by functionality:

### `public/`
Contains all static files like CSS and images.

- `css/`
  - `main.css`: Defines the global styles of the application.
- `images/`
  - `banner.jpg`: An image used in the application.

### `repositories/`
Contains data access logic.

- `carts.js`: Manages data access for the cart.
- `product.js`: Manages data access for products.
- `repository.js`: Provides general functionalities for data access.
- `users.js`: Manages data access for users.

### `routes/`
Contains the application's routes.

#### `admin/`
Specific routes for administration.

- `auth.js`: Routes related to authentication.
- `middlewares.js`: Middlewares used in admin routes.
- `products.js`: Routes related to product management.
- `validators.js`: Validators for form inputs.

- `cart.js`: Routes related to the shopping cart.
- `products.js`: Routes related to product viewing.

### `views/`
Contains the application's templates.

#### `admin/`
Specific templates for administration.

##### `auth/`
Templates related to authentication.

- `signin.js`: Template for signing in.
- `signup.js`: Template for signing up.

##### `products/`
Templates related to product management.

- `edit.js`: Template for editing a product.
- `index.js`: Template for listing all products.
- `new.js`: Template for creating a new product.

#### `carts/`
Templates related to the shopping cart.

- `show.js`: Template for displaying the shopping cart.

#### `products/`
Templates related to product viewing.

- `index.js`: Template for listing all products.

- `helpers.js`: Helper functions used in templates.
- `layout.js`: Base template used throughout the application.

### `index.js`
Entry point of the application.

## How to Run

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` to install all dependencies.
4. Run `npm start` or `node index.js` to start the application.
5. Open a browser and visit [http://localhost:3000](http://localhost:3000).
