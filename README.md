# **MERN E-commerce Website**


This is a beginner-friendly full-stack E-commerce web application built using the **MERN Stack** — MongoDB, Express.js, React.js, and Node.js.

It allows users to browse products, register accounts, and view item details. Admins can manage product data via backend APIs.

---

## 🚀 Features

### 👤 User Side:
- User registration
- Product browsing
- Responsive product grid
- Simple & clean UI

### 🔐 Admin Side:
- Add new products manually (MongoDB)
- View all registered users (MongoDB)

---

## 🛠️ Tech Stack

| Layer       | Technology           |
|-------------|----------------------|
| Frontend    | React.js, CSS |
| Backend     | Node.js, Express.js  |
| Database    | MongoDB (Mongoose)   |
| Tools       | Git, GitHub, VS Code |

---

## 📁 Project Structure
mern-ecommerce/
├── backend/
│ ├── models/
│ ├── routes/
│ ├── server.js
│
├── frontend/
│ ├── src/
│ │ ├── App.js
│ │ ├── App.css
│
├── README.md

⚙️ Installation

🔧 2. Backend Setup
bash
Copy
Edit
cd backend
npm install
Create a file named .env inside backend and add:

ini
Copy
Edit
MONGO_URI=mongodb://127.0.0.1:27017/mernshop
PORT=5000
Start the backend server:

bash
Copy
Edit
npm run server

💻 3. Frontend Setup
Open a new terminal:

bash
Copy
Edit
cd frontend
npm install
npm start
The app will run at:
http://localhost:3000

📌 Usage

Browse products from the homepage.

Register a new account.

Admin can add products directly from the database (MongoDB Compass or code).

Checkout/cart management can be extended further.

🧑‍💻 Author
Abhijit Kumar


🌟 License
This project is licensed under the MIT License.


