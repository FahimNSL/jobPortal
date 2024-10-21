
# **Job Portal MERN Stack Project**

This **Job Portal** is a full-stack web application designed to connect **job seekers** with **employers**. Job seekers can register, search, and apply for jobs, while employers can post job listings and manage applications. The project is built using the **MERN stack** and provides a dynamic, responsive experience.

## **Features**

- **Job Seekers**:
  - Register and create a user profile
  - Browse and search for available jobs
  - Apply to job listings
  - Manage job applications
  
- **Employers**:
  - Register and create a company profile
  - Post job openings
  - Review and manage job applications
  
- **Admin** (optional for future implementation):
  - Manage users, jobs, and site content

## **Technologies Used**

### **Frontend**
- **React.js**: Building the UI with reusable components
- **JavaScript (ES6+)**: Logic handling and API integration
- **HTML5/CSS3**: Structuring and styling pages
- **React Router**: Client-side routing
- **Material-UI** (or Bootstrap): Pre-built components and UI design

### **Backend**
- **Node.js**: JavaScript runtime for building the server-side application
- **Express.js**: RESTful API and routing
- **MongoDB**: NoSQL database for storing user, job, and application data
- **Mongoose**: MongoDB Object Data Modeling (ODM) library
- **JWT (JSON Web Tokens)**: Authentication and authorization

### **Deployment**
- **Frontend**: Deployed on **Netlify**
- **Backend**: Deployed on **Render**
- **CORS**: Configured for secure cross-origin requests between frontend and backend

## **Installation**

### **Backend** (Node.js + Express + MongoDB)
1. Clone the repository:
    ```bash
    git clone https://github.com/FahimNSL/jobPortal.git
    ```
2. Navigate to the project directory:
    ```bash
    cd jobportal
    ```
    **Backend start:**
     ```bash
    cd backend
    npm install
    npm run dev
    ```

    **Frontend start:**
     ```bash
    cd frontend
    npm install
    npm run dev
    ```

3. Install dependencies:
    ```bash
    npm install
    ```
4. Create a `.env` file in the root directory and add the following environment variables:
    ```bash
    PORT=5000
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```
5. Start the backend server:
    ```bash
    npm start
    ```



## **Project Structure**

```
/backend
    /controllers   # Business logic for routes
    /models        # MongoDB models (User, Job, Application)
    /routes        # API endpoints (jobs, users, auth)
    server.js      # Entry point of the server
/frontend
    /src
        /components    # React components (JobList, Profile, etc.)
        /pages         # Page components (Home, Login, Register)
        /services      # API calls (Axios)
        App.js         # Main React App component
```

## **Usage**

- **Job Seekers** can:
  - Sign up and log in
  - Search for jobs by title, company, and location
  - Apply for jobs and track application status

- **Employers** can:
  - Register and log in
  - Post job listings
  - Manage applicants and job listings




