# FixIt – Local Worker Booking Platform

A full-stack web application that connects customers with local service providers
such as plumbers, electricians, cleaners, painters, and more — for on-demand
home services.

Built with **React, Node.js, MongoDB, Cloudinary**, and **payment integration**.

---

## 🚀 Tech Stack

| Layer | Technology |
|-----|-----------|
| Frontend | React (Vite) + Tailwind CSS |
| Backend | Node.js + Express.js |
| Database | MongoDB + Mongoose |
| Authentication | JWT (JSON Web Token) |
| Image Upload | Cloudinary |
| Payments | Razorpay |
| State Management | React Context API |
| Deployment Ready | Vercel / Render |

---

## 📂 Project Structure

```bash
fixit-online-marketplace-for-local-services/
│
├── frontend/        # Customer-facing application
├── admin/           # Admin dashboard
├── backend/         # Backend API
└── README.md
🔐 Environment Variables
Frontend (frontend/.env)
env
Copy code
VITE_BACKEND_URL=http://localhost:5000
Backend (backend/.env)
env
Copy code
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret

ADMIN_EMAIL=admin@example.com
ADMIN_PASSWORD=admin123
▶️ How to Run the Project
Step 1: Install dependencies
Backend
bash
Copy code
cd backend
npm install
Frontend
bash
Copy code
cd frontend
npm install
Admin
bash
Copy code
cd admin
npm install
Step 2: Start the servers
Backend
bash
Copy code
cd backend
npm start
Backend runs at:

arduino
Copy code
http://localhost:5000
Frontend
bash
Copy code
cd frontend
npm run dev
Frontend runs at:

arduino
Copy code
http://localhost:5173
Admin Panel
bash
Copy code
cd admin
npm run dev
Admin runs at:

arduino
Copy code
http://localhost:5174
🌐 Access URLs
Role	URL
Customer Home	http://localhost:5173
User Login	http://localhost:5173/login
Admin Panel	http://localhost:5174

🔮 Future Scope
Add real-time chat between customer and service provider

Implement reviews & ratings

Enable location-based service discovery

Add notifications (Email / SMS)

Dark mode support

👨‍💻 Author
Ram Acharya

GitHub: https://github.com/AcharyaRam

LinkedIn: https://linkedin.com/in/ram-acharya-b9b62326b

