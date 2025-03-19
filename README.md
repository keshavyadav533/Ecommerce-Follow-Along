# 📌 Project Name: E_Commerce_Follow_Along  

## 🚀 Overview  
This project is an e-commerce website developed through a series of milestones, progressively adding features to build a complete and functional application.

## 📚 Table of Contents  
- [Overview](#-overview)  
- [Tech Stack](#-tech-stack)  
- [Milestones](#-milestones)  
  - [Milestone 1: Project Setup](#milestone-1-project-setup)  
  - [Milestone 2: Frontend & Backend Initialization](#milestone-2-frontend--backend-initialization)  
  - [Milestone 3: Backend Structure & Server Setup](#milestone-3-backend-structure--server-setup)  
  - [Milestone 4: Creating User Model and Controller](#milestone-4-creating-user-model-and-controller)  
  - [Milestone 5: Sign-Up Page & Form Validation](#milestone-5-sign-up-page--form-validation)  
  - [Milestone 6: Secure User Registration](#milestone-6-secure-user-registration)  
  - [Milestone 7: User Login & Authentication](#milestone-7-user-login--authentication)  
  - [Milestone 8: Product Card Component & Homepage Layout](#milestone-8-product-card-component--homepage-layout)  
  - [Milestone 9: Product Input Form](#milestone-9-product-input-form)  
  - [Milestone 10: Product Schema & Endpoint Creation](#milestone-10-product-schema--endpoint-creation)
  - [Milestone 11: Dynamic Homepage with Product Data](#milestone-11-dynamic-homepage-with-product-data)
  - [Milestone 12: My Products Page - Filtering by User Email](#milestone-12-my-products-page---filtering-by-user-email)
- [How to Run the Project](#-how-to-run-the-project) 
---

## 🛠 Tech Stack  
- Frontend: React.js, Tailwind CSS  
- Backend: Node.js, Express.js  
- Database: MongoDB  
- File Uploads: Multer  
- Password Encryption: bcrypt  
- Version Control: Git, GitHub  

---

## 📌 Milestones  

### Milestone 1: Project Setup  
*✅ Goals:*  
- Created and updated README.md file.  
- Initialized GitHub repository for version control.  

---
 
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

⿢ **Make Navbar Responsive**  
- Ensured the Navbar adapts to **all screen sizes** (desktop, tablet, mobile).  
- Used **Tailwind CSS** for styling and responsiveness.  

⿣ **Integrate Navbar Across Pages**  
- Added the **Navbar component** to all screens.  
- Ensured smooth navigation between pages.  

⿤ **Improve User Experience**  
- Implemented **active link highlighting** to indicate the current page.  
- Used **React Router** for seamless routing.  

✅ **Final Steps:**  
- **Tested** the navigation flow.  
- **Updated** the `README.md` with Milestone 15 details.  
- **Pushed** changes to GitHub.  

🚀 **Next Up:** Continue improving UI and adding more interactive features!  

---

### Milestone 16: Product Info Page  

✅ Goals:  

#### ⿡ Creating the Product Info Page  
- Designed a dedicated page to display detailed product information, including:  
  - Product Name  
  - Description  
  - Price  
  - Image(s)  

#### ⿢ Adding Quantity Selection & "Add to Cart" Button  
- Implemented a quantity selector to allow users to choose the desired quantity.  
- Added an "Add to Cart" button to store selected items in the cart.  

#### ⿣ Dynamic Routing for Product Details  
- Utilized React Router to create dynamic routes for each product.  
- Fetched product details based on the product ID from the URL.  

#### ⿤ Enhancing User Experience  
- Ensured mobile responsiveness for smooth browsing on all devices.  
- Implemented loading indicators for better user experience.  


### Milestone 17: Add to Cart Functionality  

✅ Goals:  

#### ⿡ Update User Schema for Cart Functionality  
- Modified the user schema to include a cart field.  
- Structured the cart field to store an array of product objects containing:  
  - Product ID  
  - Name  
  - Price  
  - Quantity  

#### ⿢ Backend - Add to Cart Endpoint  
- Created an endpoint to receive product details and store them in the user's cart.  
- Ensured secure handling of requests and efficient database updates using MongoDB & Mongoose.  

#### ⿣ Frontend - Add to Cart Integration  
- Connected the "Add to Cart" button from the Product Info Page to the backend API.  
- Stored cart data in the database and updated the UI dynamically.  

---

### Milestone 18: Cart Page and Checkout Functionality  

✅ Goals:  

#### ⿡ Creating the Cart Page  
- Designed a Cart Page to display:  
  - List of added products  
  - Product images, names, prices, and quantities  
  - Total cart value  
- Implemented a Remove from Cart button for each item.  

#### ⿢ Backend - Fetch & Update Cart  
- Created an endpoint to retrieve cart items from the database.  
- Implemented an API to update product quantities in the cart.  
- Ensured secure cart data management for logged-in users.  

#### ⿣ Checkout Functionality  
- Added a Checkout button that:  
  - Confirms the order  
  - Clears the cart after a successful purchase  
  - Redirects users to an order confirmation page  
- Integrated a payment gateway placeholder for future improvements.  

#### ⿤ User Experience Enhancements  
- Provided real-time cart updates when quantities change.  
- Displayed subtotal and total price dynamically.  
- Ensured a mobile-friendly UI for a seamless experience.

 
### Milestone 19: Cart Quantity Management

✅ Goals:

### ⿡ Frontend - Cart Page UI Enhancements

- Added + and - buttons next to each product to modify its quantity.

- Ensured real-time updates for accurate pricing adjustments.

### ⿢ Backend - Quantity Management Endpoint

- Created two API endpoints to increase and decrease product quantity in the cart.

- Integrated logic to prevent negative quantities and handle item removal automatically when reduced to zero.

### ⿣ Enhancing User Experience

- Ensured instant feedback when quantity adjustments are made.

- Maintained a clean UI design with clear quantity controls.

---
### Milestone 20: Profile Page

✅ Goals:

### ⿡ Backend - User Data Endpoint

- Created an API endpoint to send all user data including profile details and addresses.

- Ensured the endpoint is secure and accessible only to authenticated users.

### ⿢ Frontend - Profile Page UI

- Designed a Profile Page that displays:

   - Profile Photo

   - Name

   - Email

   - List of Addresses

- Added a clear "Add Address" button for adding new addresses.

- Displayed "No address found" when no addresses are available.

### ⿣ Enhancing User Experience

- Ensured the profile page design is clean and easy to navigate.

---

# Milestone 21: Address Form Page

✅ *Goals:*

### ⿡ Frontend - Address Form Page

- Created an address form page that collects the following details:
  - *Country*
  - *City*
  - *Address Line 1*
  - *Address Line 2*
  - *ZIP Code*
  - *Address Type* (e.g., Home, Office, etc.)

- Implemented a state that stores the address input data for better management.

- Ensured that when users click the "Add Address" button on the Profile Page, they are navigated to this form page.

### ⿢ Enhancing User Experience

- Designed the address form to be user-friendly and intuitive.
- Ensured clear input labels and proper validation for required fields.

---
# Milestone 22: Address Storage Endpoint

✅ *Goals:*

### ⿡ Backend - Address Storage Endpoint

- Created an API endpoint that receives address data from the frontend address form.
- Added logic to store the received address inside the address array within the user's profile collection in the database.
- Ensured endpoint security by restricting access to authenticated users only.

### ⿢ Enhancing User Experience

- Ensured proper error handling to manage invalid data entries.
- Implemented success and error response messages for clear user feedback.


## ▶ How to Run the Project  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/E_Commerce_Follow_Along.git  
   cd E_Commerce_Follow_Along  
   ```  
   
2. Install dependencies for both frontend and backend:  
   ```bash  
   cd frontend && npm install  
   cd ../backend && npm install  
   ```  
   
3. Run the backend server:  
   ```bash  
   npm start  
   ```  
   
4. Run the frontend application:  
   ```bash  
   cd frontend  
   npm start  
   ```  
   
5. Open [http://localhost:3000/](http://localhost:3000/) in your browser.  

