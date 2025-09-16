# Zomato Application (Food View)

A full-stack web application inspired by Zomato, allowing users to view, save, and like food reels, and food partners to manage their food listings. Built with Node.js/Express (backend) and React/Vite (frontend).

## Features

### User Side
- Register and login as a user
- View food reels and feeds
- Like and save food items
- Explore home and saved pages

### Food Partner Side
- Register and login as a food partner
- Create and manage food listings
- View profile and food items

## Tech Stack
- **Frontend:** React, Vite
- **Backend:** Node.js, Express
- **Database:** (Add your DB, e.g., MongoDB)

## Project Structure
```
backend/
  src/
    controllers/      # Route controllers
    db/               # Database connection
    middlewares/      # Express middlewares
    models/           # Mongoose models
    routes/           # API routes
    services/         # Utility services
frontend/
  src/
    components/       # Reusable UI components
    pages/            # Page views
    routes/           # Frontend routing
    styles/           # CSS files
vdeos/                # Sample video files
```

## Getting Started

### Backend
1. Navigate to the backend folder:
   ```powershell
   cd backend
   ```
2. Install dependencies:
   ```powershell
   npm install
   ```
3. Start the server:
   ```powershell
   node server.js
   ```

### Frontend
1. Navigate to the frontend folder:
   ```powershell
   cd frontend
   ```
2. Install dependencies:
   ```powershell
   npm install
   ```
3. Start the development server:
   ```powershell
   npm run dev
   ```

## Usage
- Access the frontend at `http://localhost:5173` (default Vite port)
- Backend runs on `http://localhost:3000` (default Express port)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](LICENSE)

---
*Replace database info and add environment setup as needed.*
