# 🚀 E-commerce Follow-Along Project

Welcome to the **E-commerce Follow-Along** project! This is a fully functional **full-stack e-commerce website** that incorporates modern **frontend and backend technologies**. The aim is to build a smooth **online shopping experience** with features like **product listings, authentication, cart management, and secure payments**.

---
## 🎯 Key Features

- **🛍️ Product Listings** – Browse a wide range of products with detailed descriptions.
- **🔎 Search & Filters** – Quickly find what you need using an intuitive search and filtering system.
- **🛒 Shopping Cart** – Easily add, remove, and manage products in the cart.
- **💳 Secure Payments** – Integrated payment gateway for seamless transactions.
- **🔐 User Authentication** – Sign up, log in, and manage user accounts securely.
- **🚚 Order Tracking** – Track orders in real-time with status updates.

---
## 📌 Project Milestones

### ✅ Milestone 1: Project Initialization
- 📂 Set up a **GitHub repository** named `Ecommerce-Follow-Along`.
- 📝 Created an **initial README.md**.
- 🏗️ Established a **basic project structure** and made the first commit.
 
### Milestone 2: Frontend & Backend Initialization  
*✅ Goals:*  
1. *Project Folder Structure:* Organized files into separate frontend and backend directories.  
2. *React Frontend Setup:* Initialized a React application for building the user interface.  
3. *Node.js Backend Setup:* Set up a simple Node.js server for API integration in future milestones.  
4. *Tailwind CSS Configuration:* Integrated and configured Tailwind CSS for modern, responsive styling.  
5. *Login Page Development:* Created a login page with functionality and styling.  

---

### Milestone 3: Backend Structure & Server Setup  
*✅ Goals:*  
1. *Backend Folder Structure:* Created a structured hierarchy for organizing routes, controllers, models, and middleware.  
2. *Server Setup:*  
   - Used Node.js and Express.js to create a backend server.  
   - Configured the server to listen on a designated port.  
3. *Database Connection:*  
   - Integrated MongoDB for efficient data storage.  
   - Confirmed the connection between the server and MongoDB.  
4. *Error Handling:*  
   - Provided clear error messages for better debugging and user feedback.  

---

### Milestone 4: Creating User Model and Controller  
*✅ Goals:*  
1. *User Model:* Defined the structure of user data with attributes like name, email, password, and profile picture.  
2. *User Controller:* Handled user-related actions such as registration and data retrieval.  
3. *Multer Integration:* Enabled file uploads for storing user profile pictures.  
4. *API Routes:* Created endpoints for user creation and fetching user details.  
5. *README Update:* Documented progress and updated repository.  

---

### Milestone 5: Sign-Up Page & Form Validation  
*✅ Goals:*  
1. *Sign-Up Page UI:* Designed a clean and user-friendly sign-up form with fields for name, email, and password.  
2. *Form Validation:*  
   - Ensured the email follows the correct format.  
   - Implemented password security criteria (minimum length, special characters, etc.).  
3. *User Registration Flow:* Integrated frontend form submission with the backend API.  
4. *Error Handling:* Displayed validation errors to users in real-time.  
5. *README Update:* Documented progress and updated repository.  

---

### Milestone 6: Secure User Registration  
*✅ Goals:*  
1. *Password Encryption:*  
   - Used bcrypt to hash passwords before storing them in the database.  
   - Ensured no plaintext passwords are stored.  
2. *Secure Data Storage:*  
   - Stored the user's encrypted password along with other necessary details in MongoDB.  
3. *Updated API Endpoints:*  
   - Modified the user registration endpoint to handle password hashing securely.  
4. *Security Compliance:*  
   - Followed best practices for protecting user credentials.  
5. *README Update:*  
   - Documented progress for Milestone 6 and updated the repository.  

---

### Milestone 7: User Login & Authentication  
*✅ Goals:*  
1. *Login Endpoint:* Created a backend endpoint for user login and verified user credentials.  
2. *Password Validation:* Utilized bcrypt for secure password comparison.  
3. *Authentication Flow:* Authenticated users based on matching hashed passwords.  
4. *Security Considerations:* Ensured secure handling of user credentials.  
5. *README Update:* Updated with details about the user login functionality.  

---

### Milestone 8: Product Card Component & Homepage Layout  
*✅ Goals:*  
1. *Card Component Creation:* Designed a reusable card component for displaying product details.  
2. *Homepage Layout Design:* Created a responsive grid layout for displaying multiple product cards.  
3. *Dynamic Data Display:* Implemented dynamic rendering of product cards using mapping.  
4. *Consistency & Responsiveness:* Ensured consistent styling and responsive design.  
5. *README Update:* Documented progress and learning outcomes for Milestone 8.  

---

### Milestone 9: Product Input Form  
*✅ Goals:*  
1. *Product Form Creation:*  
   - Designed a form for inputting product details such as name, description, price, and category.  
   - Included fields for uploading multiple product images.  
2. *Image Upload Functionality:*  
   - Implemented file input to accept multiple images.  
   - Configured frontend to preview selected images before submission.  
3. *Form Validation & Error Handling:*  
   - Ensured all required fields are filled out.  
   - Displayed validation errors for incomplete or incorrect inputs.  
4. *Integration with Backend:*  
   - Connected the form to the backend API for product creation.  
   - Stored product details and images in MongoDB.  
5. *User Experience Enhancements:*  
   - Provided a clean and user-friendly UI for the product input form.  
   - Added real-time feedback for image uploads and form validation.  
6. *README Update:*  
   - Documented the progress and learning outcomes for Milestone 9.  
   - Updated the repository with details about the product input form.  

---

### Milestone 10: Product Schema & Endpoint Creation  
*✅ Goals:*  
1. *Product Schema Creation:*  
   - Designed a Mongoose schema for product details including name, description, price, and image URL.  
   - Ensured each field has proper validation (e.g., required fields, correct data types).  
2. *Endpoint Creation:*  
   - Built a POST endpoint to receive product data.  
   - Validated and saved the product details to MongoDB.  
3. *Why Validation?*  
   - Ensures that only valid data is saved in the database, maintaining data integrity and preventing errors.  
4. *Security Enhancements:*  
   - Implemented additional validation and data integrity measures to ensure accurate and secure data storage.  
5. *Next Steps (Optional):*  
   - Experiment with adding features such as admin access control to allow only admins to upload products or creating user profiles with roles for managing the shop.  

---
### Milestone 11: Dynamic Homepage with Product Data  

✅ *Goals:*  

#### ⿡ Backend - Fetch All Products  
- Created an API endpoint to retrieve all product data stored in MongoDB.  
- Used *Express.js* and *Mongoose* to fetch and send product details as JSON.  

#### ⿢ Frontend - Fetch & Display Data Dynamically  
- Created a function to *fetch product data* from the backend.  
- Passed the received data to the existing *Product Card Component*.  
- Used .map() to dynamically *render each product* on the homepage.  

#### ⿣ Why This Matters?  
- Enables *dynamic content loading* from the database instead of hardcoded values.  
- Improves *scalability and flexibility* as new products are added.  

#### ⿤ Submission Steps  
- ✅ Pushed the updated code to the *GitHub repository*.  
- ✅ Updated the *README.md* file with Milestone 11 details.  
- ✅ Shared the repository link for submission.

---

### Milestone 12: My Products Page - Filtering by User Email  

✅ *Goals:*  

#### 1️⃣ Backend - Fetch Products by User Email  
- Created an API endpoint to *retrieve only the products* added by the logged-in user.  
- Used *Express.js* and *Mongoose* to *filter products based on the user's email* stored in MongoDB.  
- Ensured *secure and efficient querying* to fetch only relevant data.  

#### 2️⃣ Frontend - Fetch & Display User-Specific Products  
- Created a function to *fetch products linked to the logged-in user's email*.  
- Passed the received data to the existing *Product Card Component*.  
- Used .map() to dynamically *render only the user's products* on the *"My Products"* page.  

#### 3️⃣ Why This Matters?  
- Enables *personalized product listings* based on the logged-in user's email.  
- Improves *data filtering skills*, ensuring only relevant data is sent to the client.  
- Enhances user experience by displaying only their *added products* instead of all products.

---  


### Milestone 13: Complete Project Documentation & Code Refactoring  
✅ Goals:  
1. Code Refactoring:  
   - Improved code structure, ensuring modular and maintainable components.  
   - Removed unnecessary files and optimized logic.  
2. Comprehensive README Update:  
   - Documented all features and milestones clearly.  
   - Added setup instructions and usage details for new contributors.  
3. Bug Fixes:  
   - Fixed known issues related to authentication and data fetching.  
   - Enhanced error handling for better debugging.  
4. Deployment Preparation (Optional):  
   - Structured code for potential deployment on platforms like Vercel or Heroku.  
5. Final Submission:  
   - Pushed the updated code to GitHub.  
   - Ensured project documentation is complete and easy to understand.  

--- 


# Milestone 14 - Delete Product Functionality

## Overview
In this milestone, we implemented a delete functionality that allows users to remove a product from the database using its unique ID. This involved updating both the frontend and backend to support the delete operation.

## Learning Outcomes
By completing this milestone, we learned:
- How to create an API endpoint to delete a product from MongoDB using its ID.
- How to integrate the delete feature in the frontend.
- How to handle delete requests and update the UI accordingly.

## Steps Implemented
1. *Backend:*
   - Created an Express.js endpoint to handle DELETE requests.
   - Used MongoDB's delete operation to remove the product by its ID.

2. *Frontend:*
   - Added a delete button to each product card.
   - Implemented an event listener to send a delete request to the server when the button is clicked.
   - Updated the UI dynamically after a successful deletion.

## API Endpoint
*Method:* DELETE  
*Endpoint:* /api/products/:id  
*Description:* Deletes a product from the database using the provided ID.


### Milestone 15: Navbar Component & Navigation  

✅ **Goals:**  

⿡ **Create a Navbar Component**  
- Designed a **reusable** Navbar component.  
- Included navigation links for:  
  - **Home**  
  - **My Products**  
  - **Add Product**  
  - **Cart**



 Sure! Here's your detailed milestone breakdown rewritten in a more concise, narrative, and professional style—great for reports, presentations, or portfolio documentation:

---

### **Milestone 16: Product Info Page**
- **Implementation Highlights:**
  - Developed a dedicated product details page featuring the product name, description, price, and images.
  - Integrated a quantity selector and “Add to Cart” button to enhance user interaction.
  - Enabled dynamic routing using React Router to fetch product data based on URL parameters.
  - Focused on mobile responsiveness and added loading indicators for smoother UX.
- **Completion:** Code pushed to GitHub, README updated, and submission completed.

---

### **Milestone 17: Add to Cart Functionality**
- **Backend Enhancements:**
  - Extended the user schema to include a cart array storing product ID, name, price, and quantity.
  - Created a secure API endpoint to add items to the user's cart using MongoDB and Mongoose.
- **Frontend Integration:**
  - Connected the "Add to Cart" button with the backend and updated UI in real-time.
  - Implemented notifications and instant cart updates for better usability.
- **Completion:** All updates committed to GitHub and properly documented.

---

### **Milestone 18: Cart Page & Checkout**
- **Features Delivered:**
  - Developed a Cart Page showing product details, total value, and a "Remove" button.
  - Backend endpoints created to fetch and update cart items securely.
  - Added a functional Checkout button to confirm purchases, clear the cart, and redirect to confirmation.
  - Placeholder setup for future payment gateway integration.
- **User Experience:**
  - Dynamic subtotal/total pricing, mobile-friendly design, and real-time updates.
- **Completion:** Milestone updates pushed and shared.

---

### **Milestone 19: Quantity Management in Cart**
- **Frontend Improvements:**
  - Introduced increment/decrement buttons for product quantities.
  - Auto-removal of items when quantity hits zero.
- **Backend Logic:**
  - Built endpoints to manage quantity changes and ensure constraints like non-negative values.
  - Enabled instant UI feedback and clean interface handling.
- **Completion:** Code updated and submission finalized.

---

### **Milestone 20: Profile Page**
- **Backend:**
  - Exposed a secure endpoint for authenticated users to fetch their profile and address data.
- **Frontend:**
  - Designed a Profile Page showing photo, name, email, and stored addresses.
  - Added an “Add Address” button and appropriate handling for empty address states.
- **Completion:** Implementation complete and repository updated.

---

### **Milestone 21: Address Form Page**
- **Feature Implementation:**
  - Created a user-friendly address form collecting key fields like country, city, ZIP, and type.
  - Ensured users are directed here from the Profile Page when adding a new address.
  - Added form state management and field validation.
- **Completion:** Submitted with documentation.

---

### **Milestone 22: Address Storage Endpoint**
- **Backend:**
  - Developed a protected endpoint to store user addresses in the database.
  - Added validation, success/error handling, and messaging.
- **User Flow:**
  - Smooth experience from form submission to database storage.
- **Completion:** Pushed to GitHub and documented.

---

### **Milestone 23: Product Image Upload**
- **Backend Functionality:**
  - Created an admin-only image upload API using Multer.
  - Stored images in a local directory and saved paths in the DB.
- **UX Considerations:**
  - File validation for type and size.
  - Responsive feedback on upload status.
- **Completion:** Updates merged and submitted.

---

### **Milestone 24: Order Confirmation Page**
- **Frontend Delivery:**
  - Built a confirmation page summarizing selected products, address, total price, and a “Place Order” button.
  - Designed clean visuals with helpful UI cues.
- **User Feedback:**
  - Clear messaging on order confirmation and errors.
- **Completion:** Finalized and submitted.

---

### **Milestone 25: Place Order Endpoint**
- **Backend Logic:**
  - Created a secure endpoint that processes user orders, splitting each product into an individual order with a shared address.
  - Stored orders using a defined schema in MongoDB.
  - Secured endpoint with proper authentication and error handling.
- **Completion:** Feature deployed and README updated.

---

### **Milestone 26: Get User Orders**
- **Endpoint Functionality:**
  - Developed a user-specific order-fetching API using email for identification.
  - Handled edge cases like no orders found or invalid email.
- **Completion:** Fully tested and committed to the repository.

---

### **Milestone 27: My Orders Page**
- **Frontend Work:**
  - Designed a dedicated My Orders page pulling order data via GET request.
  - Displayed order information in an organized, readable layout.
  - Integrated the page into the app’s navigation.
- **UX Focus:** Added clear error messages and seamless data loading.
- **Completion:** All deliverables submitted successfully.

---

### **Milestone 28: Cancel Order Functionality**
- **Backend:**
  - Implemented an endpoint to cancel orders by updating their status.
  - Checked for order validity and prevented duplicate cancellations.
- **Frontend:**
  - Added a cancel button (visible only for active orders).
  - Synced UI with backend and reflected status changes instantly.
- **Completion:** Repository updated and shared.

---

### **Milestone 29: PayPal Payment Option (UI)**
- **Setup Steps:**
  - Created a PayPal developer account and retrieved sandbox credentials.
  - Displayed payment method choices on the confirmation page: COD and PayPal.
  - Used conditional rendering to show PayPal button when selected.
- **Completion:** Successfully staged for next milestone—full payment integration.

---

### **Milestone 30: PayPal Integration**
- **Backend:**
  - Integrated PayPal sandbox setup with proper API credentials.
- **Frontend:**
  - Added `@paypal/react-paypal-js`, wrapped app in `PayPalScriptProvider`, and configured `PayPalButtons`.
  - Handled transaction lifecycle: approval, capture, and feedback.
- **Security & UX:**
  - Managed payment responses securely and displayed real-time feedback.
- **Completion:** Feature completed and milestone submitted.

### **Milestone 31: Global State Management with Redux**
✅ Goals:
- **1️⃣ Backend - Redux Store Setup**
-Created a Redux store to manage global state for the application.
-Configured the Redux store with a user reducer to handle the user email state.
-Added actions for updating and accessing the global email state.
- **2️⃣ Frontend - Implementing Redux**
-Installed the react-redux package using:
-npm install react-redux
-Created a folder structure with store.js and userActions.js.
-Wrapped the App component with the Provider component to pass the Redux store to the rest of the application.
- **3️⃣ Enhancing User Experience with Redux**
-Handled the global state of the user email and ensured it's accessible across all components.
-Allowed for easy management and updating of the email state via Redux actions and reducers.
- **4️⃣ Submission Steps**
- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 31 details.
- ✅ Shared the repository link for submission.
Good luck, Kalvians! ✨

### **Milestone 32: Storing and Accessing Mail in Global State with Redux**
✅ Goals:
-**1️⃣ Backend - Redux Integration with Mail**
-Updated the Redux store to store the user's mail in the global state.
-Used the dispatch method to store the email in the global state upon login.
-**2️⃣ Frontend - Accessing Mail Across Pages**
--Used the useSelector hook to access the user's email in all pages.
- Ensured that the global email state is available across different components and pages.
-**3️⃣ Enhancing User Experience with Redux**
-Provided consistent access to the user's email across the application.
-Ensured the application responds to the state updates in a seamless manner.
-**4️⃣ Submission Steps**
-✅ Pushed the updated code to the GitHub repository.
-✅ Updated the README.md file with Milestone 32 details.
-✅ Shared the repository link for submission.
Good luck, Kalvians! ✨

### **Milestone 33: Creating and Storing JWT Token in Cookies**
✅ Goals:
-**1️⃣ Backend - JWT Token Creation**
-Installed the jsonwebtoken package using:
-npm install jsonwebtoken
-Used the sign method to create a JWT token, including the user's email and ID.
-**2️⃣ Storing JWT Token in Cookies**
-Set an expiration time for the JWT token using maxAge.
-Added the JWT token to the response as a cookie to store it in the browser.
-**3️⃣ Enhancing Security**
-Ensured that the JWT token is stored securely inside a cookie, facilitating seamless authentication.
-Implemented the cookie-based token storage to manage user sessions.
-**4️⃣ Submission Steps**
-✅ Pushed the updated code to the GitHub repository.
-✅ Updated the README.md file with Milestone 33 details.
-✅ Shared the repository link for submission.
-Good luck, Kalvians! ✨

### **Milestone 34: Validating JWT Token Stored in Cookies**
✅ Goals:
-**1️⃣ Backend - JWT Token Validation**
-Extracted the JWT token from the browser’s cookie and sent it to the server.
-Created a middleware function on the backend to validate the JWT token received from the client.
-Ensured the server checks if the token is valid before granting access to protected routes.
-**2️⃣ Frontend - Token Handling**
-Ensured that every page checks for the JWT token, preventing unauthorized access without login.
-Implemented token validation across the application to ensure users are logged in before accessing protected resources.
-**3️⃣ Enhancing Security and Authentication**
-Added robust token validation to secure the application and prevent unauthorized access.
-Implemented the necessary steps to protect routes using JWT token validation on the server side.
-**4️⃣ Submission Steps**
-✅ Pushed the updated code to the GitHub repository.
-✅ Updated the README.md file with Milestone 34 details.
-✅ Shared the repository link for submission.
-Good luck, Kalvians! ✨
--
### **Milestone 35: Deploying Your Project**
✅ Goals:
-**1️⃣ Deploying the Backend**
-Deployed the backend on a cloud service (e.g., Heroku, AWS, DigitalOcean, etc.).
-Retrieved the backend deployment link and ensured it was accessible.
-**2️⃣ Deploying the Frontend**
-Replaced the local backend URLs in the frontend code with the backend deployment link.
-Deployed the frontend to a hosting service (e.g., Netlify, Vercel, or any other platform).
-Verified that the frontend was connected to the deployed backend and functioning properly.
-**3️⃣ Full Deployment Verification**
-Ensured that both the frontend and backend were correctly deployed and were working as expected.
-Conducted final tests to confirm that the website was fully functional with deployed backend and frontend.
-**4️⃣ Submission Steps**
-✅ Pushed the updated code to the GitHub repository.
-✅ Deployed both the frontend and backend.
-✅ Shared the deployment link in the assignment submission section.
Good luck, Kalvians! ✨

---


## 🛠️ Tech Stack

### **Frontend:**
- ⚛️ **React.js / Next.js**
- 🎨 **Tailwind CSS / Bootstrap**
- 🛠️ **Redux** (for state management)

### **Backend:**
- 🖥️ **Node.js / Express.js**
- 🟢 **MongoDB**
- 🔑 **JWT Authentication**

### **Other Tools & Services:**
- ☁️ **Firebase / AWS S3** (for file storage)
- 💳 **Stripe / Razorpay** (for payment processing)
- 📝 **RESTful APIs / GraphQL**

This project aims to provide a **comprehensive learning experience** in **full-stack development** while building an exciting **e-commerce platform**! 🚀

