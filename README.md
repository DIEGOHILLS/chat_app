# Real-Time Chat Application

A full-stack messaging platform built with the MERN stack and Socket.io, featuring
real-time bidirectional communication, JWT-based authentication, and live online
status indicators.

**Live Demo:** (https://chattabox-swcj.onrender.com/)
---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React, TailwindCSS, Daisy UI |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Real-Time | Socket.io |
| State Management | Zustand |
| Authentication | JWT |

---

## Key Features

- **Real-Time Messaging** — Instant bidirectional communication via Socket.io with
  no page reloads, tested across multiple concurrent user sessions.

- **JWT Authentication & Authorization** — Secure user access with token-based auth,
  protected routes, and session validation on both client and server.

- **Live Online Status** — Real-time user presence tracking using Socket.io rooms
  and React Context for global state synchronization.

- **Global State Management** — Efficient client-side state handling with Zustand,
  ensuring consistent UI behavior across chat threads and user lists.

- **Error Handling** — Comprehensive error boundaries on the frontend and centralized
  error middleware on the backend for robust debugging and user feedback.

---


---

## What I Learned

Building this application deepened my understanding of **WebSocket event-driven
architecture** and the challenges of maintaining consistent state across
distributed clients. I also gained practical experience with **JWT token lifecycle
management** and the importance of separating authentication concerns between
frontend routing and backend middleware.

---

## Getting Started

### Prerequisites
- Node.js v18+
- MongoDB instance (local or Atlas)

### Environment Variables
Create a `.env` file in the server directory:

```env
PORT=5000
MONGO_DB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
NODE_ENV=development

# Clone the repository
git clone https://github.com/DIEGOHILLS/your-repo-name.git

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install

# Build and start
npm run build
npm start
