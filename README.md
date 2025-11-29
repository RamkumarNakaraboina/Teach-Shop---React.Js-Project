Tech-Shop React Project
Introduction

Tech-Shop is a complete e-commerce front-end application built using React.js (Vite).
The project includes product listing, product details, filtering, sorting, cart updates, and a fully responsive design.
It is built to demonstrate strong React fundamentals, Redux Toolkit state management, and clean UI development.

1. Pages and Screens
1.1 Home Page
- Hero banner slider
- Featured products section
- Top categories
- Navigation to product details
1.2 All Products Page
- Grid display of all products
- Sorting: Latest, Featured, Price Low–High, Price High–Low
- Filtering: Brand, Category, Type
1.3 Product Details Page
- Multiple preview images
- Product name, description, ratings
- Pricing with discount
- Add to Cart button
- Related products suggestion
1.4 Cart Page
- Add or remove items
- Update quantity dynamically
- Automatic total price update
- Order summary including:

Original price

Discount

Delivery charges

Final payable amount

2. Code Overview
2.1 Project Folder Structure
src/
│
├── assets/
│
├── component/
│   ├── Header.jsx
│   ├── Footer.jsx
│   ├── Slider.jsx
│   ├── Advantages.jsx
│   ├── ProductCard.jsx
│   └── ...
│
├── pages/
│   ├── Home.jsx
│   ├── AllProduct.jsx
│   ├── ProductDetails.jsx
│   ├── Cart.jsx
│   └── ...
│
├── reduxToolkit-store/
│   ├── productSlice.js
│   └── store.js
│
├── myContext/
│   └── MyContext.jsx
│
├── App.jsx
├── main.jsx
└── index.css

2.2 Redux Toolkit (productSlice.js)
Handles the following:

Adding items to cart

Removing items

Updating item quantity

Managing total price and discounts

Storing product data globally

2.3 Context API (MyContext.jsx)
Used for UI-level shared utilities and helper functions
2.4 Routing (App.jsx)
Uses React Router DOM to handle navigation:

/ (Home)

/allproducts

/product/:id

/cart

3. Running the Project
Step 1: Install Dependencies
npm install

Step 2: Start the Development Server
npm run dev

Step 3: Open in Browser
http://localhost:5173/

4. How the Application Works
4.1 User Flow
- User starts on the Home page
- Browses featured products and categories
- Navigates to All Products to filter or sort items
- Opens Product Details page
- Adds items to cart
- Goes to Cart page to update quantity or remove items
4.2 Cart Logic
Automatically calculates:

Product subtotal

Discounts

Delivery charges

Final payable amount

4.3 UI Structure
- Fully responsive layout
- Clean spacing, grid structure, and typography
- Reusable components throughout the application
Conclusion

Tech-Shop is a complete front-end e-commerce project demonstrating:

- Component-based architecture
- Redux Toolkit global state management
- Routing and navigation flow
- Clean folder structure
- Responsive and modern UI design

It is an excellent demonstration of practical React.js development skills suitable for production-level applications.
