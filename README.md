 Crafted a full-stack note-taking app with Google authentication, allowing users to securely create, update, delete, and
 search notes.
 Designed a responsive UI using EJS templates and Bootstrap, with dynamic pagination and customizable dashboards.
 Established a secure backend with session management, CRUD operations, and third-party authentication integration for
 scalability and data integrity.

## You need:
- Database (MongoDB)
- Google Console Account to create the API Auth Key's

## Create .env file
Create a .env file to store your credentials. Example below:

```
MONGODB_URI = mongodb+srv://<username>:<password>@mongodburlhere
GOOGLE_CLIENT_ID= YOUR_GOOGLE_ID_HERE
GOOGLE_CLIENT_SECRET= YOUR_GOOGLE_CLIENT_SECRET_HERE
GOOGLE_CALLBACK_URL=http://localhost:5000/google/callback
```

## Installation
To install and run this project - install dependencies using npm and then start your server:

```
$ npm install
$ npm start
```
