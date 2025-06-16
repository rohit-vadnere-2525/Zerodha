# Zerodha Clone 💹

A full-stack stock trading dashboard inspired by Zerodha. This project provides a modern, interactive frontend and robust backend architecture for simulating stock orders, holdings, and analytics.

---

## 🔧 Tech Stack

- **Frontend**: React.js, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Others**: Chart.js (Doughnut Charts), dotenv, MVC Architecture

---

## ✨ Features

- 💻 Clean & modern React frontend with component-based structure  
- 📊 Live charts for holdings & positions using reusable chart components  
- 🧾 Order placement and holdings simulation  
- 📁 Modular folder structure using **MVC pattern**  
- 🗂️ Environment variables secured using `.env`  
- 🛠️ Fully scalable and easy to maintain project setup

---

## 📁 Folder Structure

```
Zerodha/
├── client/             # React frontend
│   ├── components/
│   ├── pages/
│   └── App.js
├── models/             # MongoDB schemas
├── routes/             # Express routes
├── controllers/        # Backend logic
├── .env
├── server.js
└── README.md
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/zerodha-clone.git
cd zerodha-clone
```

### 2️⃣ Install dependencies
```bash
npm install
cd client
npm install
```

### 3️⃣ Set up environment variables
Create a `.env` file in the root and add:

```
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

### 4️⃣ Run the project

```bash
# Run backend
npm run server

# Run frontend
cd client
npm start
```

---

## 🧑‍💻 Author

- [Rohit Rajesh Vadnere](https://github.com/rohit_vadnere-2525)
- MERN Stack Developer | Passionate about building scalable web apps

---

## 📜 License

This project is licensed under the MIT License. Feel free to use and contribute.

---
