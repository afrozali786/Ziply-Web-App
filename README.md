# ZIPLY - Restaurant Ordering Platform

A comprehensive restaurant ordering platform that connects customers, vendors, and delivery personnel.

## Features

- Multi-role authentication (Customer, Vendor, Delivery)
- Real-time order tracking
- Vendor dashboard for inventory management
- Customer ordering system
- Delivery tracking system
- Location-based services
- Profile management
- Search functionality
- Responsive design with red color scheme

## Tech Stack

- Frontend: React (Vite)
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT
- Real-time updates: Socket.io

## Project Structure

```
ziply/
├── client/             # Frontend React application
├── server/             # Backend Node.js application
└── README.md
```

## Setup Instructions

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Backend Setup
1. Navigate to server directory:
   ```bash
   cd server
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create .env file with required environment variables
4. Start the server:
   ```bash
   npm run dev
   ```

### Frontend Setup
1. Navigate to client directory:
   ```bash
   cd client
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Environment Variables

Create a .env file in the server directory with the following variables:

```
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request "# Bulk-order-project" 
"# bulk" 
