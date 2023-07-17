# Secrets
This repository contains a simple user authentication application built to explore authentication concepts. 
The application allows users to register, login, and authenticate either by connecting to a local MongoDB database or by registering using their Google accounts. 
The primary technologies utilized in this project include Passport for authentication.
It was created as part of the "Complete 2023 Web Development Bootcamp" by Angela Yu.

## Features
- User Registration: Users can create new accounts by providing their desired username, email, and password.
- User Login: Registered users can log in using their credentials to access the application.
- Local Database Authentication: User information is securely stored and authenticated against a local MongoDB database.
- Google Authentication: Users have the option to register and log in using their Google accounts for a seamless authentication experience.
- Security: Passwords are securely hashed and stored in the database to ensure user account security.

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Passport.js (Local and Google strategies)
- HTML
- CSS
- JavaScript
  
## Prerequisites

Before setting up and using this project, ensure that you have the following installed:

- [Node.js](https://nodejs.org/en)
- [MongoDB](https://www.mongodb.com/try/download/community)

## Installation

1. Clone the repository to your local machine:
```bash
git clone https://github.com/tristantanjh/Secrets.git
```
2. Navigate to the project directory:
```bash
cd Secrets
```
3. Install the dependencies:
```bash
npm install
```
4. Install Nodemon (if not already installed):
```bash
npm install -g nodemon
```

## Usage
1. Start the MongoDB server:
```bash
mongod
```
  
2. Start the Express server - Runs on http://localhost:3000:
```bash
nodemon
```
