# Project Name
Portfolio, Shalkharov Seidulla
## Description
This project is a web application for managing items. It allows users to add, edit, and delete items. Each item can have multiple images, names for localization, descriptions for localization, and timestamps for creation, update, and deletion. The application has separate functionalities for administrators and regular users. Administrators have full control over the items, while regular users can view and interact with the items.

## Features
- **User Authentication:** Users can register and log in to access the application.
- **Role-based Access Control:** Different functionalities are available based on user roles (admin or user).
- **Add Item:** Users can add new items with multiple images, names, descriptions, and timestamps.
- **Edit Item:** Administrators can edit existing items.
- **Delete Item:** Administrators can delete items.
- **View Items:** Users can view all items with their details.

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose
- API, RestAPI
- HTML/CSS
- EJS (Embedded JavaScript) for templating
- Axios for HTTP requests
- Nodemailer for sending emails
- bcrypt for password hashing
- JWT (JSON Web Tokens) for authentication
- Session management with Express Session

## Installation
1. **Clone the repository:** `git clone <repository-url>`
2. **Install dependencies:** `npm install`
3. **Set up MongoDB:** Make sure MongoDB is installed and running on your local machine. Update the MongoDB connection URI in `server.js` if necessary.
4. **Start the server:** `npm start`
5. **Access the application:** Open your web browser and navigate to `http://localhost:3000`

## Usage
1. **Register/Login:** Register as a new user or log in with existing credentials.
2. **Admin Dashboard:** As an administrator, you can add, edit, and delete items using the admin dashboard.
3. **View Items:** As a regular user, you can view items but cannot perform administrative actions.


