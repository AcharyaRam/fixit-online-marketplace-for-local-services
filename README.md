# FixIt – Online Marketplace for Local Services

FixIt is a full-stack web application that connects users with local service providers such as electricians, plumbers, and home maintenance professionals. The platform allows users to discover services easily, while service providers can manage bookings efficiently through an admin dashboard.

---

## 🚀 Features

### User Side
- Browse and search local services
- User authentication and authorization
- Service booking and management
- Responsive and user-friendly UI

### Admin Panel
- Manage service providers
- View and manage bookings
- Secure admin authentication

### Backend
- RESTful APIs
- Secure authentication using JWT
- Database management with MongoDB

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- Tailwind CSS
- JavaScript

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication

### Admin Panel
- React (Vite)
- Tailwind CSS

---

## 📂 Project Structure

```bash
fixit-online-marketplace-for-local-services/
│
├── frontend/        # User-facing application
├── admin/           # Admin dashboard
├── backend/         # Backend API
└── README.md



⚙️ How to Run the Project Locally
1️⃣ Clone the repository
git clone https://github.com/AcharyaRam/fixit-online-marketplace-for-local-services.git

2️⃣ Install dependencies
Backend
cd backend
npm install
npm start

Frontend
cd frontend
npm install
npm run dev

Admin Panel
cd admin
npm install
npm run dev

🔐 Environment Variables

Create a .env file in the backend folder and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

👨‍💻 Author

Ram Acharya

GitHub: https://github.com/AcharyaRam

LinkedIn: https://linkedin.com/in/ram-acharya-b9b62326b