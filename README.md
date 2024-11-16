# Haven Heights Real Estate

Haven Heights Real Estate is a comprehensive real estate web application built using the MERN stack. It allows users to explore, list, and manage properties seamlessly.

## Features
- **Property Listings**: View detailed property information, including images, price, and description.
- **Search and Filter**: Find properties based on location, price range, and other filters.
- **User Authentication**: Secure login and registration for users.
- **Admin Dashboard**: Manage property listings and user activities.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Project Structure
```bash
Haven-Heights-Real-Estate/
├── api/          # Backend code (Node.js, Express.js)
└── client/       # Frontend code (React.js)

Backend (API)
Built with Node.js and Express.js.
Database: MongoDB for storing property and user data.
Features:
User authentication with JWT.
CRUD operations for property listings.
Secure API endpoints.
Frontend (Client)
Built with React.js.
State management using Redux.
Styled with CSS and Bootstrap for a professional look.
Features:
Property search and filtering.
User-friendly interface for property exploration.
Dynamic routing using React Router.
Installation and Setup
Prerequisites
Node.js and npm installed
MongoDB server running locally or in the cloud
Steps
Clone the repository:

bash
Copy code
git clone https://github.com/Prudhviganesh09/Haven-Heights-Real-Estate.git
Set up the backend:

bash
Copy code
cd Haven-Heights-Real-Estate/api
npm install
npm start
Set up the frontend:

bash
Copy code
cd ../client
npm install
npm run dev
Environment Variables
Create a .env file in the api directory with the following keys:

bash
Copy code
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Technologies Used
bash
Copy code
Frontend: React.js, Redux, Bootstrap
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JWT
