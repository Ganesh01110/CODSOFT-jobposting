# MERN Stack Job Posting Website

## Overview

This project is a MERN stack job posting website where employers can post job openings and job seekers can search and apply for jobs. The application includes features for user authentication, job listing, job detail viewing, job application, and dashboards for both employers and candidates.

## Features

- **Home Page**: Welcome message and featured job listings.
- **Job Listings Page**: List of job openings with essential details.
- **Job Detail Page**: Detailed information about a specific job.
- **Employer Dashboard**: Account management and job posting.
- **Candidate Dashboard**: Profile management and job applications.
- **Job Application Process**: Application form with resume upload.
- **Search Functionality**: Search bar for finding specific jobs.
- **Email Notifications**: Notifications for successful applications and updates.
- **User Authentication and Security**: Secure user login and data protection.
- **Mobile Responsiveness**: Website works well on different devices.

## Technologies Used

### Server

- Node.js
- Express
- MongoDB (or PostgreSQL)

### Client

- React
- Redux Toolkit
- Axios
- Cloudinary

### Server Dependencies

```json
{
  "bcryptjs": "^2.4.3",
  "body-parser": "^1.20.2",
  "cors": "^2.8.5",
  "dotenv": "^16.3.1",
  "express": "^4.18.2",
  "express-async-errors": "^3.1.1",
  "express-mongo-sanitize": "^2.2.0",
  "express-rate-limit": "^7.1.4",
  "jsonwebtoken": "^9.0.2",
  "mongoose": "^8.0.0",
  "morgan": "^1.10.0",
  "nodemon": "^3.0.1",
  "validator": "^13.11.0",
  "xss-clean": "^0.1.4"
}
```

### Client Dependencies

```json
{
  "@headlessui/react": "^1.7.17",
  "@reduxjs/toolkit": "^1.9.7",
  "axios": "^1.6.1",
  "cloudinary": "^1.41.0",
  "react": "^18.2.0",
  "react-dom": "^18.2.0",
  "react-hook-form": "^7.48.2",
  "react-icons": "^4.11.0",
  "react-moment": "^1.1.3",
  "react-redux": "^8.1.3",
  "react-router-dom": "^6.18.0"
}
```

## Getting Started

### Prerequisites

- Node.js
- MongoDB or PostgreSQL

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Ganesh01110/CODSOFT-jobposting.git
    cd CODSOFT-jobposting
    ```

2. Install server dependencies:
    ```sh
    cd server
    npm install
    ```

3. Install client dependencies:
    ```sh
    cd client
    npm install
    ```

4. Create a `.env` file in the server directory with the following environment variables:
    ```env
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_api_secret
    ```

### Running the Application

1. Start the server:
    ```sh
    cd server
    npm run dev
    ```

2. Start the client:
    ```sh
    cd client
    npm start
    ```

3. Open your browser and navigate to `http://localhost:3000`.

## Folder Structure

```
mern-job-posting-website/
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   ├── utils/
│   ├── .env
│   ├── server.js
│   └── ...
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   ├── App.js
│   │   └── ...
│   ├── .env
│   └── ...
│
├── README.md
└── package.json
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

- [Ganesh Sahu](https://github.com/Ganesh01110)
- Email: ganesh0108@gmail.com

---

Feel free to customize this README file further based on your specific project requirements and additional information.
