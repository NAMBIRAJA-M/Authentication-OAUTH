
//DESCRIPTION
This project demonstrates how to implement Google OAuth 2.0 authentication in a Node.js application using Express and Passport.js.
The application allows users to log in with their Google accounts and handles the authentication process securely and efficiently.

//Features
* Google OAuth 2.0 Authentication: Users can authenticate with their Google accounts.
* Passport.js Integration: Utilizes Passport.js for handling authentication strategies.
* Session Management: Serializes and deserializes user information to manage sessions effectively.
* Environment Configuration: Uses dotenv to manage sensitive credentials securely.

//INSTALLATION
 * To install dependencies, run:
npm install
 *  Create a .env file in the root directory and add your Google API credentials:
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
GOOGLE_CALLBACK_URL=http://localhost:3000/auth/google/callback

//USAGE
To use this project, run:

node index.js
