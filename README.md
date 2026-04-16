🚀 Talent-Q – Group Coding Interview Platform

A full-stack MERN-based real-time coding interview platform that enables users to collaborate through video calls, live chat, and code execution in a shared environment.

🌟 Features
🔐 Authentication (Clerk)
Secure and scalable user authentication using Clerk
Supports session management and protected routes
🎥 Real-Time Video Calls
Powered by Stream Video SDK
Smooth group video communication
💬 Live Chat
Real-time messaging using Stream Chat
💻 Online Code Editor
Monaco Editor integration
Multi-language code execution using Judge0 API
👥 Group Interview Rooms
Multiple users can join and collaborate simultaneously
⚡ Modern UI
Built with Tailwind CSS + DaisyUI
Responsive and clean design
🛠️ Tech Stack
🔹 Frontend
React 19 (Vite)
Tailwind CSS + DaisyUI
React Query (TanStack)
Monaco Editor
Stream Video & Chat SDK
Clerk React SDK
🔹 Backend
Node.js
Express.js
MongoDB (Mongoose)
Clerk Backend SDK
Stream Node SDK
🔹 APIs & Services
Clerk → Authentication
Stream → Video Calls & Chat
Judge0 → Code Execution
📂 Project Structure
TALENT-Q/
│
├── Backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── lib/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   └── server.js
│   ├── .env
│   └── package.json
│
├── FrontEnd/
│   ├── src/
│   │   ├── api/
│   │   ├── components/
│   │   ├── data/
│   │   ├── hooks/
│   │   ├── lib/
│   │   │   ├── axios.js
│   │   │   ├── judge.js
│   │   │   ├── stream.js
│   │   │   └── utils.js
│   │   ├── Pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── .env
│   └── package.json
│
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/talent-q.git
cd talent-q
2️⃣ Install Dependencies
Backend
cd Backend
npm install
Frontend
cd FrontEnd
npm install
🔑 Environment Variables
📌 Backend .env
PORT=5000
MONGO_URI=your_mongodb_uri

CLERK_SECRET_KEY=your_clerk_secret
STREAM_API_KEY=your_stream_api_key
STREAM_SECRET=your_stream_secret
📌 Frontend .env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
VITE_STREAM_API_KEY=your_stream_key
VITE_BACKEND_URL=http://localhost:5000
▶️ Running the Project
Start Backend
cd Backend
npm run dev
Start Frontend
cd FrontEnd
npm run dev
🔄 Application Flow
User logs in using Clerk Authentication
Creates or joins an interview room
Initializes:
🎥 Video call (Stream)
💬 Chat system
Writes code in Monaco Editor
Code is sent to Judge0 API
Output is returned and displayed instantly
📸 Key Modules
middleware/ → Auth protection & request validation
controllers/ → Business logic
routes/ → API endpoints
lib/ → External integrations (Stream, Judge0, Axios)
components/ → Reusable UI elements
hooks/ → Custom React hooks
🚀 Future Enhancements
🔄 Real-time collaborative coding (like Google Docs)
🎯 Interview recording & playback
🤖 AI-based code feedback
📊 Performance analytics dashboard
🧑‍💼 Interview scheduling system
🤝 Contributing

Contributions are welcome!

# Fork the repo
# Create a feature branch
git checkout -b feature-name

# Commit changes
git commit -m "Added new feature"

# Push
git push origin feature-name

👨‍💻 Author

Suman Ranjan
