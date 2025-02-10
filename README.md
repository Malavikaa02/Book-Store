# 📚✨ MERN Book Store 🚀

## 📖 Description
The **MERN Book Store** is a full-stack web application that allows users to manage a collection of books. Users can 📖 browse, 🔍 search, ➕ add, 📝 edit, and ❌ delete books with an intuitive interface. Built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js), this application offers seamless 🔑 user authentication and a responsive design 📱.

---

## 🚀 Features
- 🔑 **User Authentication**: Login and registration functionality
- 📚 **Browse Books**: View available books in an interactive UI
- 🔍 **Search Books**: Search by title, author, or genre
- ✍️ **Add Books**: Add new books to the collection
- 📝 **Edit Books**: Update book details
- ❌ **Delete Books**: Remove books from the collection
- 📱 **Responsive Design**: Optimized for different screen sizes

---

## 🛠️ Technologies Used
- 🎨 **Frontend:** React.js, Redux, React Router, Bootstrap
- ⚙️ **Backend:** Node.js, Express.js
- 🗄️ **Database:** MongoDB, Mongoose
- 🔐 **Authentication:** JSON Web Tokens (JWT), bcrypt
- 🛠️ **Other Tools:** Git, Heroku (for deployment)

---

## ⚡ Installation & Setup

### 🔑 Prerequisites
- 🖥️ **Node.js** & **npm** installed
- 🗃️ **MongoDB** (local or cloud database)
- 🌍 **Git** installed

### 📝 Steps to Set Up the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Malavikaa02/Book-Store.git
   cd mern-book-store
   ```

2. **Install Dependencies**:
   - 🖥️ Backend dependencies:
     ```bash
     cd backend
     npm install
     ```
   - 🎨 Frontend dependencies:
     ```bash
     cd ../frontend
     npm install
     ```

3. **Set Up Environment Variables**:
   Create a `.env` file inside the `backend` directory and add the following:
   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   PORT=5000
   ```

4. **Run the Application**:
   - ⚙️ Start the **backend server**:
     ```bash
     cd backend
     nodemon index.js
     ```
   - 🎨 Start the **frontend server**:
     ```bash
     cd ../frontend
     npm run dev
     ```
   - The application will be available at:
     - 🌍 **Frontend**: http://localhost:5173
     - 🖥️ **Backend**: http://localhost:5000

---

## 🌟 Contributing
Contributions are welcome! Follow these steps:
1. 🍴 **Fork** the repository.
2. 🌿 **Create a new branch**: `git checkout -b feature-branch`
3. 🛠️ **Make changes** and **commit**: `git commit -m 'Add new feature'`
4. 🚀 **Push to branch**: `git push origin feature-branch`
5. 🎉 **Open a Pull Request** on GitHub.

---



