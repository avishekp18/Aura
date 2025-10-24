# 🌐 Aura - Social Networking Platform (MERN + Next.js)

Welcome to **Aura**, a modern **social networking platform** built using the **MERN Stack + Next.js**.  
This project lets users connect, post, chat, and engage socially — just like a professional social media experience.

![Website Screenshot](./frontend/public/images/Aura.webp)

---

## 🚀 Live Demo

👉 **Live App:** [https://aura-frontend-orcin.vercel.app](https://aura-frontend-orcin.vercel.app)

---

## 📄 Description

**Aura** allows users to:

- Sign up or log in with **Google OAuth** or manual registration
- Post text and photo updates
- Like and comment on posts
- Send and receive **friend requests**
- Chat in **real time** with **Socket.io**
- Edit profiles, bios, and profile pictures
- Enjoy a smooth, responsive UI built with Tailwind CSS

---

## 🛠️ Tech Stack

### **Frontend**

- **Next.js** (React Framework)
- **React.js**
- **Redux Toolkit** (State Management)
- **Tailwind CSS**
- **Framer Motion**

### **Backend**

- **Node.js**
- **Express.js**
- **Socket.io** (Real-time messaging)

### **Database**

- **MongoDB Atlas**

### **Authentication**

- **NextAuth.js** (Google OAuth)
- **JWT** (JSON Web Tokens)

### **Cloud Storage**

- **Cloudinary**

### **Hosting**

- **Frontend:** Vercel
- **Backend:** Render

---

## 🔧 Features

- 🔐 Secure Authentication (Manual + Google OAuth)
- 📝 Post Creation, Editing, and Deletion
- ❤️ Like & 💬 Comment System
- 🧑‍🤝‍🧑 Friend Request Management
- 💬 Real-time Chat with Socket.io
- 🧾 Story Uploads (24-hour posts)
- 👤 Profile Customization (Bio, Profile Picture, Cover Image)
- 🪶 Smooth Animations and Modern UI

---

## 🖥️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/avishekp18/Aura.git

```

2️⃣ Install Dependencies

For both frontend and backend:

```bash
npm install

```

3️⃣ Environment Variables

Create a .env file inside the backend folder and include:

```bash
PORT=8080
MONGO_URI=<your-mongodb-atlas-uri>
CORS_ORIGIN=http://localhost:3000,https://aura-frontend-orcin.vercel.app
JWT_SECRET=<your-jwt-secret>

CLOUDINARY_CLOUD_NAME=<your-cloudinary-cloud-name>
CLOUDINARY_API_KEY=<your-api-key>
CLOUDINARY_API_SECRET=<your-api-secret>


```

3️⃣ Environment Variables

For the frontend .env.local:

```bash
NEXT_PUBLIC_BACKEND_API=https://aura-backend-y8n8.onrender.com
NEXT_PUBLIC_SOCKET_URL=https://aura-backend-y8n8.onrender.com
NEXTAUTH_URL=https://aura-frontend-orcin.vercel.app
NEXTAUTH_SECRET=<your-nextauth-secret>

GOOGLE_CLIENT_ID=<your-google-client-id>
GOOGLE_CLIENT_SECRET=<your-google-client-secret>

```

4️⃣ Run the Backend Project:

```bash
npm run dev

```

4️⃣ Run the Backend Project:

```bash
npm run dev
```

5️⃣ Access the App

Frontend: http://localhost:3000

Backend: http://localhost:8080

👨‍💻 Developer

Avishek Pradhan
🔗 [LinkedIn](https://www.linkedin.com/in/avishek-pradhan01/)

Feel free to explore, fork, and contribute! 🚀

🪶 Aura — Connect. Share. Chat.

---

Would you like me to make a **shorter version** (for your LinkedIn project post) — like 4–5 bullet points and one short paragraph for the caption?
