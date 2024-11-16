# Haven Heights Real Estate

Haven Heights Real Estate is a comprehensive real estate web application built using the MERN stack. It allows users to explore, list, and manage properties seamlessly.

## Features
- **Property Listings**: View detailed property information, including images, price, and description.
- **Search and Filter**: Find properties based on location, price range, and other filters.
- **User Authentication**: Secure login and registration for users.
- **Admin Dashboard**: Manage property listings and user activities.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Project Structure
Haven-Heights-Real-Estate/ ├── api/ # Backend code (Node.js, Express.js) └── client/ # Frontend code (React.js)

### Backend (API)
- Built with **Node.js** and **Express.js**.
- Database: **MongoDB** for storing property and user data.
- Features:
  - User authentication with JWT.
  - CRUD operations for property listings.
  - Secure API endpoints.

### Frontend (Client)
- Built with **React.js**.
- State management using **Redux**.
- Styled with **CSS** and **Bootstrap** for a professional look.
- Features:
  - Property search and filtering.
  - User-friendly interface for property exploration.
  - Dynamic routing using React Router.

## Installation and Setup

### Prerequisites
- Node.js and npm installed
- MongoDB server running locally or in the cloud

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Prudhviganesh09/Haven-Heights-Real-Estate.git
Navigate to the backend directory and install dependencies:
bash
cd Haven-Heights-Real-Estate/api
npm install
Start the backend server:
bash
npm start
Navigate to the frontend directory and install dependencies:
bash
cd ../client
npm install
Start the frontend development server:
bash
npm run dev
Environment Variables
Create a .env file in the api directory with the following keys:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Technologies Used
Frontend: React.js, Redux, Bootstrap
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JWT

Author
Prudhvi Ganesh
