# 💬 Real-Time Chat App

A full-stack chat application built with the **MERN** stack, featuring real-time messaging, authentication, and a modern UI.

## 🔧 Features

* 🌐 **Tech Stack**: MongoDB, Express, React, Node.js
* 🧠 **State Management**: Zustand for global state handling
* 💬 **Real-Time Communication**: Enabled via Socket.io
* 🔐 **Authentication**: JWT-based login and access control
* 👤 **Online User Tracking**: Shows which users are online in real time
* 🎨 **Styling**: TailwindCSS with Daisy UI components
* ⚠️ **Error Handling**: Implemented on both client and server sides
* 🚀 **Deployment**: Hosted on **Render**
* ☁️ **Media Uploads**: Integrated with Cloudinary

## 📁 Environment Configuration

Create a `.env` file in the backend directory and add:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret_key

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

## 🏗️ Build the App

```bash
npm run build
```

## ▶️ Start the App

```bash
npm start
```

## 📊 Architecture & Flow

![Architecture](/assets/architecture.png)

Architecture

![Flowchart](/assets/flowchart.png)

Flowchart
