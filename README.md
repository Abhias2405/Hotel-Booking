<div align="center">
  <br />
  <div>
    <img src="https://img.shields.io/badge/-React-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react" />
    <img src="https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logoColor=white&logo=mongodb&color=47A248" alt="mongodb" />
    <img src="https://img.shields.io/badge/-Express-black?style=for-the-badge&logoColor=white&logo=express&color=000000" alt="express" />
    <img src="https://img.shields.io/badge/-Node.js-black?style=for-the-badge&logoColor=white&logo=nodedotjs&color=339933" alt="nodejs" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
  </div>
  <h3 align="center">MERN Stack Hotel Booking Application</h3>
   <div align="center">
     A full-stack hotel booking platform with secure payments and image management
    </div>
</div>

## 📋 Table of Contents
1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🧪 [Testing](#testing)
6. 🚀 [Deployment](#deployment)

## <a name="introduction">🤖 Introduction</a>
A comprehensive hotel booking platform built using the MERN stack (MongoDB, Express.js, React, Node.js). The application features secure user authentication, real-time booking management, image uploads via Cloudinary, and secure payment processing through Stripe.

## <a name="tech-stack">⚙️ Tech Stack</a>
### Frontend
- React with TypeScript
- Tailwind CSS for styling
- React Query for state management
- React Hook Form for form handling

### Backend
- Node.js & Express.js
- MongoDB with Mongoose
- TypeScript
- JWT for authentication
- Express Validator

### Testing & DevOps
- Playwright for E2E testing
- Render.com for deployment
- Cloudinary for image management
- Stripe for payment processing

## <a name="features">🔋 Features</a>
👉 **User Authentication**: Secure signup/login with JWT  
👉 **Hotel Management**: Complete CRUD operations for hotel listings  
👉 **Image Handling**: Cloudinary integration for hotel images  
👉 **Booking System**: Real-time availability checking and booking  
👉 **Payment Processing**: Secure payments via Stripe  
👉 **Search & Filter**: Advanced hotel search functionality  
👉 **Responsive Design**: Mobile-first approach with Tailwind CSS  
👉 **E2E Testing**: Comprehensive test coverage with Playwright

## <a name="quick-start">🤸 Quick Start</a>

### Prerequisites
- Node.js
- MongoDB Atlas account
- Cloudinary account
- Stripe account

### Installation

1. **Clone Repository**
```bash
git clone https://github.com/Abhias2405/Hotel-Booking
cd Hotel-Booking
```

2. **Backend Setup**
```bash
cd backend
npm install
# Configure .env file with MongoDB, Cloudinary, and Stripe credentials
npm run dev
```

3. **Frontend Setup**
```bash
cd frontend
npm install
# Configure .env file with API URLs and Stripe public key
npm run dev
```

## <a name="testing">🧪 Testing</a>
```bash
cd e2e-tests
npm install
npx playwright install
npm run test
```

## <a name="deployment">🚀 Deployment</a>
The application is deployed on Render.com with the following setup:
- Frontend: Static site hosting
- Backend: Web service
- Database: MongoDB Atlas
- Assets: Cloudinary CDN

## 🔒 Environment Variables

### Backend
```plaintext
MONGODB_CONNECTION_STRING=
JWT_SECRET_KEY=
FRONTEND_URL=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
STRIPE_API_KEY=
```

### Frontend
```plaintext
VITE_API_BASE_URL=
VITE_STRIPE_PUB_KEY=
```
