# Ecommerce-Follow-Along

created readme.md 
pushed readme.md

milestone 3 
Here's a proper format for a `README.md` file that you can use for your project:

```md
# Project Name

## 📌 Created `README.md`

### 🚀 Project Overview
Provide a brief introduction to the project. Mention its purpose, key features, and technologies used.

### 📂 Folder Structure
Explain the directory layout of your project for easy navigation.

```
project-folder/
│-- 📂 controllers/   # Handles request logic
│-- 📂 models/        # Defines database schemas
│-- 📂 routes/        # Manages API endpoints
│-- 📂 middlewares/   # Custom middleware functions
│-- 📂 utils/         # Helper functions and utilities
│-- 📂 config/        # Configuration files (e.g., database connection)
│-- 📜 server.js      # Main server entry point
```

### ⚙️ Setup Instructions
Provide step-by-step guidance on how to set up the project.

#### 🛠 Technologies Used
- **Node.js**: JavaScript runtime for backend development.
- **Express.js**: Web framework for building APIs.
- **MongoDB**: NoSQL database for data storage.

#### 📝 Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-repo
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the server:
   ```bash
   npm start
   ```
   The server will run on the designated port (e.g., `3000`).

### 🗄 Database Connection
Provide details on how to connect the project to a database.

- The database is managed using **MongoDB**.
- Connection settings are defined in `config/db.js`.
- Ensure MongoDB is running before starting the project.

### ⚠️ Error Handling
Explain how errors are handled in the project.

#### ✅ Best Practices
- Provide clear error messages.
- Implement a global error handler in Express.
- Use `try/catch` blocks for async functions.

#### 🛠 Example Middleware
```js
app.use((err, req, res, next) => {
  console.error(err.stack);
  res.status(500).json({ message: "🚨 Internal Server Error" });
});
```

### 🔜 Next Steps
List future improvements and planned features.

## 📤 Pushed `README.md`
```

You can replace placeholders like `your-username` and `your-repo` with actual values. Let me know if you need a more customized format! 🚀



## Milestone 4: Creating User Model and Controller

In this milestone, the following objectives were achieved:

- **User Model:** Created a User Model to define the structure of user data in the database.
- **User Controller:** Set up a User Controller to handle user-related operations, including creating and fetching users.
- **File Uploads with Multer:** Enabled file uploads using Multer to allow users to upload profile images.

### Folder Structure

The project is organized as follows:

- `frontend/`: Contains the React application.

  - `public/`: Static assets like HTML files.
  - `src/`: React components and related files.
  - `package.json`: Manages frontend dependencies.
  - `tailwind.config.js`: Configuration for Tailwind CSS.

- `backend/`: Contains the Node.js server.
  - `controllers/`: Contains the userController.js file.
  - `models/`: Contains the userModel.js file.
  - `routes/`: Contains the userRoutes.js file.
  - `middlewares/`: Contains the errorHandler.js file.
  - `uploads/`: Directory for storing uploaded files.
  - `index.js`: Main server file handling API requests.
  - `package.json`: Manages backend dependencies.

## Milestone 5: Creating Sign-Up Page

In this milestone, the following objectives were achieved:

- **Sign-Up Page:** Created a Sign-Up Page to allow users to register by filling out their details.
- **Form Validation:** Added basic form validation to ensure users input valid data before submitting the form.

### Folder Structure

The project is organized as follows:

- `frontend/`: Contains the React application.

  - `public/`: Static assets like HTML files.
  - `src/`: React components and related files.
  - `package.json`: Manages frontend dependencies.
  - `tailwind.config.js`: Configuration for Tailwind CSS.

- `backend/`: Contains the Node.js server.
  - `controllers/`: Contains the userController.js file.
  - `models/`: Contains the userModel.js file.
  - `routes/`: Contains the userRoutes.js file.
  - `middlewares/`: Contains the errorHandler.js file.
  - `uploads/`: Directory for storing uploaded files.
  - `index.js`: Main server file handling API requests.
  - `package.json`: Manages backend dependencies.

## Milestone 6: Encrypting Passwords and Storing User Data

In this milestone, the following objectives were achieved:

- **Password Encryption:** Used bcrypt to hash the user's password during signup.
- **Secure Data Storage:** Stored the hashed password and other user data securely in the database.

### Folder Structure

The project is organized as follows:

- `frontend/`: Contains the React application.

  - `public/`: Static assets like HTML files.
  - `src/`: React components and related files.
  - `package.json`: Manages frontend dependencies.
  - `tailwind.config.js`: Configuration for Tailwind CSS.

- `backend/`: Contains the Node.js server.
  - `controllers/`: Contains the userController.js file.
  - `models/`: Contains the userModel.js file.
  - `routes/`: Contains the userRoutes.js file.
  - `middlewares/`: Contains the errorHandler.js file.
  - `uploads/`: Directory for storing uploaded files.
  - `index.js`: Main server file handling API requests.
  - `package.json`: Manages backend dependencies.

