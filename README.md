# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
# Tourist Booking Platform

## Project Overview
A full-stack web application for booking tourist packages with multiple tour guides.  
Users can browse tours, select guides, book packages securely, and track their bookings.  
The platform features responsive design, user authentication, and an admin dashboard for management.

## Live Project
🔗 [Live Demo](https://your-live-site-link.com)  
🔗 [GitHub Repository](https://github.com/your-username/your-repo-name)

## Screenshot
![Platform Screenshot](screenshot.png)  
*Replace `screenshot.png` with an actual clean screenshot image in the repo.*

## Technologies Used
- React.js  
- Tailwind CSS & DaisyUI  
- Firebase Authentication  
- Node.js & Express.js  
- MongoDB & Mongoose  
- React Hook Form  
- React Router DOM  
- Axios  
- Framer Motion  

## Core Features
- User registration and login with Firebase Authentication  
- Browse and search tour packages dynamically  
- Select tour guides and make bookings  
- Responsive UI with smooth animations  
- Protected routes and secure data access  
- Admin dashboard for managing tours, guides, and bookings  
- Real-time booking status updates  

## Dependencies
- react  
- react-dom  
- react-router-dom  
- tailwindcss  
- daisyui  
- firebase  
- axios  
- express  
- mongoose  
- react-hook-form  
- framer-motion  

## How to Run Locally

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git

   Navigate to project directory

bash
Copy
Edit
cd your-repo-name
Install frontend dependencies

bash
Copy
Edit
cd client
npm install
Install backend dependencies

bash
Copy
Edit
cd ../server
npm install
Setup environment variables

Create .env files in client and server folders with required keys (Firebase config, MongoDB URI, JWT secret, etc.)

Run frontend

bash
Copy
Edit
cd ../client
npm start
Run backend

bash
Copy
Edit
cd ../server
npm run dev
Open browser at

arduino
Copy
Edit
http://localhost:3000
