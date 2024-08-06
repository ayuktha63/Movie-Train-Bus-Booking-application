# Ticket Booking Application

## Overview

This application allows users to book tickets for movies, trains, and buses. Users can view their booking details, while admin users have the capability to manage and view data across all booking categories. Admins can also delete records from the database.

## Features

- **User Login**: Users can log in to access booking features.
- **Booking Functionality**: Users can book tickets for movies, trains, and buses.
- **Admin Dashboard**: Admin users can log in with specific credentials to manage and view data for movies, buses, and trains.
- **Data Management**: Admins can view details and delete records from each category.

## Technologies Used

- **Frontend**: 
  - HTML
  - CSS
  - JavaScript
  - React (for the admin dashboard)
- **Backend**: 
  - Node.js v22.4.1
  - Express.js (for handling API requests)
- **Database**: 
  - MongoDB (for storing booking data)

## Setup Instructions

### Prerequisites

- Node.js v22.4.1
- MongoDB (ensure MongoDB is installed and running)

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/ayuktha63/Movie-Train-Bus-Booking-application.git
    ```

2. **Install Dependencies**:
    ```bash
    npm install
    ```

3. **Configure Environment Variables**:
    Create a `.env` file in the root directory and add the following content:
    ```env
    PORT=5001
    MONGO_URI=mongodb://localhost:27017/ticket
    ```

4. **Start the Frontend**:
    Run the following command to start the frontend server:
    ```bash
    node server.js
    ```

    Open your browser and navigate to `http://127.0.0.1:5001` to access the application.

### API Endpoints

- **GET** `/api/movies`: Retrieve movie data
- **GET** `/api/buses`: Retrieve bus data
- **GET** `/api/trains`: Retrieve train data
- **DELETE** `/api/delete-movie/:id`: Delete a movie record
- **DELETE** `/api/delete-bus/:id`: Delete a bus record
- **DELETE** `/api/delete-train/:id`: Delete a train record

### Admin Credentials

- **Username**: `admin@gmail.com`
- **Password**: `admin@123`

Use these credentials to log in to the admin dashboard and manage the data.

## Personal Note

This project was originally developed by a friend, and I assisted in completing it. I have a passion for helping friends with coding and enjoy assisting others. I am somewhat familiar with the Flask framework in Python and have completed many projects in Django which are visible on my profile. This project presented a new challenge, and I am pleased to have successfully completed it with the help of ChatGPT.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## Contact

For any questions or feedback, please contact [krishnaprasadsm63@gmail.com](mailto:krishnaprasadsm63@gmail.com).
