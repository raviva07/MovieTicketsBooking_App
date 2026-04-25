# 🎬 Movie Ticket Booking App

A full-stack Movie Ticket Booking System built using **Spring Boot (Backend)**, **MongoDB (Database)**, and **React (Frontend)**.  
This application allows users to browse movies, check showtimes, select seats, and book tickets online with a smooth and responsive UI.

---

## 🚀 Features

### 👤 User Features
- User registration and login (JWT authentication)
- Browse available movies
- View movie details and showtimes
- Select seats and book tickets
- View booking history
- Receive booking confirmation 

### 🎬 Admin Features
- Add / update / delete movies
- Manage show timings
- Manage seat availability
- View all bookings

### ⚙️ System Features
- Role-based access (ADMIN / USER)
- Secure authentication with JWT
- RESTful API architecture
- Responsive UI (React)
- MongoDB for flexible data storage

---

## 🛠️ Tech Stack

### Backend
- Java 17+
- Spring Boot
- Spring Security (JWT)
- Spring Data MongoDB
- Maven

### Frontend
- React JS
- Redux Toolkit
- Axios
- React Router

### Database
- MongoDB

---



---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/movie-ticket-booking-app.git
🖥️ Backend Setup (Spring Boot)
2️⃣ Configure MongoDB
Make sure MongoDB is running locally or use MongoDB Atlas.

Update application.properties:

properties

spring.application.name=movie-ticket-booking-backend
server.port=8080

spring.data.mongodb.uri=mongodb://localhost:27017/movieticket_db

# JWT Secret
jwt.secret=yourSecretKey
jwt.expiration=86400000
3️⃣ Run Backend
bash
Copy code
cd backend
mvn clean install
mvn spring-boot:run
Backend runs on:


http://localhost:8080
🌐 Frontend Setup (React)
4️⃣ Install Dependencies

cd frontend
npm install
5️⃣ Start React App

npm start
Frontend runs on:


http://localhost:3000
🔐 Authentication Flow
User registers / logs in

JWT token is generated

Token is stored in localStorage

Token is sent in headers for protected APIs

📡 API Endpoints (Sample)
Auth
POST /api/auth/register

POST /api/auth/login

Movies
GET /api/movies

POST /api/movies (Admin)

PUT /api/movies/{id} (Admin)

DELETE /api/movies/{id} (Admin)

Booking
POST /api/bookings

GET /api/bookings/user/{userId}




👨‍💻 Author
Developed by Ravi Varma

📌 Note
This project is built for learning and portfolio purposes. It demonstrates full-stack development using modern Java and React technologies.

⭐ If you like this project, don't forget to star the repository!
