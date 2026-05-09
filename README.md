# 🎫 Event Access Management System

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

---

## 📌 Project Overview

This system allows:
- Users to **register/login** and **book events**
- Organizers to **create and manage** their events
- Admins to **manage all events and users**
- Organizers/Admins to **verify attendee entry** using a unique Ticket ID

---

## ⚙️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Node.js | JavaScript runtime |
| Express.js | Web framework |
| MongoDB | NoSQL Database |
| Mongoose | MongoDB object modeling |
| JWT | Authentication tokens |
| bcryptjs | Password hashing |
| dotenv | Environment variables |
| express-validator | Input validation |
| swagger-ui-express | API documentation |
| uuid | Unique ticket ID generation |

---

## 🚀 Getting Started

### Prerequisites
- Node.js installed → [nodejs.org](https://nodejs.org)
- MongoDB running locally **or** a free [MongoDB Atlas](https://www.mongodb.com/atlas) account
- Postman for API testing → [postman.com](https://www.postman.com)

### Installation

**1. Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/event-access-management.git
cd event-access-management
```

**2. Install dependencies**
```bash
npm install
```

**3. Set up environment variables**
```bash
cp .env.example .env
```
Open `.env` and fill in your values:
```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/event_access_db
JWT_SECRET=your_super_secret_key
JWT_EXPIRES_IN=7d
NODE_ENV=development
```

**4. Start the server**
```bash
# Development (auto-reload)
npm run dev

# Production
npm start
```

**5. Open API Docs**
