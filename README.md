# 🍽️ SHARE A SMILE - Food Donation Platform

## 🌍 About the Project
**SHARE A SMILE** is a technology-driven food donation platform designed to **reduce food waste** and **combat hunger**. It connects **donors** (individuals, supermarkets, NGOs) with **recipients** (people in need, NGOs, and food banks) efficiently and transparently.

By leveraging **Node.js, Express, MongoDB, and React**, this platform ensures seamless donation management, tracking, and communication between stakeholders.

## 🔐 Credentials
| Role               | Email                         | Password           |
|--------------------|-----------------------------|--------------------|
| Admin             | sagwakmaria@gmail.com        | adminpass123       |
| Donor             | ariavhope4@gmail.com         | @Mingyu_donor      |
| Recipient         | rhimelkhan@gmail.com         | @Byeon_recipient   |
| NGO               | angela.otieno254@gmail.com   | @Miran_ngo*        |
| Donor-Supermarket | sugakookiemin8@gmail.com     | *Mart_supermarket  |
| Donor-Restaurant  | savory.haven@gmail.com       | *Savory_restaurant |

---

## 🎯 Key Features
✅ **User Roles**: Donor, Recipient, NGO, Admin  
✅ **Donation Management**: Create, view, and claim food donations  
✅ **Search & Filtering**: Easily find donations based on category, expiry, and location  
✅ **Approval Process**: Ensure transparency in claims before pickup  
✅ **Chat System**: Communicate with donors and recipients via an integrated chat  
✅ **Dashboard Analytics**: View statistics on food donations, claims, and impact  
✅ **Notifications System**: Get real-time alerts for donation approvals, updates, and messages  
✅ **Automated Cleanup**: Expired donations are automatically marked unavailable  
✅ **Authentication & Authorization**: Secure login and role-based access control  

---

## 🏗️ Project Structure
```
SHAREASMILE-FOOD_DONATION_APP/
│── server/               # Backend (Node.js, Express, MongoDB)
│   ├── models/           # Database schemas
│   ├── routes/           # API endpoints
│   ├── controllers/      # Business logic
│   ├── middleware/       # Authentication & validation
│   ├── utils/            # Helper functions
│── client/               # Frontend (React, Bootstrap, ShadCN UI)
│   ├── components/       # Reusable UI components
│   ├── pages/            # Page views (Dashboard, Profile, Donations, etc.)
│   ├── services/         # API integration
│   ├── styles/           # Custom CSS & UI tweaks
│── .env                  # Environment variables
│── README.md             # Project Documentation
```

---

## 🔗 API Routes
### 🛠️ Authentication
- `POST /api/auth/register` → User registration
- `POST /api/auth/login` → User login
- `POST /api/auth/logout` → Logout

### 🍲 Food Donations
- `POST /api/donations/create` → Create a new food donation
- `GET /api/donations` → Get all available donations
- `GET /api/donations/:id` → Get donation details
- `PATCH /api/donations/:id/claim` → Claim a donation
- `DELETE /api/donations/:id` → Remove expired/unavailable donation

### 📊 Statistics & Recent Activities
- `GET /api/stats/donor` → Get donor-specific statistics
- `GET /api/stats/recipient` → Get recipient-specific statistics
- `GET /api/stats/admin` → Get platform-wide insights
- `GET /api/activities/:userId` → Get recent activities

### 📢 Notifications
- `GET /api/notifications` → Get user notifications
- `PATCH /api/notifications/read` → Mark notifications as read

### 💬 Chat System
- `POST /api/chat/send` → Send a message
- `GET /api/chat/:userId` → Retrieve chat messages

---

## 🚀 Tech Stack
### Backend 🛠️
- **Node.js & Express.js** → REST API development
- **MongoDB & Mongoose** → Database & schema management
- **JWT Authentication** → Secure authentication & role-based access
- **Socket.io (Planned Upgrade)** → Real-time chat & notifications

### Frontend 🎨
- **React.js** → Dynamic UI & user experience
- **ShadCN UI & Radix UI** → Modern UI components
- **Bootstrap & CSS** → Styling and layout

---

## 📌 Setup Instructions
### Prerequisites
Ensure you have **Node.js**, **MongoDB**, and **npm/yarn** installed.

### 1️⃣ Clone the Repository
```sh
$ git clone https://github.com/yourusername/share-a-smile.git
$ cd share-a-smile
```

### 2️⃣ Backend Setup
```sh
$ cd server
$ npm install
$ cp .env.example .env  # Configure environment variables
$ npm start
```

### 3️⃣ Frontend Setup
```sh
$ cd client
$ npm install
$ npm start
```

🚀 **Visit:** `http://localhost:3000/` to access the platform.

---

## 🎯 Roadmap & Future Enhancements
✔️ Implement donation approval process ✅ (In Progress)  
✔️ Enhance chat system with WebSockets 🔄 (In Progress) 
✔️ Optimize search filters for better efficiency 📌 (Planned)  
✔️ Improve user dashboard UI for better insights ✨ (Planned)
✔️ Multi-language Support
✔️ OTP Implementation for Secure Authentication 🔐 (Planned)
✔️ Lockscreen Feature During Inactivity ⏳ (Planned)

---

## 🛡️ Security & Best Practices
🔐 **Authentication**: JWT-based secure login system  
⚡ **Validation**: Backend data validation with middleware  
🛑 **Error Handling**: Standardized API responses with error codes  
📊 **Database Indexing**: Optimized for faster queries  

---

## 🤝 Contributing
We welcome contributions! Please follow these steps:
1. Fork the repo & clone it locally.
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes & push: `git push origin feature-name`
4. Submit a Pull Request 🎉

---

## 📩 Contact & Support
📧 Email:  
🌐 Website: [https://share-a-smile-food-donation-app.vercel.app/](https://share-a-smile-food-donation-app.vercel.app/)  

> *“Together, we can make a difference. Let's fight hunger, one meal at a time!”* 🍽️💙


---

## 🔗 Links
- **GitHub Repository**: [https://github.com/SagwaM/ShareASmile-Food_Donation_App](https://github.com/SagwaM/ShareASmile-Food_Donation_App)
- **Live Demo**: [https://share-a-smile-food-donation-app.vercel.app/](https://share-a-smile-food-donation-app.vercel.app/)
- **API Documentation**: 

---

## 📸 Screenshots
![Homepage Screenshot] <img width="799" alt="Homepage-SmileAShare" src="https://github.com/user-attachments/assets/66cf5ebf-8169-45d7-bab4-dbb0f106bc55" /> ![Chat System Screenshot]![Screenshot 2025-03-24 113333](https://github.com/user-attachments/assets/fa575bdd-8f07-47d8-954a-bb475556d99d)  <img width="865" alt="image" src="https://github.com/user-attachments/assets/c0fc398e-7cc1-4aea-ba5c-4ed4102ec8d6" />



