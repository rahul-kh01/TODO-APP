Sure, here's the rewritten version with the same structure and code:

---

# Fullstack Project TODO app (MERN)

# Overview
The Cloud-Based Project TODO app is a web application designed to enhance team task management. Utilizing the MERN stack (MongoDB, Express.js, React, and Node.js), this platform offers a user-friendly interface for efficient task assignment, tracking, and collaboration. It serves both administrators and regular users with features aimed at boosting productivity and organization.

### Why/Problem?
In a dynamic work environment, effective task management is essential for team success. Traditional methods like spreadsheets or manual systems can be cumbersome and error-prone. The Cloud-Based Project TODO app seeks to solve these issues by offering a centralized platform for task management, facilitating seamless collaboration and improved workflow efficiency.

### **Background**:
With the rise of remote work and distributed teams, there's a growing need for tools that support effective communication and task coordination. The Cloud-Based Project TODO app meets this need by leveraging modern web technologies to deliver an intuitive and responsive task management solution. The MERN stack ensures scalability, while Redux Toolkit, Headless UI, and Tailwind CSS enhance the user experience and performance.

## **Admin Features:**
1. **User Management:**
    - Create admin accounts.
    - Add and manage team members.

2. **Task Assignment:**
    - Assign tasks to individual or multiple users.
    - Update task details and status.

3. **Task Properties:**
    - Label tasks as todo, in progress, or completed.
    - Assign priority levels (high, medium, normal, low).
    - Add and manage sub-tasks.

4. **Asset Management:**
    - Upload task assets, such as images.

5. **User Account Control:**
    - Disable or activate user accounts.
    - Permanently delete or trash tasks.

## **User Features:**
1. **Task Interaction:**
    - Change task status (in progress or completed).
    - View detailed task information.

2. **Communication:**
    - Add comments or chat to task activities.

## **General Features:**
1. **Authentication and Authorization:**
    - User login with secure authentication.
    - Role-based access control.

2. **Profile Management:**
    - Update user profiles.

3. **Password Management:**
    - Change passwords securely.

4. **Dashboard:**
    - Provide a summary of user activities.
    - Filter tasks into todo, in progress, or completed.

## **Technologies Used:**
- **Frontend:**
    - React (Vite)
    - Redux Toolkit for State Management
    - Headless UI
    - Tailwind CSS

- **Backend:**
    - Node.js with Express.js

- **Database:**
    - MongoDB for efficient and scalable data storage.

The Cloud-Based Project TODO app offers an innovative solution for task management within teams. By leveraging the MERN stack and modern frontend technologies, the platform provides a seamless experience for both administrators and users, fostering collaboration and productivity.

&nbsp;

## SETUP INSTRUCTIONS

# Server Setup

## Environment Variables
First, create the `.env` file in the server folder. The `.env` file should contain the following environment variables:

- MONGODB_URI = `your MongoDB URL`
- JWT_SECRET = `any secret key - must be secured`
- PORT = `8800` or any port number
- NODE_ENV = `development`

&nbsp;

## Set Up MongoDB:

1. Setting up MongoDB involves the following steps:
    - Visit MongoDB Atlas Website
        - Go to [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

    - Create an Account
    - Log in to your MongoDB Atlas account.
    - Create a New Cluster
    - Choose a Cloud Provider and Region
    - Configure Cluster Settings
    - Create Cluster
    - Wait for Cluster to Deploy
    - Create Database User
    - Set Up IP Whitelist
    - Connect to Cluster
    - Configure Your Application
    - Test the Connection

2. Create a new database and configure the `.env` file with the MongoDB connection URL.

## Steps to Run Server

1. Open the project in your preferred editor.
2. Navigate to the server directory with `cd server`.
3. Install the packages with `npm i` or `npm install`.
4. Start the server with `npm start`.

If configured correctly, you should see a message indicating that the server is running successfully and `Database Connected`.

&nbsp;

# Client Side Setup

## Environment Variables
First, create the `.env` file in the client folder. The `.env` file should contain the following environment variables:

- VITE_APP_BASE_URL = `http://localhost:8800` #Note: Change the port 8800 to your port number.
- VITE_APP_FIREBASE_API_KEY = `Firebase API key`

## Steps to Run Client

1. Navigate to the client directory with `cd client`.
2. Install the packages with `npm i` or `npm install`.
3. Run the app with `npm start` on `http://localhost:3000`.
4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

&nbsp;

