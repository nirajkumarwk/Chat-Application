# Real-Time Chat Application

A real-time chat application built using **React, JavaScript, Tailwind CSS, Zustand, MongoDB, Express, and DaisyUI** for UI components.

## Features

* Real-time messaging
* User authentication (JWT-based)
* Cloud image upload (Cloudinary)
* Theme customization with DaisyUI
* State management with Zustand

## Technologies Used

* **Frontend**: React, Tailwind CSS, DaisyUI, Zustand
* **Backend**: Node.js, Express, MongoDB
* **Authentication**: JWT (JSON Web Tokens)
* **Cloud Storage**: Cloudinary

## Installation

### Prerequisites

Make sure you have the following installed:
* Node.js & npm
* MongoDB

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/real-time-chat-app.git
   cd real-time-chat-app

2. Install dependencies:
   ```bash
   npm install
   cd frontend && npm install
   cd backend && npm install

3. Setup the .env file in the root directory:
   ```bash
   PORT=5001
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   
4. Start the backend server:
   ```bash
   npm run dev

5. Start the frontend:
   ```bash
   npm run dev

6. Open the application in your browser:
   ```bash
   http://localhost:5173
   
