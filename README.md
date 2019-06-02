Veterinario

This project is for authenticating user/clients using Google API Oauth.  By using Google Oauth you have the user give permission for application to access there email profile.  On this project only the Google user id is stored on a MongoDB deployed in the cloud using MongoDB Atlas.  Only after the user allows access to profile can they login. Below libraries and dependencies to create app:

"dependencies": {
    "client": "0.0.1",
    "cookie-session": "^1.3.3",
    "create-react-app": "^3.0.1",
    "express": "^4.17.0",
    "mongoose": "^5.5.10",
    "nodeman": "^1.1.2",
    "passport": "^0.4.0",
    "passport-google-oauth20": "^2.0.0"
  }
