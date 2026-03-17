<<<<<<< HEAD
# 🎨 AI Image Generator – Full Stack AI Art Sharing Platform

A **full-stack AI-powered web application** that allows users to generate images from text prompts and share them with a community.

This project demonstrates real-world integration of **AI (DALL·E), React, Node.js, MongoDB, and Cloudinary** to build a scalable, production-style application.

---

## 🚀 Features

* ✍️ **AI Image Generation (DALL·E)**

  * Generate images from text prompts using OpenAI API

* ☁️ **Cloudinary Image Storage**

  * Upload and store generated images securely in the cloud
  * Optimized image delivery and faster loading

* 🌐 **Full-Stack Architecture**

  * React frontend + Express backend

* 🧑‍🤝‍🧑 **Community Feed**

  * Browse images created by other users

* 📤 **Create & Share Posts**

  * Generate and publish AI images with name & prompt

* 🔍 **Search Functionality**

  * Search posts by prompt or username

* 💾 **MongoDB Database**

  * Stores post metadata (name, prompt, image URL)

* ⚡ **Responsive UI**

  * Built with Tailwind CSS

---

## 🛠 Tech Stack

### Frontend

* React (Vite)
* Tailwind CSS
* JavaScript

### Backend

* Node.js
* Express.js

### Database

* MongoDB (Mongoose)

### AI Integration

* OpenAI DALL·E API

### Media Storage

* Cloudinary

---

## 📂 Project Structure

```
AI-Image-Generation/
│── client/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Card.jsx
│   │   │   ├── FormField.jsx
│   │   │   ├── Loader.jsx
│   │   │
│   │   ├── page/
│   │   │   ├── Home.jsx
│   │   │   ├── CreatePost.jsx
│   │   │
│   │   ├── utils/
│   │   └── assets/
│   │
│   │── App.jsx
│   │── main.jsx
│
│── server/
│   ├── routes/
│   │   ├── dalleRoutes.js
│   │   ├── postRoutes.js
│   │
│   ├── mongodb/
│   │   ├── connect.js
│   │   └── models/post.js
│   │
│   ├── cloudinary/
│   │   └── config.js          # Cloudinary setup
│   │
│   └── index.js
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/ai-image-generator.git
cd AI-Image-Generation
```

---

### 2. Setup Backend

```bash
cd server
npm install
```

Create a `.env` file in `/server`:

```env
OPENAI_API_KEY=your_openai_api_key
MONGODB_URL=your_mongodb_connection_string

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Run backend:

```bash
npm start
```

---

### 3. Setup Frontend

```bash
cd client
npm install
npm run dev
```

App runs at:

```
http://localhost:5173
```

---

## 🧠 How It Works

1. User enters a prompt in **Create Post**
2. Frontend sends request → `/api/v1/dalle`
3. Backend calls **OpenAI API**
4. Image is generated (base64 format)
5. Image is uploaded to **Cloudinary**
6. Cloudinary returns a hosted image URL
7. Post (name + prompt + image URL) is stored in **MongoDB**
8. Home page fetches and displays all posts

---

## 📸 Screenshots

### 🏠 Community Feed

![Homepage](./screenshots/homepage.png)

### ✍️ Create Post Page

![Prompt Input](./screenshots/prompt.png)

### 🎨 Generated Image

![Generated Output](./screenshots/output.png)

---

## ✨ Example Generation

**Prompt:**

> "A futuristic cyberpunk city with neon lights"

**Output:**
![Example](./screenshots/example.png)

---

## ⚠️ Limitations

* API latency may affect generation speed
* Requires OpenAI API key
* Free-tier limits (OpenAI & Cloudinary)

---

## 🔮 Future Enhancements

* ❤️ Like & comment system
* 📥 Download images
* 🔐 User authentication
* 📊 Analytics dashboard
* 📱 Mobile optimization

---

## 💡 What This Project Demonstrates

* Full-stack development (React + Node + MongoDB)
* AI integration (OpenAI)
* Cloud storage handling (Cloudinary)
* REST API design
* Real-world scalable architecture

---

## 👨‍💻 Author

Aryan Saraogi
B.Tech CSE | Software Developer

---

## ⭐ Support

If you like this project:

* Give it a ⭐ on GitHub
* Share it
* Contribute 🚀
=======

>>>>>>> f221cd20d0e925fa7f86a0756a111cd19c76774d
