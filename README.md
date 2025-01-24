# Vet Clinic Appointment System
This repository is learning material for course Web Dev, COEAI, WU

![HTML](https://img.shields.io/badge/HTML-5-orange)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-1.9.6-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![NodeJS](https://img.shields.io/badge/NodeJS-14.15.1-green)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue)
![Express](https://img.shields.io/badge/Express-4.17.1-lightgrey)
![multer](https://img.shields.io/badge/multer-1.4.2-red)

## Overview
This project is a web-based application for managing appointments at a veterinary clinic. It includes functionalities for registering users, logging in and out, adding pets, and creating appointments. The application uses a MySQL database to store data about doctors, services, owners, pets, and appointments.

## Features
- User Registration
- User Login and Logout
- Add Pet Information
- Create Appointments
- View Appointments

## Data Structure
The application manages the following data:
- **Doctors**: Information about veterinary doctors.
- **Services**: Details of services offered by the clinic.
- **Owners**: Information about pet owners.
- **Pets**: Details of pets owned by the users.
- **Appointments**: Appointment details between pets and doctors.

## Technologies Used
- **Frontend**: JavaScript, HTML, TailwindCSS
- **Backend**: NodeJS, Express
- **Database**: MySQL
- **File Uploads**: multer

## Database Schema
The database schema is defined in the `db_schema.sql` file and includes the following tables:
- `owners`
- `doctors`
- `services`
- `pets`
- `appointments`

## Getting Started
### Prerequisites
- Node.js
- MySQL

### Initialize project
```
npm init -y
```

### Install dependencies
#### For your vet clinic project, you’ll need [express] for the server and [mysql] for database connectivity.
#### You may also want to use [body-parser] to parse incoming request bodies.
```npm install express mysql2 body-parser multer cors```

#### (Optional) Install nodemon for development
#### To make development easier, you can install [nodemon], which automatically restarts your server when file changes are detected
```
npm install --save-dev nodemon
```

#### Update package.json for nodemon
#### Manually edit package.json to include "dev" script
```
"scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js"
}
```

### Start server
```
npm run dev
```

## License
This project is licensed under the ISC License.

## Contributor
![Contributor](https://avatars.githubusercontent.com/mlkklkhl?s=100)
