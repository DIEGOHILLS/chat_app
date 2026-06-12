# Real-Time Chat Application

A full-stack messaging platform built with the MERN stack and Socket.io. This application features real-time bidirectional communication, secure JWT-based authentication, and live online status indicators.

 **[Live Demo](https://chattabox-swcj.onrender.com/)**

---

## Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | React, TailwindCSS, Daisy UI |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **Real-Time** | Socket.io |
| **State Management** | Zustand |
| **Authentication** | JWT (JSON Web Tokens) |

---

##  Key Features

* **Real-Time Messaging** — Instant, bidirectional communication powered by Socket.io with zero page reloads. Tested thoroughly across multiple concurrent user sessions.
* **JWT Authentication & Authorization** — Secure user access with token-based authentication, protected routes, and session validation enforced on both the client and server.
* **Live Online Status** — Real-time user presence tracking using Socket.io rooms and Zustand for global state synchronization.
* **Global State Management** — Clean and efficient client-side state handling with Zustand, ensuring consistent UI behavior across chat threads and user lists.
* **Robust Error Handling** — Implemented comprehensive error boundaries on the frontend and centralized error-handling middleware on the backend for graceful failure states and easier debugging.

---

##  What I Learned

Building this application deepened my understanding of **WebSocket event-driven architecture** and the nuances of maintaining consistent state across distributed clients. I also gained practical experience managing the **JWT token lifecycle** (including storage and expiration) and mastering the separation of authentication concerns between frontend routing and backend middleware.

---

##  Getting Started

### Prerequisites
* **Node.js** v18+
* **MongoDB** instance (Local or MongoDB Atlas)

### 1. Clone the Repository
```bash
git clone [https://github.com/DIEGOHILLS/your-repo-name.git](https://github.com/DIEGOHILLS/your-repo-name.git)
cd your-repo-name
