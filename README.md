# 🌍 Travel Around — AI-Powered Group Travel Planning

<div align="center">

![Travel Around](https://img.shields.io/badge/Travel%20Around-Smart-blue)
![MERN Stack](https://img.shields.io/badge/Stack-MERN-green)
![Node.js](https://img.shields.io/badge/Node.js-18.x-brightgreen)
![React](https://img.shields.io/badge/React-18.x-61dafb)
![AI Powered](https://img.shields.io/badge/AI-Powered-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

### ✈️ Plan Smarter. Explore Together. Travel Better.

**A full-stack AI-powered travel platform that takes the chaos out of group trips — generating personalized itineraries, handling group conflicts, and keeping everyone on the same page.**

</div>

---

## 🌟 What is Travel Around?

I built Travel Around because planning group trips with friends is genuinely painful. Everyone has different budgets, different interests, and nobody ever agrees. This app uses AI to step in as the neutral coordinator — it generates smart, day-wise itineraries based on the group's collective preferences, balances the budget, and even handles conflicting opinions intelligently.

Whether you're planning a weekend road trip with 3 friends or a 2-week international tour with a full group, Travel Around has you covered.

## ✨ Key Features

* 🤖 **AI Itinerary Generator** — Generate detailed, day-wise travel plans based on group interests and budget using Gemini AI.
* 🧠 **Smart Conflict Resolution** — AI-driven logic that finds the middle ground when group members have conflicting preferences.
* 💰 **Budget Optimizer** — Estimates costs, splits expenses, and suggests optimizations so no one breaks the bank.
* 👥 **Real-time Collaboration** — A centralized hub where group members can vote, discuss, and finalize plans together.
* 💬 **Trip Chat** — Built-in Socket.io powered chat for each trip group — no need for a separate WhatsApp group.
* 🛡️ **Admin & Organiser Dashboards** — Comprehensive controls for trip validation, user management, and booking oversight.
* 🔔 **Live Notifications** — Real-time alerts for booking approvals, new messages, and trip updates.

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|-------------|
| **Frontend** | React 18, Vite, TailwindCSS v4, shadcn/ui |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB + Mongoose |
| **AI / LLM** | Google Gemini AI |
| **Real-time** | Socket.io |
| **Auth** | Sessions + Bcrypt |

## 📁 Project Structure

```text
travel-around/
├── client/          # Vite + React Frontend
│   ├── src/
│   │   ├── components/   # Reusable UI components
│   │   ├── pages/        # Route-level page components
│   │   ├── context/      # Auth & global state
│   │   ├── service/      # API & AI model utilities
│   │   └── chat/         # Socket.io chat module
├── server/          # Node.js + Express Backend
│   ├── models/      # Mongoose schemas
│   ├── routes/      # REST API endpoints
│   └── middleware/  # Auth middleware
├── .github/         # CI/CD Workflows
└── README.md
```

## 🚀 Getting Started

### Prerequisites

* Node.js (v18+)
* MongoDB (local or Atlas)
* Google Gemini API Key

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sonakshi2407/travel-around.git
   cd travel-around
   ```

2. **Install all dependencies (client + server):**
   ```bash
   npm run install-all
   ```

3. **Set up environment variables:**
   Create a `.env` file inside the `server/` directory:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   GEMINI_API_KEY=your_gemini_api_key
   JWT_SECRET=your_secret_key
   SESSION_SECRET=your_session_secret
   ```

### Running Locally

```bash
# Run both frontend and backend concurrently
npm run dev
```

- Frontend: `http://localhost:5173`
- Backend: `http://localhost:5000`

```bash
# Build for production
npm run build
```

---

## 🔑 Environment Variables Reference

| Variable | Description |
|----------|-------------|
| `MONGO_URI` | MongoDB connection string |
| `GEMINI_API_KEY` | Google Gemini AI API key |
| `SESSION_SECRET` | Secret for express-session |
| `PORT` | Backend port (default: 5000) |

---

## 👩‍💻 Author

**Sonakshi Singla**
- GitHub: [@sonakshi2407](https://github.com/sonakshi2407)
- Email: [sonakshisingla105@gmail.com](mailto:sonakshisingla105@gmail.com)

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

⭐ **If this project helped you or you find it interesting, a star means a lot!**
