﻿# MERN Project: eHospitCare

This project is a web application built using the MERN stack (MongoDB, Express, React, Node.js). The repository contains two main folders:

- `client`: Frontend built with React
- `backend`: Backend API built with Node.js and Express

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16.x or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [MongoDB](https://www.mongodb.com/) (local or cloud instance)
- Git

---

## How to Clone and Run This Project

### Step 1: Clone the Repository

1. Open your terminal and navigate to the directory where you want to clone the project.
2. Run the following command:

```bash
git clone <repository-url>
```

Replace `<repository-url>` with the URL of this repository.

3. Navigate into the project folder:

```bash
cd <project-folder-name>
```

---

### Step 2: Set Up the Backend

1. Navigate to the `backend` folder:

```bash
cd backend
```

2. Install the required dependencies:

```bash
npm install
```

3. Set up environment variables:
   - Create a `.env` file in the `backend` folder.
   - Add the following variables:

```env
PORT=4000
MONGODB_URL=mongodb://localhost:27017/eHospitCare
JWT_SECRETE=THIS IS SECRETE
```

4. Start the backend server:

```bash
npm start
```

The backend server should now be running on `http://localhost:4000` (or the port you specified).

---

### Step 3: Set Up the Frontend

1. Navigate to the `client` folder:

```bash
cd ../client
```

2. Install the required dependencies:

```bash
npm install
```

3. Set up environment variables:
   - Create a `.env` file in the `backend` folder.
   - Add the following variables:

```env
PORT=4000
MONGODB_URL= {copy and paste mongodb compass url here}
JWT_SECRETE=THIS IS SECRETE
```


4. Start the frontend development server:

```bash
npm start
```

The frontend should now be running on `http://localhost:4000`.

---
ctrl+click the url from terminal to see it on browser

### Step 4: Access the Application

- Open your browser and navigate to `http://localhost:4000`.

---