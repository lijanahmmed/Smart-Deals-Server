# Smart Deals Server

**Smart Deals Server** is the backend API for the Smart Deals application.  
It handles secure authentication, deal management, user operations, and seamless communication with the MongoDB database.  
Built using **Node.js**, **Express.js**, and **MongoDB**, this server powers all core backend functionalities of the Smart Deals platform.

---

## Features

- **User Authentication & Authorization**
- **CRUD Operations for Deals**
- **Secure API Endpoints**
- **MongoDB Database Integration**
- **Error Handling & Data Validation**
- **CORS Enabled for Client Communication**
- **Environment Variable Configuration**

---

## Technologies Used

- **Node.js**
- **Express.js**
- **MongoDB**
- **dotenv**
- **cors**

---

## Dependencies

```json
"dependencies": {
    "cors": "^2.8.5",
    "dotenv": "^17.2.3",
    "express": "^5.1.0",
    "firebase-admin": "^13.5.0",
    "jsonwebtoken": "^9.0.2",
    "mongodb": "^6.20.0",
    "nodemon": "^3.1.10"
  }
```

## Links

- **Client Repository:**
  https://github.com/lijanahmmed/Smart-Deals-Client

---

## Clone the Repository

Use the following command to clone the project:

```bash
git clone https://github.com/lijanahmmed/Smart-Deals-Server.git

cd Smart-Deals-Server
```

### Install Dependencies

```bash
cd Smart-Deals-Server
npm install

```

### Start Backend

```bash
nodemon index.js
```
