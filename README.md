
# Blogify - MERN Stack WebApp

Blogify is a full-stack web application built using the MERN stack (MongoDB, Express, React, Node.js). It provides a seamless environment to create, edit, and share blog posts with features like authentication, CRUD operations, profile editing, and more. The app is designed with an eye-catching frontend and a scalable backend.

## Features
- **Authentication:** User login and registration.
- **CRUD Operations:** Create, read, update, and delete blog posts.
- **Profile Editing:** Edit user profiles with custom information.
- **Scalable Backend:** Built to handle growing data and users efficiently.
- **Eye-catching Frontend:** Responsive and interactive UI/UX.

## Project Setup

### Prerequisites
- Node.js and npm installed on your system.
- MongoDB Atlas account for cloud database (or set up a local MongoDB instance).

### Folder Structure

The project is divided into two main parts:

- `backend/`: Contains the server-side code.
- `frontend/`: Contains the client-side code.

## Backend Setup

1. Navigate to the `backend` directory:

   ```bash
   cd backend
   ```

2. Install the required dependencies:

   ```bash
   npm install
   ```

3. Set up your environment variables:

   Create a `.env` file in the `backend/` folder and add the following content:

   ```
   PORT=9080
   MONGO_URI="...."
   JWT_SECRET="qwertyuiopasdfghjklzxcvbnm"
   ```

4. Start the backend server:

   ```bash
   npm start
   ```

The backend will run on `http://localhost:9080`.

## Frontend Setup

1. Navigate to the `frontend` directory:

   ```bash
   cd frontend
   ```

2. Install the required dependencies:

   ```bash
   npm install
   ```

3. Set up your environment variables:

   Create a `.env` file in the `frontend/` folder and add the following content:

   ```
   REACT_APP_API_URL=http://localhost:5000/api
   ```

4. Start the frontend development server:

   ```bash
   npm start
   ```

The frontend will run on `http://localhost:3000`.

## Running the Application

1. Ensure both the backend and frontend servers are running.
2. Open your browser and go to `http://localhost:3000` to see the Blogify app in action.

## Contributing

Feel free to fork this repository, open issues, or submit pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License.

Happy Coding!
```
This README provides step-by-step instructions to set up and run your MERN stack app. It includes details about the folder structure, environment variables, and the necessary commands for installing dependencies and running the app.
