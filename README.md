# Blog App

The Blog App is a full-stack web application that allows users to create, upload, and view blog posts. It provides a platform for users to share their thoughts, ideas, and experiences with others.

## Features

- **User Registration and Login:** Users can create accounts and log in to the app using their credentials.

- **Create and Upload Posts:** Logged-in users can create new blog posts by providing a title, content, and optionally, an image.

- **View Posts:** Users can browse and view all the posts created by themselves and other users.

- **Edit and Delete Posts:** Users have the ability to edit or delete their own posts as needed.

## Technologies Used

- **Frontend:** The frontend of the app is built using React, including components for different parts of the app such as authentication, post creation, and post display. It communicates with the backend via API calls. 

- **Backend:** The backend is developed using Node.js and the Express framework. It handles API requests, interacts with the database, and manages user authentication.

- **Database:** The app uses a MySQL database to store user information, post data, and other relevant details.

## Installation

1. Clone the repository

2. Navigate to the project directory

3. Install dependencies:
   - For the frontend, navigate to the `frontend` directory and run `npm install`.
   - For the backend, navigate to the `backend` directory and install the required packages.

4. Set up the database:
   - Create a new database for the app.
   - Configure the database connection in the backend by updating the appropriate configuration file.

5. Start the app:
   - Run the frontend: Navigate to the `frontend` directory and run `npm start`.
   - Run the backend: Navigate to the `backend` directory and start the server.

6. Access the app: Open your web browser and go to `http://localhost:3000` (or the appropriate port configured).

## Usage

1. Register an account or log in using existing credentials.

2. Once logged in, you'll be directed to the main dashboard where you can see posts from various users.

3. To create a new post, click on the "Write" button, fill in the necessary details, and submit.

4. To view a post's details, click on the post title or its associated image.

5. You can edit or delete your posts by accessing them from your user dashboard.

## Contributing

If you're interested in contributing to the Blog App, feel free to fork the repository, make your changes, and submit a pull request. Make sure to follow the existing code style and guidelines.
