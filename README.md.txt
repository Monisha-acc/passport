# Passport Automation System

A web-based Passport Automation System designed to streamline the passport application process. The system allows users to apply for a passport online, track their application status, and facilitates different roles like Applicant, Passport Admin, Regional Admin, and Police for seamless operations.

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MongoDB
- **Authentication**: JWT / Session-based (as implemented)
- **Environment**: Node.js, npm

## 📁 Project Structure

```
passport-automation-system/
├── models/              # MongoDB models (e.g., Application, User)
├── node_modules/        # Dependencies
├── .env                 # Environment variables
├── package.json         # Project metadata and dependencies
├── server.js            # Entry point for the backend server
├── server.html          # Main HTML page (or could be a UI template)
```

## 🚀 Features

- User registration and login
- Apply for a passport via online form
- Status tracking by various departments:
  - Regional Admin
  - Police
  - Passport Admin
- Role-based dashboards
- Admin functionalities for appointment and document verification

## 📦 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/passport-automation-system.git
   cd passport-automation-system
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root directory and define:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. **Run the app:**

   ```bash
   node server.js
   ```

5. **Open in browser:**

   Visit `http://localhost:5000` to access the application.

## 📷 Screenshots

*Add screenshots or UI walkthroughs if available.*

## ✍️ Authors

- Monisha ([@your-github-username](https://github.com/your-github-username))

## 📄 License

This project is licensed under the MIT License.
