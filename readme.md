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

### ✅ Milestone 2: Project Setup & Login Page
- 🔐 Designed and implemented the **Login Page**.
- ⚙️ Configured **authentication mechanisms**.
- 📤 Committed and pushed all changes to GitHub.

### ✅ Milestone 3: Backend Organization & Database Setup
- 📂 Structured the backend with **dedicated folders** for better organization.
- 🌐 Set up a **Node.js server** for handling API requests.
- 🟢 Connected the application to **MongoDB**.
- 🛠️ Implemented **error handling** for a stable server environment.

### ✅ Milestone 4: User Model, Controller & File Uploads
- 👤 Created a **User Model** to store user data.
- 🛠️ Developed a **User Controller** for handling user operations.
- 📤 Integrated **Multer** for image and file uploads (profile pictures, product images).

### ✅ Milestone 5: User Registration UI & Validation
- 🎨 Designed a **user-friendly registration UI**.
- ✅ Implemented **form validation**.
- 🔗 Connected the registration **UI with the backend API**.

### ✅ Milestone 6: Login Authentication
- 🔑 Created a **backend login endpoint**.
- 🔍 Implemented **password encryption & validation** using `bcrypt`.
- ⚠️ Added **error handling** for incorrect login attempts.

### 🎉 Milestone 7: Product Card Component & Homepage
- 🛠️ Developed a **dynamic Product Card component**.
- 📄 Designed an **interactive homepage** displaying product cards.
- 🔁 Implemented **array mapping** to dynamically render products.

### 🚀 Milestone 8: Product Input Form
- 📝 Built a **frontend form** for adding new products.
- 🖼️ Enabled **multiple image uploads**.
- 🎨 Designed an intuitive **product input UI**.

### 🚀 Milestone 9: Product Schema & API Endpoint
- 🛠️ Created a **Mongoose schema** for products.
- 🔎 Implemented **validation** for required fields.
- 🌐 Built a `POST` endpoint for storing product details in **MongoDB**.

### 🚀 Milestone 10: Display Products on the Frontend
- 📝 Created an **endpoint to fetch product data** from MongoDB.
- 🔙 Developed a function to retrieve data in the frontend.
- 🖼️ Displayed products dynamically using the **Product Card component**.

### 🚀 Milestone 11: Personalized Products Page
- 🛒 Built a **"My Products" page** displaying a user’s added products.
- 📝 Developed an **endpoint to filter products** based on the user’s email.
- 🔙 Implemented frontend functionality to fetch and render **filtered products**.

### 🚀 Milestone 12: Edit Product Feature
- ✏️ Introduced an **Edit button** on the product card.
- 🛠️ Created a **backend endpoint** to update product details.
- 🔄 Auto-filled the **edit form** with existing product data.

### 🚀 Milestone 13: Delete Product Functionality
- 🗑️ Added a **Delete button** for products.
- ⚙️ Built a **backend endpoint** to delete products by ID.
- 🖱️ Implemented a **frontend function** to send a delete request.

Here’s a reworded version of your milestones while keeping the same content:  

---

### **Milestone 14: Implementing Product Deletion**  
✅ **Objectives:**  

1️⃣ **Backend - Delete Product API**  
- Developed an API endpoint to remove products by their unique ID.  
- Utilized Express.js and Mongoose to ensure secure and efficient deletion.  

2️⃣ **Frontend - Delete Button Functionality**  
- Integrated a Delete button into each product card.  
- Configured the button to send a request to the backend to delete the product when clicked.  

3️⃣ **User Experience Enhancements**  
- Added confirmation prompts to prevent accidental deletions.  
- Implemented smooth UI transitions upon product removal.  

4️⃣ **Submission Checklist**  
✅ Pushed updated code to GitHub.  
✅ Documented Milestone 14 in the README.md file.  
✅ Shared the repository link for review.  

---

### **Milestone 15: Navbar Creation & Navigation**  
✅ **Objectives:**  

1️⃣ **Building the Navbar Component**  
- Designed a responsive navigation bar featuring links for:  
  - Home  
  - My Products  
  - Add Product  
  - Cart  
- Ensured consistency across all pages for a unified experience.  

2️⃣ **Reusability & Scalability**  
- Implemented the Navbar across all screens for a standardized layout.  
- Optimized the component structure to support future scalability.  

3️⃣ **Responsiveness & UI Enhancements**  
- Utilized CSS Flexbox/Grid and Tailwind CSS for adaptable design.  
- Incorporated a hamburger menu for seamless navigation on mobile devices.  

4️⃣ **Submission Checklist**  
✅ Updated and committed code to GitHub.  
✅ Included Milestone 15 details in the README.md file.  
✅ Submitted the repository link.  

---

### **Milestone 16: Product Information Page**  
✅ **Objectives:**  

1️⃣ **Developing the Product Details Page**  
- Created a dedicated page to showcase product details such as:  
  - Name  
  - Description  
  - Price  
  - Images  

2️⃣ **Adding Quantity Selection & Cart Functionality**  
- Implemented a quantity selector to allow users to specify purchase amounts.  
- Added an "Add to Cart" button to enable product selection.  

3️⃣ **Dynamic Product Routing**  
- Utilized React Router for dynamic routes based on product IDs.  
- Fetched product details dynamically from the backend.  

4️⃣ **Enhancing User Experience**  
- Ensured mobile responsiveness for an optimal browsing experience.  
- Added loading indicators for smooth interactions.  

5️⃣ **Submission Checklist**  
✅ Pushed changes to GitHub.  
✅ Updated README.md with Milestone 16 information.  
✅ Submitted repository link.  

---

### **Milestone 17: Adding Cart Functionality**  
✅ **Objectives:**  

1️⃣ **User Schema Updates**  
- Enhanced the user schema to incorporate a cart system, storing:  
  - Product ID  
  - Name  
  - Price  
  - Quantity  

2️⃣ **Backend - Cart API**  
- Created an API endpoint to handle cart additions securely.  
- Integrated MongoDB & Mongoose for efficient cart data management.  

3️⃣ **Frontend - Cart Integration**  
- Linked the "Add to Cart" button to the backend API.  
- Implemented real-time updates for a smooth UI experience.  

4️⃣ **User-Friendly Enhancements**  
- Introduced notification pop-ups for successful cart additions.  
- Ensured cart updates occur instantly without requiring a page refresh.  

5️⃣ **Submission Checklist**  
✅ Code pushed to GitHub.  
✅ README.md updated with Milestone 17 details.  
✅ Repository link submitted.  

---

### **Milestone 18: Cart Page & Checkout Process**  
✅ **Objectives:**  

1️⃣ **Building the Cart Page**  
- Designed a cart interface displaying:  
  - List of added products  
  - Images, names, prices, and quantities  
  - Total cost calculation  
- Added a "Remove from Cart" button for each item.  

2️⃣ **Backend - Managing Cart Data**  
- Developed an API endpoint to fetch cart items from the database.  
- Implemented logic to modify product quantities.  

3️⃣ **Checkout Process**  
- Introduced a "Checkout" button to:  
  - Confirm orders  
  - Clear the cart upon successful purchase  
  - Redirect users to an order confirmation page  
- Set up a placeholder for future payment gateway integration.  

4️⃣ **User Experience Improvements**  
- Enabled real-time cart updates when quantities change.  
- Displayed subtotal and total prices dynamically.  
- Optimized for mobile responsiveness.  

5️⃣ **Submission Checklist**  
✅ Pushed the latest code to GitHub.  
✅ Included Milestone 18 in the README.md file.  
✅ Shared the repository link.  

---

### **Milestone 19: Cart Quantity Management**  
✅ **Objectives:**  

1️⃣ **Frontend - UI Updates for Cart**  
- Implemented + and - buttons to adjust product quantities dynamically.  
- Ensured accurate real-time pricing adjustments.  

2️⃣ **Backend - Quantity Management APIs**  
- Developed separate API endpoints for increasing and decreasing item quantities.  
- Added logic to prevent negative quantities and remove items when the count reaches zero.  

3️⃣ **User Experience Enhancements**  
- Provided instant feedback upon quantity changes.  
- Maintained a clean UI with intuitive controls.  

4️⃣ **Submission Checklist**  
✅ Uploaded updated code to GitHub.  
✅ Included Milestone 19 details in the README.md file.  
✅ Shared the repository link.  

---

### **Milestone 20: Profile Page Development**  
✅ **Objectives:**  

1️⃣ **Backend - User Data API**  
- Created a secure API endpoint to fetch user details and addresses.  
- Restricted access to authenticated users only.  

2️⃣ **Frontend - Profile Page UI**  
- Designed a profile section displaying:  
  - Profile picture  
  - Name  
  - Email  
  - Saved addresses  
- Included an "Add Address" button for easy address management.  
- Displayed a "No address found" message when no addresses exist.  

3️⃣ **User Experience Enhancements**  
- Optimized the profile page layout for seamless navigation.  

4️⃣ **Submission Checklist**  
✅ Code committed to GitHub.  
✅ README.md updated with Milestone 20 information.  
✅ Repository link submitted.  

---

### **Milestone 21: Address Form Implementation**  
✅ **Objectives:**  

1️⃣ **Frontend - Address Input Form**  
- Designed an address entry form collecting:  
  - Country  
  - City  
  - Address Line 1 & 2  
  - ZIP Code  
  - Address Type (Home, Office, etc.)  
- Ensured smooth navigation from the Profile Page to the form.  

2️⃣ **Enhancing User Experience**  
- Created an intuitive layout with clear input labels.  
- Implemented form validation to ensure required fields are completed.  

3️⃣ **Submission Checklist**  
✅ Code updates pushed to GitHub.  
✅ README.md documented with Milestone 21 details.  
✅ Repository link submitted.  

---

### **Milestone 22: Address Storage Backend**  
✅ **Objectives:**  

1️⃣ **Backend - Address Storage API**  
- Developed an API to receive and store user addresses.  
- Integrated logic to save addresses in the user's profile collection.  
- Restricted access to authenticated users for security.  

2️⃣ **User Experience Enhancements**  
- Implemented error handling for invalid entries.  
- Provided clear success/error messages for better user feedback.  

3️⃣ **Submission Checklist**  
✅ Uploaded code updates to GitHub.  
✅ README.md updated with Milestone 22 details.  
✅ Repository link submitted.  

---

This version keeps the meaning intact while improving readability and flow. Let me know if you'd like any tweaks! 🚀

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

