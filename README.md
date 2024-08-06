# BusyBuy E-Commerce Application

BusyBuy is an E-Commerce application developed using **React.js** and **Firebase**. The app allows users to browse products, manage their shopping carts, and complete purchases. It offers a user-friendly interface with a focus on providing a seamless shopping experience. The project includes a variety of features and functionalities, as outlined below.

## Features

### User Authentication

- **Register Page:** 
  - New users can create an account using their name, email, and password. 
  - Form validation ensures all inputs are correct before submission.

- **Login Page:** 
  - Existing users can sign in using their registered email and password.
  - Incorrect inputs trigger appropriate error messages.

### Product Browsing and Management

- **Home Page:** 
  - Displays a list of products with a search bar to find products by name.
  - Features a filter sidebar to sort products by price and categories.

- **Product Card Component:** 
  - Shows product details, including image, title, price, and buttons for adding/removing items from the cart.

- **Cart Page:** 
  - Displays all items added to the cart, with options to adjust quantities or remove products.
  - Shows total price and includes a "Purchase" button to complete the order.

- **Orders Page:** 
  - Lists all past purchases with details on products and order dates.

### Conditional Rendering

- **Loading State:** 
  - Uses `react-spinners` to indicate data loading.

- **Data Absence:** 
  - Displays appropriate messages when no data is available.

### Notifications and Feedback

- **Toast Messages:** 
  - Provides feedback for user actions and error conditions using `react-toastify`.

### Routing

- **Protected Routes:** 
  - Pages like "My Orders" and "Cart" are accessible only to logged-in users.
  - Invalid URLs lead to a "Page Not Found" message.

## Test Cases

- **Home Page:** 
  - Displays a search bar with placeholder "Search By Name." Unauthenticated users see "Sign In" and "Home" in the navbar.

- **Routes:** 
  - `/signup`, `/signin`, `/cart`, `/myorders`, and `*` for 404.

- **Signup Page:** 
  - Validates inputs for name, email, and password. 
  - Shows error messages for invalid data.

- **Login Page:** 
  - Validates credentials and redirects users upon successful login.

- **Filter Sidebar:** 
  - Allows filtering by price and category.

- **Cart and Order Pages:** 
  - Handle cart management and display order history.
