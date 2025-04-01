# Fashion Store

A modern e-commerce platform for clothing and accessories, inspired by Bewakoof.com.

## Features

- User authentication and authorization
- Product browsing and searching
- Shopping cart functionality
- Order management
- Responsive design
- Admin dashboard

## Tech Stack

### Frontend
- React with TypeScript
- Tailwind CSS
- Redux Toolkit
- React Router
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Multer for file uploads

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
```

2. Install dependencies
```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Set up environment variables
Create a `.env` file in the backend directory with the following variables:
```
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=5000
```

4. Start the development servers
```bash
# Start backend server
cd backend
npm run dev

# Start frontend server
cd frontend
npm start
```

The application will be available at `http://localhost:3000`

## Project Structure

```
fashion-store/
├── frontend/           # React frontend application
├── backend/           # Node.js backend application
└── README.md
```

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request 
