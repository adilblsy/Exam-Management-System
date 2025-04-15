# Internal Examination Management System

A web-based system developed as part of our B.Tech Mini Project at RIT Kottayam to simplify and automate internal exam management for the Department of Computer Science and Engineering.

## Features

- Question paper upload and scrutiny workflow  
- Real-time notification system via email  
- Role-based access for Head of Department (HOD), Exam Coordinator (EC), Assistant Exam Coordinator (AEC), Module Coordinator (MC), and Faculty  
- Automated seating arrangement generation  
- Manual but structured invigilation duty allocation  

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB with Mongoose  
- **APIs & Tools**:  
  - REST APIs  
  - JWT for authentication  
  - SMTP for email notifications  
- **Deployment**: Railway.app  

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/internal-exam-management.git
cd internal-exam-management
```

### 2. Install dependencies
```bash
npm install
```

### 3. Start the backend server
```bash
node server.js
```

### 4. Open the frontend
Open index.html in your browser to access the user interface.
Make sure MongoDB is running locally or update the connection URI in server.js.


## Project Report

You can view the full project report [here](./Report.pdf).


## License

This project is open-source and available under the MIT License.
