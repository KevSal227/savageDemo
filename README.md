# 🎤 21 Savage Fan Message Board

<img width="522" height="540" alt="21 savage demo SS" src="https://github.com/user-attachments/assets/c9ff91cc-988d-49e3-ba91-d1c21791238d" />


### Full-Stack CRUD Application

## About the Project

This is a 21 Savage fan message board I worked on to practice building a full-stack application with Node.js, Express, and MongoDB.

The idea was to create a simple place where fans could leave messages and interact with other posts.

This project helped me understand how to connect the front end to the back end and how to save, update, and delete information in a database.

## Features

- **Post Messages:** Users can enter their name and leave a message.
- **View Messages:** Display posts saved in MongoDB.
- **Like Messages:** Increase the positive-vote count on a post.
- **Dislike Messages:** Decrease the positive-vote count on a post.
- **Delete Messages:** Remove posts from the database.

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Node.js
- Express.js
- EJS
- MongoDB
- Fetch API

## How It Works

1. A user visits the message board and sees existing posts.
2. They enter their name and a message.
3. The Express server saves the post to MongoDB.
4. EJS displays the saved messages.
5. Users can like, dislike, or delete messages.
6. JavaScript sends requests to the server using the Fetch API.

## Getting Started

1. Clone the repository:

   `git clone https://github.com/KevSal227/savageDemo.git`

2. Open the project directory:

   `cd savageDemo`

3. Install dependencies:

   `npm install`

4. Configure a valid MongoDB connection in `server.js`.

5. Start the application:

   `npm start`

6. Open `http://localhost:3000` in your browser.

You can also run `npm run savage` to start the application with Nodemon.

## What I Learned

This project helped me practice:

- Setting up an Express server.
- Creating GET, POST, PUT, and DELETE routes.
- Connecting an application to MongoDB.
- Using EJS to display dynamic information.
- Sending requests with the Fetch API.
- Updating database records using MongoDB's `$inc` operator.
- Working with CRUD operations in a full-stack application.

One of the biggest things I learned was how the browser, server, and database communicate when someone interacts with a post.

## Current Limitations

There are still a few improvements I'd make:

- Identify posts by their MongoDB ObjectId instead of matching names and messages.
- Add separate positive and negative vote counters.
- Improve error handling and form validation.
- Move database credentials into environment variables.
- Add authentication and permissions for modifying posts.
- Update older dependencies.

## Acknowledgments

This project was developed as part of my full-stack development practice and served as a foundation for later projects involving authentication and CRUD functionality. 
