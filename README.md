# CRUD App

A full-stack CRUD (Create, Read, Update, Delete) application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). This application allows users to manage employee records efficiently.

## 🚀 Features

- Add new employees with details like name, email, and position.
- View a list of all employees.
- Edit existing employee information.
- Delete employee records.
- Responsive UI for seamless user experience.

## 🛠️ Tech Stack

- **Frontend**: React.js, Axios
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (via Mongoose)
- **Styling**: Tailwind CSS

## 📁 Project Structure

```
crud-app/
├── client/           # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── App.js
│       └── index.js
├── server/           # Express backend
│   ├── models/
│   ├── routes/
│   └── server.js
├── package.json
└── README.md
```

## ⚙️ Installation

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/aarish19/crud-app.git
   cd crud-app
   ```

2. **Set up the backend:**

   ```bash
   cd server
   npm install
   ```

3. **Set up the frontend:**

   ```bash
   cd ../client
   npm install
   ```

4. **Configure environment variables:**

   Create a `.env` file in the `server` directory and add your MongoDB connection string:

   ```
   MONGO_URI=your_mongodb_connection_string
   ```

5. **Run the application:**

   In the `server` directory:

   ```bash
   npm start
   ```

   In a new terminal, navigate to the `client` directory:

   ```bash
   npm start
   ```

   The frontend will be available at `http://localhost:3000` and the backend at `http://localhost:5000`.

## 📬 API Endpoints

| Method | Endpoint           | Description              |
|--------|--------------------|--------------------------|
| GET    | /api/employees     | Retrieve all employees   |
| POST   | /api/employees     | Add a new employee       |
| PUT    | /api/employees/:id | Update an employee       |
| DELETE | /api/employees/:id | Delete an employee       |

## 🖼️ Screenshots

(https://github.com/aarish19/crud-app/blob/main/Screenshot%202025-05-02%20021321.png)
https://github.com/aarish19/crud-app/blob/main/Screenshot%202025-05-02%20021359.png

## 📄 License

This project is licensed under the MIT License.

## 🙌 Acknowledgements

- [MongoDB](https://www.mongodb.com/)
- [Express.js](https://expressjs.com/)
- [React.js](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
