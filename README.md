# Matcha - 42 School Education Project

Matcha is an exciting educational project developed as part of the 42 School curriculum. This README will guide you through the project, its features, technologies used, and how to get started.

## Project Description

Matcha is a dating application that brings together people with similar interests. It allows users to create profiles, search for potential matches based on various criteria, and interact with each other. This project emphasizes the use of a wide range of technologies, including MySQL for database management, Node.js for server-side scripting, and React.js for the frontend.

For detailed project specifications and requirements, please refer to the [Matcha Project Subject](https://cdn.intra.42.fr/pdf/pdf/88549/en.subject.pdf).

## Features

Matcha comes with a variety of features to enhance the user experience:

- **User Authentication**: Secure user registration and login.
- **User Profile**: Users can create and edit their profiles, including personal information, interests, and profile pictures.
- **Matching Algorithm**: Matcha uses a matching algorithm to suggest potential matches based on user preferences, such as age, location, and interests.
- **Real-Time Notifications**: Users receive real-time notifications when they receive likes or messages from other users.
- **Chat System**: Users can chat with their matches in real-time through a built-in chat system.
- **Geolocation**: Matcha utilizes geolocation to help users find matches in their vicinity.
- **Report and Block**: Users can report and block other users for inappropriate behavior.
- **History of Interactions**: Users can see a history of their interactions with other users, including likes and messages.

## Technologies Used

- **MySQL**: Used for database management.
- **Node.js**: The server-side scripting language.
- **Express.js**: A web application framework for Node.js.
- **React.js**: The frontend library for building user interfaces.
- **Socket.io**: For real-time communication.
- **HTML/CSS**: For styling and structuring the frontend.
- **Geolocation API**: Utilized for location-based features.
- **RESTful API**: Used for handling requests and responses.

## Getting Started

To get started with the Matcha project, follow these steps:

1. Clone the Matcha repository to your local machine.

```bash
git clone https://github.com/oboualla/MatchaV.git
```

2. Install the necessary dependencies for the server and client.

```bash
cd MatchaV/backend
npm install

cd ../matcha
npm install
```

3. Create a `.env` file in the `backend` directory to store your environment variables, including database credentials, and any other sensitive information.

4. Set up your MySQL database according to the project requirements outlined in the subject.

5. Start the server and client:

```bash
# In the backend directory (server)
npm start

# In the matcha directory (client)
npm start
```

6. Access the Matcha application in your web browser at `http://localhost:3000`.

---

Thank you for checking out the Matcha project! If you have any questions or need further assistance.

**Happy coding!**
