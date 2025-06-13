# Restaurant Reservation Management Application

## Overview

The Restaurant Reservation Management Application is a web-based application designed to facilitate the management of restaurant reservations. It allows users to create reservations, view existing reservations, and leave comments regarding their experiences. The application is built using a backend powered by Express.js and a frontend developed with ReactJS.

## Project Structure

The project is organized into two main directories: `backend` and `frontend`.

### Backend

- **src**: Contains the source code for the backend application.
  - **controllers**: Contains the logic for handling requests related to comments, reservations, and tables.
    - `commentController.js`: Handles comment-related operations.
    - `reservationController.js`: Manages reservations.
    - `tableController.js`: Handles table-related operations.
  - **models**: Defines the data models and their relationships.
    - `Comment.js`: Defines the Comment model.
    - `Reservation.js`: Defines the Reservation model.
    - `Table.js`: Defines the Table model.
    - `User.js`: Defines the User model.
  - **routes**: Sets up the API routes for the application.
    - `commentRoutes.js`: Routes for comment-related API endpoints.
    - `reservationRoutes.js`: Routes for reservation-related API endpoints.
    - `tableRoutes.js`: Routes for table-related API endpoints.
  - `app.js`: The entry point of the backend application.
  - **config**: Contains configuration files.
    - `db.js`: Database configuration and connection logic.
- `package.json`: Lists the dependencies and scripts for the backend project.
- `README.md`: Documentation specific to the backend project.

### Frontend

- **src**: Contains the source code for the frontend application.
  - **components**: Contains React components for the application.
    - `AddReservation.js`: Component for adding a new reservation.
    - `ReservationList.js`: Component for displaying a list of reservations.
    - `CommentForm.js`: Component for submitting comments.
  - `App.js`: The main entry point for the frontend application.
  - **api**: Contains functions for making API calls.
    - `reservationApi.js`: Functions for reservation-related API calls.
- `package.json`: Lists the dependencies and scripts for the frontend project.
- `README.md`: Documentation specific to the frontend project.

## Features

- Create and manage reservations.
- View reservations filtered by table.
- Post comments related to reservations.
- User-friendly interface built with ReactJS.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB or any other database of your choice for data storage.

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd restaurant-reservation-app
   ```

2. Navigate to the backend directory and install dependencies:
   ```
   cd backend
   npm install
   ```

3. Navigate to the frontend directory and install dependencies:
   ```
   cd frontend
   npm install
   ```

### Running the Application

1. Start the backend server:
   ```
   cd backend
   npm start
   ```

2. Start the frontend application:
   ```
   cd frontend
   npm start
   ```

The application should now be running on `http://localhost:3000` for the frontend and `http://localhost:5000` for the backend (or whichever port you have configured).

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.