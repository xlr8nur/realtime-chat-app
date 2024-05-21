# Realtime Chat App

Realtime Chat App is a platform where users can chat with their friends in real time. The project is built using modern web technologies to ensure a seamless and responsive user experience.

## Table of Contents

- [Overview](#overview)
- [Technologies](#technologies)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

The Realtime Chat App allows users to have real-time conversations with their friends. The frontend is developed using React, TailwindCSS, and Zustand, while the backend utilizes Postman for API management, MongoDB for the database, and Socket.io for real-time communication.

## Technologies

### Frontend

- **React**
- **TailwindCSS**
- **Zustand**

### Backend

- **API**: Postman
- **Database**: MongoDB
- **Socket.io**: For real-time communication

## Features

- **Real-time Chat**: Users can send and receive messages in real-time.
- **User Authentication**: Secure login and signup functionality.
- **Friend List Management**: Users can add and remove friends.
- **Message History**: Users can view the chat history.

## Installation

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB setup

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/xlr8nur/realtime-chat-app.git
   cd realtime-chat-app
   ```

2. **Install frontend dependencies:**

   ```bash
   cd frontend
   npm install
   ```

3. **Install backend dependencies:**

   ```bash
   cd ../backend
   npm install
   ```

4. **Set up MongoDB:**

   - Ensure MongoDB is running and accessible.

5. **Configure environment variables:**

   Create a `.env` file in the backend directory and add your MongoDB connection string and other necessary environment variables.

6. **Run the backend server:**

   ```bash
   npm start
   ```

7. **Run the frontend development server:**

   ```bash
   cd ../frontend
   npm start
   ```

   The application will run on `http://localhost:3000`.

## Usage

Users can access the project by clicking this link: [Realtime Chat App](https://realtime-chat-app-1-veis.onrender.com).

1. **Sign Up / Sign In:**

   Users can sign up for a new account or sign in to an existing account.

2. **Add Friends:**

   Users can add friends to start chatting.

3. **Start Chatting:**

   Users can send and receive messages in real-time.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, please contact:

xlr8nur@protonmail.com
