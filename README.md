# Real-Time Chat Application

A real-time chat application built using the MERN stack, Socket.io, TailwindCSS, and Daisy UI. This project is designed to enhance my understanding of WebSockets and real-time communication.

## 🚀 Features

- 🌟 **Tech Stack:** MERN (MongoDB, Express.js, React, Node.js) + Socket.io + TailwindCSS + Daisy UI
- 🎃 **Authentication & Authorization:** Secure login and signup using JWT
- 👾 **Real-Time Messaging:** Instant communication powered by Socket.io
- 🔒 **Secure Backend:** User authentication and message encryption for privacy
- 🎨 **Modern UI:** Styled with TailwindCSS and Daisy UI for a clean and responsive experience

## 📦 Installation & Setup

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/realtime-chat-app.git]
   cd realtime-chat-app
   ```

2. Install dependencies:
   ```bash
   # Server
   cd backend
   npm install
   
   # Client
   cd frotnend
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the `server` directory and add the following:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

4. Start the development servers:
   ```bash
   # Start backend
   cd backend
   nodemon server.js
   
   # Start frontend
   cd frontend
   npm run dev
   ```

5. Open the application in your browser at `LOCALHOST / UR PORT`

## 🛠 Tech Stack

- **Frontend:** React, TailwindCSS, Daisy UI
- **Backend:** Node.js, Express.js, MongoDB
- **Real-Time:** Socket.io
- **Authentication:** JWT

## 📌 To-Do

- [ ] Add typing indicators
- [ ] Implement read receipts
- [ ] Implement groupchat feature

## 🤝 Contributing

Feel free to fork this repo and submit pull requests to improve the application!

## 📜 License

This project is licensed under the MIT License.

---



