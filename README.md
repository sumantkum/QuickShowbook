# QuickShow – Book & Show Booking Platform

QuickShow is a full-stack web application that allows users to explore, book, and manage shows or books with a smooth and modern user experience.  
This project is built to demonstrate real-world application architecture, UI design, and backend integration.

---

## Features

- Browse available books and shows
- View detailed information
- Book tickets / reserve books
- User authentication (Login / Signup)
- Admin dashboard for managing shows
- Responsive design (Mobile + Desktop)
- Scalable backend architecture

---

## Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Framer Motion
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### Authentication
- JWT (JSON Web Token)

### Deployment
- Frontend: Vercel
- Backend: Node / Cloud Server
- Database: MongoDB Atlas

---

## Project Structure
```
QuickShow/
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── context/
│ │ ├── services/
│ │ └── App.jsx
│
├── backend/
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ ├── middleware/
│ └── server.js
│
└── README.md

Frontend Setup
cd frontend
npm install
npm run dev

Backend Setup
cd backend
npm install
npm start
