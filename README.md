# Web Application README

## Overview
This web application is built using Node.js, Express, MongoDB, and Passport for authentication. It provides functionality for managing listings, reviews, and user accounts.

## Setup
1. Clone this repository.
2. Install dependencies using `npm install`.
3. Create a `.env` file in the root directory and define the following variables:
4. Start the server using `npm start`.
5. Navigate to `http://localhost:8000` in your web browser.

## Features
- **Listings Management**: Users can create, update, and delete listings.
- **Review System**: Users can leave reviews for listings.
- **User Authentication**: Passport is used for user authentication with local strategy.
- **Flash Messages**: Flash messages for success and error alerts.
- **Session Management**: User sessions are managed using Express session and stored in MongoDB.
- **Static Files**: Static files like CSS and client-side scripts are served from the `public` directory.
- **Error Handling**: Custom error handling for 404 and other server errors.

## Routes
- `/`: Home page.
- `/listings`: Listings management routes.
- `/listings/:id/reviews`: Routes for managing reviews for a specific listing.
- `/users`: User management routes.

## Dependencies
- `express`: Web application framework.
- `mongoose`: MongoDB object modeling tool.
- `ejs-mate`: EJS template engine with layout support.
- `method-override`: Middleware for HTTP method override.
- `express-session`: Middleware for managing sessions.
- `connect-mongo`: MongoDB session store for Express session.
- `connect-flash`: Middleware for displaying flash messages.
- `passport`: Authentication middleware for Node.js.
- `passport-local`: Local authentication strategy for Passport.
- `dotenv`: Loads environment variables from a `.env` file.

## Website Link
Access the website [here](https://wanderlust-80q4.onrender.com/listings).

## Developer
This project was developed by Vishal Kumar Yadav.

## License
This project is licensed under the [MIT License](LICENSE).
