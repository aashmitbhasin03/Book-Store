# Book Store Application

This is a full-stack Book Store application with a React frontend and a Node.js/Express backend. The app allows users to create, view, update, and delete books from a database.

## Project Structure

```
client/   # React frontend
server/   # Node.js/Express backend
```

---

## Features
- List all books
- View details of a single book
- Add a new book
- Update book details
- Delete a book

---

## Tech Stack

### Frontend (client)
- React
- Vite
- Tailwind CSS

### Backend (server)
- Node.js
- Express.js
- MongoDB (via Mongoose)

---

## Getting Started

### Prerequisites
- Node.js (v16 or above)
- npm or yarn
- MongoDB (local or cloud)

### Setup Instructions

#### 1. Clone the repository
```sh
git clone <repo-url>
cd Book_Store
```

#### 2. Install dependencies

##### Frontend
```sh
cd client
npm install
```

##### Backend
```sh
cd ../server
npm install
```

#### 3. Configure Environment Variables
- Create a `.env` file in the `server/` directory with your MongoDB connection string:
  ```env
  MONGODB_URI=<your-mongodb-uri>
  PORT=5000
  ```

#### 4. Run the Application

##### Start the backend server
```sh
cd server
npm start
```

##### Start the frontend
```sh
cd client
npm run dev
```

- The frontend will typically run on `http://localhost:5173`
- The backend will run on `http://localhost:5000`

---

## Folder Structure

### client/
- `src/components/` - Reusable React components
- `src/pages/` - Page components for routing
- `src/assets/` - Static assets

### server/
- `controllers/` - Express route controllers
- `models/` - Mongoose models
- `routes/` - Express routes
- `middlewares/` - Custom middleware
- `utils/` - Utility functions
- `connection/` - Database connection

---

## License

This project is licensed under the MIT License.
