# 📚 BookStore App

**`Full-Stack Web Application for Book Management`**

The BookStore App is a full-stack web application that allows users to browse, buy, and manage books. It includes user authentication, personalized user data, and a responsive design for an excellent user experience.

---

## 🚀 Features

- **User Authentication**: Sign up and log in securely with hashed passwords.
- **Book Management**: Browse a list of books with details like name, price, category, and title.
- **Search and Filtering**: Quickly find books with search functionality.
- **User-Specific Features**: Personalized dashboard based on user login.
- **Responsive Design**: Mobile-first, responsive UI using modern CSS frameworks.
- **Dark Mode**: Toggle between light and dark themes.
- **Free Courses**: Separate section for free books or courses.

---

## 🛠️ Tech Stack

### Frontend
- **React.js**: For building a responsive and dynamic UI.
- **Tailwind CSS**: For styling the application.
- **React Router**: For navigation and routing.
- **React Hook Form**: For managing forms and validation.

### Backend
- **Node.js**: Server-side runtime environment.
- **Express.js**: Backend framework for creating APIs.
- **MongoDB**: NoSQL database for storing user and book data.
- **Mongoose**: ORM for managing MongoDB.

### Additional Tools
- **Axios**: For API requests.
- **bcrypt.js**: For hashing passwords.
- **dotenv**: For environment variable management.
- **toastify**: For notifications.

---

## 📂 Project Structure

### Backend

```
backend/
├── controllers/
│   ├── user.controller.js   # Handles user authentication logic
│   ├── book.controller.js   # Manages book-related operations
├── models/
│   ├── user.model.js       # User schema and model
│   ├── book.model.js       # Book schema and model
├── routes/
│   ├── user.route.js       # Routes for user endpoints
│   ├── book.route.js       # Routes for book endpoints
├── server.js               # Main server file
```

### Frontend

```
frontend/
├── components/
│   ├── Navbar.jsx         # Top navigation bar
│   ├── Footer.jsx         # Footer of the application
│   ├── Course.jsx         # Displays the list of books
│   ├── Cards.jsx          # Individual book card component
│   ├── Login.jsx          # Login form
│   ├── Signup.jsx         # Signup form
├── pages/
│   ├── Home.jsx          # Homepage layout
│   ├── Courses.jsx       # Courses page
├── App.jsx               # Main app component
```

---

## 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/bookstore-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd bookstore-app
   ```

3. Install dependencies for the backend:
   ```bash
   cd backend
   npm install
   ```

4. Install dependencies for the frontend:
   ```bash
   cd ../frontend
   npm install
   ```

5. Create a `.env` file in the `backend/` directory:
   ```env
   PORT=4001
   MongoDBURI=your_mongodb_connection_string
   ```

6. Start the backend server:
   ```bash
   cd backend
   npm start
   ```

7. Start the frontend development server:
   ```bash
   cd frontend
   npm run dev
   ```
