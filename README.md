
# Book Store (MERN Stack Project)

Welcome to the **Book Store** project! This is a full-stack web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. The project showcases the capabilities of a dynamic and modern web application, providing a seamless platform for managing books.

## Features

- 📚 **Book Management**: Add, view, edit, and delete book details.
- 🔍 **Search Functionality**: Find books quickly using the search feature.
- 🛒 **Shopping Cart**: Add books to your cart for purchase.
- 🛡️ **Authentication**: Secure user login and registration.
- 📈 **Responsive Design**: Optimized for both desktop and mobile devices.
- 🔄 **Real-Time Updates**: Dynamic content updates without page reloads.

## Tech Stack

- **Frontend**: React.js, HTML, CSS, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Others**: RESTful APIs, JWT Authentication

## Installation

Follow these steps to run the project locally:

### Prerequisites
- Node.js and npm installed
- MongoDB installed and running locally or access to a MongoDB cloud instance

### Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/najeeb-08/Book-Store-MERN-Stack-Project.git
   cd Book-Store-MERN-Stack-Project
   ```

2. **Install dependencies**:
   - For the backend:
     ```bash
     cd backend
     npm install
     ```
   - For the frontend:
     ```bash
     cd frontend
     npm install
     ```

3. **Set up environment variables**:
   Create a `.env` file in the backend directory and include the following:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   ```

4. **Run the application**:
   - Start the backend server:
     ```bash
     cd backend
     npm start
     ```
   - Start the frontend development server:
     ```bash
     cd frontend
     npm start
     ```

5. Open your browser and navigate to `http://localhost:3000`.

## Project Structure

```
Book-Store-MERN-Stack-Project/
│
├── backend/
│   ├── models/         # MongoDB schemas
│   ├── routes/         # API routes
│   ├── controllers/    # Request handlers
│   └── server.js       # Entry point for the backend
│
├── frontend/
│   ├── src/
│   │   ├── components/ # React components
│   │   ├── pages/      # Application pages
│   │   ├── App.js      # Main React component
│   │   └── index.js    # Entry point for the frontend
│
└── README.md           # Project documentation
```

## Screenshots

_Add screenshots here to showcase your application. This can include the homepage, book list, search, and shopping cart._

## Contributing

Contributions are welcome! If you'd like to contribute to this project:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Added a new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
