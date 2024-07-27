# MERN Authentication with Google OAuth

**Here's The UI of MERN Auth**

![Screenshot 2024-07-27 225316](https://github.com/user-attachments/assets/6ba78c11-8e6c-4019-8f0b-ce2ec25fbfe0)

**2nd ONE**-UI

![Screenshot 2024-07-27 225334](https://github.com/user-attachments/assets/39e10d82-abf7-437e-ae6d-47977f49454e)


## Introduction
This project is a comprehensive authentication system built using the MERN stack (MongoDB, Express.js, React.js, Node.js) and Google OAuth. The application enables users to authenticate using their Google accounts, eliminating the need for separate registration or signup processes. User data is securely fetched and verified using their Gmail accounts.

## Features
- **Google OAuth Authentication**:
   Authenticate users via their Google accounts.
  
- **Secure Access**:
   Protect user data and manage sessions securely.
  
- **No Registration Needed**:
  Users can log in without any additional registration steps.
  
- **Fetch User Data**:
   Retrieve user information from Google upon authentication.
- **Session Management**:
   Maintain user sessions with JWT (JSON Web Tokens).
  

## Technologies Used
- **Frontend**: 
  - React.js: For building the user interface.
  - Tailwind CSS: For styling the application.

- **Backend**: 
  - Node.js: For server-side JavaScript runtime.
  - Express.js: For building the RESTful APIs.
 
- **Database**: 
  - MongoDB: For storing user data.
- **Authentication**: 
  - Google OAuth 2.0: For authenticating users with their Google accounts.
  - JWT (JSON Web Tokens): For securing user sessions.

## Architecture
The architecture of this authentication system follows the typical MERN stack structure:
- **Frontend**: React.js manages the user interface and interactions.
- **Backend**: Node.js with Express.js handles the API requests and authentication logic.
- **Database**: MongoDB stores user information and session data.
- **Authentication Layer**: Google OAuth 2.0 is used for user authentication.

## Installation
Follow these steps to set up and run the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/mern-auth-google-oauth.git
   cd mern-auth-google-oauth

2. **For Frontend**
   Open Terminal / cd client / npm i

3. **For Backend**
   Open Terminal / cd server / npm i

4. **-Environment Variables-**
   PORT = 8080
   CLIENT_ID = Add your client id here
   CLIENT_SECRET = Add yout client secret here
   CLIENT_URL = frontend/client URL here

   Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure to follow the project's code style and add appropriate tests.
   
