# 📰 Online News Portal

A full-stack **Online News Portal** web application inspired by platforms like Prothom Alo.  
Users can read news by category, while admins and editors can manage content efficiently.

---

## 🚀 Features

### 👤 User Features
- 📰 Browse latest news
- 🔍 Search news by title
- 🗂️ Filter news by category
- 📱 Responsive UI (mobile + desktop)

### 🔐 Authentication & Security
- 🔑 JWT Authentication
- 🔒 Secure password hashing (bcrypt)
- 🔁 Password reset system (email-based)
- 🌐 OAuth login (Google)

### 🧑‍💻 Admin / Editor Features
- ➕ Add news
- ✏️ Edit news
- ❌ Delete news
- 🗂️ Manage categories
- 👥 Role-based access (Admin / Editor / User)

---

## 🛠️ Tech Stack

### 🌐 Frontend
- React.js / Next.js
- Tailwind CSS / Bootstrap

### ⚙️ Backend
- Node.js
- Express.js

### 🗄️ Database
- MongoDB Atlas

### 🔐 Auth & Security
- JWT (JSON Web Token)
- OAuth (Google Login)
- bcrypt

---

## 📁 Project Structure
news-portal/

│

├── client/ # Frontend (React / Next.js)

├── server/ # Backend (Node.js + Express)

│

├── models/ # MongoDB Models

├── routes/ # API Routes

├── controllers/ # Business logic

│

├── .env # Environment variables

├── .gitignore

└── README.md


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
bash
git clone https://github.com/your-username/your-repo.git
cd news-portal

---

### 2️⃣ Install dependencies
npm install

---

### 3️⃣ Setup environment variables

Create a .env file in root:
**This won't shows to others**
PORT=8080
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
GOOGLE_CLIENT_ID=your_client_id
GOOGLE_CLIENT_SECRET=your_client_secret
EMAIL_USER=your_email
EMAIL_PASS=your_password

---

### 4️⃣ Run the project
npm start
🔗 API Endpoints (Example)
Method	Endpoint	Description
POST	/api/auth/register	Register user
POST	/api/auth/login	Login
GET	/api/news	Get all news
POST	/api/news	Create news
PUT	/api/news/:id	Update news
DELETE	/api/news/:id	Delete news
🧠 Future Improvements
🖼️ Image upload (Cloudinary)
💬 Comment system
⭐ Bookmark / Save news
📊 Admin dashboard analytics
🌍 Multi-language support
🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

---

### 📄 License

This project is licensed under the MIT License.

---

### 👨‍💻 Author

Asif Hasan

GitHub: https://github.com/asifhasanplabon
LinkedIn: https://linkedin.com/in/plabon010