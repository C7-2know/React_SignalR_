# Real-Time Chat Application with ASP.NET Core Web API and React Frontend

Welcome to the **Real-Time Chat Application**, a cutting-edge communication platform built with an ASP.NET Core Web API backend and a React frontend. This project harnesses the power of **SignalR** to deliver real-time messaging and seamless communication for multiple users. Whether you're chatting in a group or joining a specific chat room, this app ensures a responsive and engaging user experience.


![Screenshot of Application](/ChatMessages.PNG "Application Screenshot")

## Technologies Used

### Backend
- **ASP.NET Core Web API**: The robust and scalable API serves as the backend for this real-time application, managing user connections and data flow.
- **SignalR**: A Microsoft library used for adding real-time functionality to web applications, enabling live communication between the server and connected clients.

### Frontend
- **React**: A powerful JavaScript library for building user interfaces, providing a responsive and dynamic frontend experience.

## How It Works

### Real-Time Messaging with SignalR
- **Joining the Chat**: When a user joins, they can connect to either a global chat or a specific group (chat room). The backend registers the connection and announces the user’s entry to all members.
- **Group-Specific Communication**: Users can join specific chat rooms where they can exchange messages exclusively with other members of that room.
- **Dynamic User Handling**: The app dynamically assigns colors to each user's messages for easy differentiation and timestamps every message to provide context.
  
## Credit
This project was inspired by and built following tutorials and guidance from [Mohamad Lawand]
## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org)
- [ASP.NET Core SDK](https://dotnet.microsoft.com/download)
- [React](https://reactjs.org)

