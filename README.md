# CodeFusion



A real-time collaborative coding platform where teams can code together, compile programs, communicate via chat, video/audio calls, and annotate on a shared whiteboard.

---

## Features

- Realtime synced code editor (single cursor).
- Online compiler, supports 7 languages (C++, Java, Python, JavaScript, Go, C, PHP).
- Synced whiteboard for annotation.
- Group video/audio call.
- Chat messaging.
- Code, input, and chat history persisted using MongoDB.

> ⚠ Make sure the app is running on **HTTPS** only and camera/microphone permissions are enabled for video/audio calls.

---

## Technology Stack

- **Frontend:** React, Redux  
- **Backend:** Node.js, Express  
- **Database:** MongoDB  
- **Realtime Communication:** Socket.io  
- **Other:** JavaScript  

---

## Installation

CodeFusion requires [Node.js](https://nodejs.org/) to run.  
Follow these steps:

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd codefusion
Install dependencies for both server and client:

bash
Copy
Edit
npm install
cd client
npm install
Set up environment variables (see below).

Start the server and client:

bash
Copy
Edit
# Server
npm start

# Client
cd client
npm start
## Environment Variables

| Key                   | Value / Description                                   |
|------------------------|-------------------------------------------------------|
| APP_CERTIFICATE        | Agora app certificate (generate in Agora dashboard)   |
| APP_ID                 | Agora app ID                                         |
| MONGO_URI              | MongoDB connection URI (Atlas or local)              |
| NODE_ENV               | `dev` or `prod`                                      |
| REACT_APP_AGORA_ID     | Agora app ID for frontend                            |
| REACT_APP_API_URL      | Backend server endpoint with port                    |
| REACT_APP_ENV          | `dev` or `prod`                                      |
| SKIP_PREFLIGHT_CHECK   | `true` to skip CRA preflight checks                  |


