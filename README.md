# Notes App (MERN Stack)

A full-stack notes app where users can sign up, log in and manage their personal notes.

## Features
- User sign up and login with JWT authentication
- Add, edit and delete notes
- Pin / unpin important notes
- Search notes
- Tags for each note
- Protected routes (each user sees only their own notes)

## Tech Stack
- **Frontend:** React (Vite), Tailwind CSS, React Router, Axios
- **Backend:** Node.js, Express
- **Database:** MongoDB with Mongoose
- **Auth:** JSON Web Tokens (JWT)

## API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /create-account | Register a new user |
| POST | /login | Login user |
| GET | /get-users | Get logged-in user |
| POST | /add-note | Add a note |
| PUT | /edit-note/:noteId | Edit a note |
| GET | /get-all-notes | Get all notes |
| DELETE | /delete-note/:noteId | Delete a note |
| PUT | /update-note-pinned/:noteId | Pin / unpin a note |
| GET | /search-notes | Search notes |

## How to Run Locally

### 1. Clone the repo
```bash
git clone https://github.com/UmeshWakadkar/notes-app.git
cd notes-app
```

### 2. Backend
```bash
cd backend
npm install
```
Create a `.env` file in `backend` with your secret key (see `.env.example`), and make sure MongoDB is running locally.
```bash
npm start
```

### 3. Frontend
```bash
cd frontend/notes-app
npm install
npm run dev
```

Open the link shown in the terminal (usually http://localhost:5173).

## Author
**Umesh Wakadkar**
GitHub: [UmeshWakadkar](https://github.com/UmeshWakadkar)