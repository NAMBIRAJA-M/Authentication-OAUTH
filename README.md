# Google OAuth 2.0 Authentication with Node.js

This project demonstrates how to implement Google OAuth 2.0 authentication in a Node.js application using Express and Passport.js. The application allows users to log in with their Google accounts and handles the authentication process securely and efficiently.

## Features

- **Google OAuth 2.0 Authentication**: Users can authenticate with their Google accounts.
- **Passport.js Integration**: Utilizes Passport.js for handling authentication strategies.
- **Session Management**: Serializes and deserializes user information to manage sessions effectively.
- **Environment Configuration**: Uses dotenv to manage sensitive credentials securely.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
2. Install dependencies:

  ```sh
npm install
Create a .env file in the root directory and add your Google API credentials:
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
GOOGLE_CALLBACK_URL=http://localhost:3000/auth/google/callback
```
3. Usage

To start the application, run:

node index.js

Contributing

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Open a pull request.

Acknowledgements

Node.js
Express
Passport.js
dotenv
