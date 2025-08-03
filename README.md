# 🌍 Smart AI Translator - Frontend

This is the **frontend** for Smart AI Translator, built with **HTML, CSS, and JavaScript**.  
It connects to the backend API (Flask app) to fetch supported languages and translate text in real-time.

---

## 📂 Project Structure

translator-frontend/
│── index.html # Main frontend interface
│── README.md # Project documentation
│── .gitignore # Ignore unnecessary files


---

## 🛠 Setup

### 1️⃣ Clone the Repository

git clone https://github.com/YOUR-USERNAME/translator-frontend.git
cd translator-frontend

### 2️⃣ Update Backend API URL
Open index.html and update:

const backendURL = "YOUR_RENDER_BACKEND_URL";

Replace with your deployed backend URL from Render.

## 🌐 Usage
Open index.html in a browser (for local testing) OR deploy to Vercel.

Enter text, select input & target languages, click Translate.

The translation will appear instantly.
