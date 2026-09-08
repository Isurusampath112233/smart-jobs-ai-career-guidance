

# Smart Jobs – AI-Based Job Recommendation & Career Guidance System

Smart Jobs is an AI-powered web application designed to help users discover suitable job opportunities, identify skill gaps, explore career pathways, and manage their job applications.

## Features

* 🔍 AI-based job recommendations
* 📊 Skill gap analysis
* 🧭 Career pathway guidance
* 📋 Job application tracking
* 👤 User profile management
* 📈 Personalized dashboard
* 🔐 User authentication
* 🌐 Responsive web interface

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6+)
* Bootstrap
* PHP
* MySQL
* MongoDB
* AI / NLP Concepts

## Requirements

Before running the project, make sure you have:

* A web server environment such as XAMPP
* PHP installed and configured
* MySQL database
* MongoDB connection
* A modern web browser
* **An active internet connection**

> **Important:** An internet connection is required for some features of the application because the project uses external resources and services.

## Environment Configuration

The project requires MongoDB configuration through environment variables.

Create or configure your `.env` file and add your MongoDB connection details.

Example:

```env
MONGODB_URI=your_mongodb_connection_string
```

Replace `your_mongodb_connection_string` with your actual MongoDB connection string.

> **Security:** Do not upload your `.env` file or expose your MongoDB connection string publicly on GitHub. Add `.env` to your `.gitignore` file.

Example `.gitignore` entry:

```gitignore
.env
```

## Installation & Setup

1. Clone or download the repository.

2. Place the project inside your web server directory, for example:

```text
xampp/htdocs/
```

3. Create the required MySQL database and import the provided database structure/data if included with the project.

4. Configure the MongoDB connection in the `.env` file.

5. Make sure your web server and MySQL services are running.

6. Ensure you have an active internet connection.

7. Open the project through your local web server.

Example:

```text
http://localhost/smart-jobs/
```

## Important Notes

* Do not share your MongoDB credentials or connection string publicly.
* Keep your `.env` file private.
* Make sure all required services are running before using the application.
* Some external resources/features may not function correctly without an internet connection.

## Project Purpose

This project was developed as a **Final Year Project** to explore the use of artificial intelligence and web technologies in career guidance and job recommendation systems.

## Author

**Isuru Sampath**



//installing npm 

cd backend
npm install
npm start


power shell  restart 


netstat -ano | findstr :5001  // finding the port - 5001

taskkill /PID 14736 /F // terminating the connection (14736 will change time to time )
