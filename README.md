# Vinnie's Trattoria Admin Panel

## Overview
The Vinnie's Trattoria Admin Panel is a robust web application designed to help manage the operations of Vinnie's Trattoria. This admin panel allows administrators to efficiently handle menu updates, reservations, user feedback, and other key functionalities necessary for running the restaurant.

## Features
- **Menu Management:**
  - Add, edit, or remove menu items with ease.
  - Upload images and descriptions for menu items.
- **Reservation System:**
  - View and manage customer reservations.
  - Approve, decline, or update reservation requests.
- **Feedback and Reviews:**
  - Access and respond to customer reviews or inquiries.
- **User Management:**
  - Manage admin accounts and roles.
- **Analytics Dashboard:**
  - View insights about reservations, customer activity, and sales.

## Technologies Used
- **Frontend:**
  - React.js
  - Material-UI
- **Backend:**
  - Node.js
  - Express.js
- **Database:**
  - MongoDB
- **Authentication:**
  - JSON Web Tokens (JWT)
- **Other Tools:**
  - Axios (for API calls)
  - dotenv (for environment variable management)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/OJOCoding/VinniesTratoriaAdmin.git
   cd VinniesTratoriaAdmin
   ```

2. Install dependencies for both the frontend and backend:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the `server/` directory.
   - Add the following variables:
     ```env
     PORT=5000
     MONGO_URI=your-mongodb-uri
     JWT_SECRET=your-secret-key
     ```

4. Start the application:
   - Run the backend server:
     ```bash
     cd server
     npm start
     ```
   - Run the frontend client:
     ```bash
     cd client
     npm start
     ```

5. Open your browser and navigate to:
   - Frontend: `http://localhost:3000`
   - Backend API: `http://localhost:5000`

## Project Structure
```plaintext
VinniesTratoriaAdmin/
├── client/             # Frontend application (React.js)
│   ├── public/         # Static files
│   ├── src/            # React components, pages, and services
│   └── package.json    # Frontend dependencies
├── server/             # Backend application (Node.js/Express)
│   ├── models/         # Database models
│   ├── routes/         # API routes
│   ├── controllers/    # Request handlers
│   ├── utils/          # Utility functions
│   └── package.json    # Backend dependencies
├── .env.example        # Example environment variables file
├── README.md           # Project documentation
└── LICENSE             # License file
```

## Usage
1. **Login:** Use admin credentials to log in to the admin panel.
2. **Menu Management:** Navigate to the menu section to update restaurant offerings.
3. **Reservations:** Access the reservations page to manage bookings.
4. **Feedback:** Monitor customer reviews and respond as necessary.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your changes:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to your fork.
4. Create a pull request detailing your updates.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For any questions or support, please reach out:
- GitHub: [OJOCODING](https://github.com/OJOCODING)
- Email: oniluca@ymail.com

---

Thank you for contributing to the Vinnie's Trattoria Admin Panel project!
