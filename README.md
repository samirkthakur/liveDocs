> # Google Docs Clone
---
A Google Docs user interface clone built using JavaScript, Quill (for rich text editing), Mongoose (for MongoDB database management), and Socket.io (for real-time collaboration). This project mimics the functionality of Google Docs, enabling multiple users to edit the same document simultaneously.
---
> ## Table of Contents

- [Installation and Usage](#Installation-and-Usage)
- [Dependencies](#Dependencies)

> ## Installation and Usage

> ### Clone the Repository
Clone the project repository to your local machine.

```sh
Copy code
git clone https://github.com/yourusername/google-docs-clone.git
```
---
> ### Install Dependencies
---
> #### For Client:

```sh
cd google-docs-clone/client
npm install
```

This will install:
**Quill** (for rich text editing)
**Socket.io-client** (for real-time updates)
**react-router-dom** (for routing in React)

> #### For Server:

```sh
cd ../server
npm install
```

This will install:
**Mongoose** (for MongoDB database management)
**Socket.io** (for real-time communication)
**Nodemon** (for automatically restarting the server during development)
---
> ### Set Up MongoDB

Ensure that you have a MongoDB instance running (either locally or via a cloud provider like MongoDB Atlas). If using MongoDB Atlas (recommended for cloud solutions), create a cluster and get the MongoDB connection string. In the server folder, replace the connection-string in the server.js file.
---
> ### Running the Project

After setting up the dependencies and MongoDB, you can start both the client and server.
In the server directory:

```sh
npm run dev
```

In the client directory:

```sh
npm start
```
---
> ### Open in Browser

Once both the client and server are running, open your web browser and navigate to http://localhost:3000 to use the application.
---
> ## Dependencies
---
> ### Client

**Quill**: A powerful, rich text editor used to build the document editing interface.
**Socket.io-client**: The client-side library for real-time communication with the backend.
**react-router-dom**: A routing library for managing different pages in the React app.

> ### Server

**Mongoose**: Object Data Modeling (ODM) library for MongoDB and Node.js.
**Socket.io**: Enables real-time, bi-directional communication between web clients and servers.
**Nodemon**: A tool that automatically restarts the server during development.
