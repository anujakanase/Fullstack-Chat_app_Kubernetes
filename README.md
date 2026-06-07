# 🚀 Full Stack Chat Application on Kubernetes

A scalable real-time chat application built using the MERN stack, Docker, and Kubernetes. This project demonstrates cloud-native application deployment, real-time communication, containerization, and orchestration using modern DevOps practices.

---

## 📌 Project Overview

This application enables users to communicate in real time through a modern web interface. The architecture follows a microservice-oriented deployment model using Kubernetes.

### Architecture Flow

1. **User Interaction**

   * Users interact with the React frontend through their browser.
   * Actions include login, registration, sending messages, updating profiles, and viewing online users.

2. **Frontend (React App)**

   * Renders the user interface.
   * Handles user interactions.
   * Communicates with the backend using HTTP APIs and WebSocket connections.

3. **Backend (Node.js + Express + Socket.IO)**

   * Processes authentication and API requests.
   * Handles message storage and retrieval.
   * Manages real-time communication using Socket.IO.

4. **MongoDB**

   * Stores user information, chat messages, and application data.
   * Provides persistent storage for the application.

---

## 🏗️ Architecture Diagram

User Browser
↓
React Frontend
↓
Node.js + Express Backend
↓
Socket.IO (Real-Time Communication)
↓
MongoDB Database

Deployed using:

Docker → Kubernetes → AWS EC2

---

## ✨ Features

### 💬 Real-Time Messaging

* Instant message delivery using Socket.IO.
* Seamless real-time communication between users.

### 🔐 Authentication & Authorization

* Secure JWT-based authentication.
* Protected routes and user sessions.

### 👤 Profile Management

* Upload and update profile pictures.
* Manage user information.

### 🟢 Online Status Tracking

* Display active users in real time.
* Track online/offline presence.

### 🎨 Modern User Interface

* Responsive design using React and TailwindCSS.
* Beautiful components powered by DaisyUI.

### 🚀 Scalable Architecture

* Containerized using Docker.
* Orchestrated using Kubernetes.
* Suitable for cloud-native deployments.

---

## 🛠️ Technology Stack

### Frontend

* React.js
* TailwindCSS
* DaisyUI
* Zustand

### Backend

* Node.js
* Express.js
* Socket.IO

### Database

* MongoDB

### Authentication

* JSON Web Token (JWT)

### DevOps & Cloud

* Docker
* Kubernetes
* Nginx
* AWS EC2

---

## 🔧 Prerequisites

Before running the application, ensure you have:

* Node.js v14+
* Docker
* Kubernetes Cluster (Minikube, Kind, EKS, K3s, etc.)
* kubectl
* Git

---

## 📊 Kubernetes Components Used

* Deployments
* Services
* Namespaces
* Secrets
* Cluster Networking
* Pod Communication

---

## 🔍 Troubleshooting Experience

During deployment, I worked on resolving:

* CrashLoopBackOff issues
* ImagePullBackOff errors
* MongoDB service connectivity issues
* Kubernetes DNS and networking challenges
* Backend-to-database communication failures
* Container startup and configuration problems

---

## 📚 Learning Outcomes

This project helped me gain practical experience in:

* Docker containerization
* Kubernetes orchestration
* Service discovery
* Cloud-native architecture
* Production troubleshooting
* DevOps workflows
* Application deployment on AWS





LinkedIn:
(Add your LinkedIn profile URL here)
