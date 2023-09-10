
# SecretsApp 🤫

![SecretsApp Logo](https://github.com/MahmoodWebDev/secrets-authentication-oauth2/blob/main/secrets.png)

## Description

**SecretsApp** is a full-stack application built using Node.js, Express, EJS, and MongoDB. It serves as a platform where users can anonymously share their secrets. The project demonstrates various levels of authentication and security, including OAuth 2.0 with Google.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Authentication**: Secure user registration and login via Passport.js.
- **Google OAuth 2.0**: Option to sign in via Google.
- **Security**: Hashing, salting, and session management.
- **Anonymity**: Secrets are posted anonymously.
- **Responsive Design**: Thanks to Bootstrap.

## Installation

Before you begin, make sure you have Node.js and MongoDB installed.

1. Clone the repository:
   ```bash
   git clone (https://github.com/MahmoodWebDev/secrets-authentication-oauth2)
   ```
2. Navigate into the directory:
   ```bash
   cd SecretsApp
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Create a `.env` file to store your environment variables:
   ```bash
   touch .env
   ```
   Populate it as follows:
   ```env
   DATABASE_URL=your_mongodb_url
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   SESSION_SECRET=your_session_secret
   ```

## Usage

1. Start the MongoDB server:
   ```bash
   mongod
   ```
2. Run the app:
   ```bash
   node app.js
   ```
3. Visit `http://localhost:3000` to access the app.

## Contributing

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License

MIT License. See the `LICENSE` file for details.
