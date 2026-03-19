# FitNaija Fitness App 💪

FitNaija is a full-stack fitness application built to help users stay active, track progress, and maintain a healthier lifestyle.  
The app includes workout plans, progress tracking, BMI calculation, hydration reminders, and nutrition tips.

This project is designed as a **GitHub-ready full-stack repository** with a **mobile frontend (React Native + Expo)** and a **backend API (Node.js + Express + MongoDB)**.

---

## 🚀 Features

### User Features
- User Registration & Login
- JWT Authentication
- Personalized Dashboard
- Workout Plan Listing
- Workout Progress Tracking
- BMI Calculator
- Daily Water Intake Tracker
- Nutrition Tips
- Profile Management

### Developer Features
- Clean folder structure
- Scalable backend architecture
- Protected API routes
- MongoDB integration
- Reusable React Native components
- Easy setup for local development
- Ready for GitHub portfolio showcase

---

## 🛠️ Tech Stack

### Frontend (Mobile App)
- React Native
- Expo
- React Navigation
- Axios
- Context API

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT (JSON Web Tokens)
- bcryptjs
- dotenv
- cors

---

## 📁 Project Structure

```bash
fitnaija-fitness-app/
│
├── client/                     # React Native Expo mobile app
│   ├── assets/
│   ├── src/
│   │   ├── components/
│   │   ├── screens/
│   │   ├── navigation/
│   │   ├── services/
│   │   ├── utils/
│   │   └── context/
│   ├── App.js
│   ├── package.json
│   └── app.json
│
├── server/                     # Node.js + Express backend API
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   └── server.js
│   ├── .env.example
│   ├── package.json
│   └── .gitignore
│
├── README.md
├── .gitignore
└── package.json
```

---

## 📱 Screens Included

- Splash Screen
- Login Screen
- Register Screen
- Home Dashboard
- Workout Screen
- Progress Screen
- Nutrition Screen
- Profile Screen

---

## 🔐 Authentication

This project uses **JWT authentication**.

### Auth Flow
1. User registers an account
2. Password is hashed using `bcryptjs`
3. User logs in
4. JWT token is generated
5. Protected routes require valid token

---

## 📊 Core Functionalities

### 1. Workout Plans
Users can:
- Browse workouts
- View workout categories
- Mark workouts as completed

### 2. Progress Tracking
Users can track:
- Weight changes
- Workout completion
- Fitness progress over time

### 3. BMI Calculator
Users can calculate BMI using:
- Weight (kg)
- Height (m)

### 4. Hydration Tracker
Users can:
- Track daily water intake
- Monitor hydration goals

### 5. Nutrition Tips
Users receive:
- Healthy meal suggestions
- Basic nutrition advice
- Lifestyle improvement tips

---

## ⚙️ Installation Guide

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/fitnaija-fitness-app.git
cd fitnaija-fitness-app
```

---

## 2️⃣ Backend Setup

```bash
cd server
npm install
```

### Create Environment File

Create a `.env` file inside the `server` folder and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_super_secret_key
```

### Start Backend Server

```bash
npm run dev
```

Backend should run on:

```bash
http://localhost:5000
```

---

## 3️⃣ Frontend Setup

Open a new terminal:

```bash
cd client
npm install
```

### Start Expo App

```bash
npx expo start
```

You can then run the app on:
- Expo Go (Android/iPhone)
- Android Emulator
- iOS Simulator

---

## 🌐 API Endpoints

### Auth Routes
- `POST /api/auth/register` → Register user
- `POST /api/auth/login` → Login user

### Workout Routes
- `GET /api/workouts` → Get all workouts
- `POST /api/workouts` → Create workout (protected)

### Progress Routes
- `GET /api/progress` → Get user progress (protected)
- `POST /api/progress` → Add progress (protected)

---

## 🧪 Example API Request

### Register User

```http
POST /api/auth/register
Content-Type: application/json
```

```json
{
  "name": "Emmanuel",
  "email": "emmanuel@example.com",
  "password": "123456"
}
```

---

## 📦 Environment Variables

Inside `server/.env`:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_super_secret_key
```

---

## 🧹 .gitignore Suggestions

### Root `.gitignore`
```gitignore
node_modules/
.env
dist/
.expo/
coverage/
```

### Server `.gitignore`
```gitignore
node_modules/
.env
```

---

## 🚀 Future Improvements

- Push notifications
- Subscription plans
- Premium workout programs
- AI workout recommendation
- Video workout tutorials
- Admin dashboard
- Meal planner
- Calorie tracker
- Payment integration (Paystack / Flutterwave)
- Offline workout mode

---

## 💰 Monetization Ideas

This app can be monetized in Nigeria by adding:

- Premium workout plans
- Personalized coaching
- Nutrition consultation
- Fitness challenge entry fees
- In-app ads
- Affiliate links for fitness products
- Gym partnership subscriptions

---

## 📸 Suggested Screenshots Section

You can later add screenshots here:

```md
## 📸 App Screenshots

![Login Screen](./screenshots/login.png)
![Home Screen](./screenshots/home.png)
![Workout Screen](./screenshots/workout.png)
```

---

## 🤝 Contributing

Contributions are welcome!

To contribute:
1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit your changes
5. Push to your branch
6. Open a Pull Request

---

## 📝 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Emmanuel Adegoke**

If you use this project, feel free to customize and scale it for your own fitness startup.

---

## ⭐ Support

If you like this project:

- Star the repository on GitHub
- Share it with friends
- Build on top of it
- Turn it into a real business 🚀

---

## 📬 Contact

For collaborations or improvements, you can connect through your GitHub profile.

---

# Built with passion for fitness, growth, and real-world impact 💪🔥
