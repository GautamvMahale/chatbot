# 🤖 AI-Powered Chatbot (MERN + Google Gemini)

An intelligent, real-time chatbot application built using the **MERN Stack** with **Google Gemini AI integration**. Designed to deliver fast, human-like conversations with real-time messaging support and optimized performance.

---

## 🔥 Features

- 🧠 **AI Responses** — Uses Google Gemini for intelligent conversation
- 💬 **Real-Time Chat** — Powered by Socket.io
- 🧾 **Persistent History** — Stores messages securely in MongoDB
- ⚡ **Performance Boost** — Redis caching for faster responses
- 📱 **Responsive UI** — Built with React and Tailwind CSS
- 🔐 **Secure APIs** — Express + JWT (Optional for Auth)
- 🐳 **Dockerized** — Easily deployable across environments

---

## 🛠️ Tech Stack

| Layer         | Technology                         |
|--------------|-------------------------------------|
| Frontend     | React.js (with Hooks, Context API)  |
| Backend      | Node.js, Express.js                 |
| Database     | MongoDB                             |
| AI           | Google Gemini API                   |
| Real-Time    | Socket.io                           |
| Caching      | Redis                               |
| Dev Tools    | Docker, Postman                     |

---

## 🚀 Getting Started

### 1. Clone the Repository

git clone https://github.com/your-username/chatbot-mern-gemini.git
cd chatbot-mern-gemini
# for set up
cd server
npm install
## 2 Create a .env file inside server:
PORT=5000
MONGO_URI=your_mongodb_uri
GEMINI_API_KEY=your_google_gemini_key
REDIS_URL=your_redis_url
#Then run :
npm run dev
##3. Setup Frontend
cd ../client
npm install
npm start
-------
###🧠 How It Works
Users type messages in the React frontend.

Socket.io enables real-time messaging.

Backend processes the message and forwards it to Google Gemini.

Gemini generates a reply, which is then sent back via Socket.io.

MongoDB stores the full conversation history.

Redis caches previous responses to improve performance.




