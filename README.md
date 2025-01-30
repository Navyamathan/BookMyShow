BookMyShow - Movie Ticket Booking System

📌 Project Overview

BookMyShow is a Java-based movie ticket booking system that allows users to book movie tickets online. The system supports admin and customer functionalities, including managing theatres, shows, and ticket reservations.

🚀 Features

🎭 Admin Functionalities

Add & Manage Shows: Admins can add movie shows with details like date, time, location, and price.

Manage Screens & Theatres: Admins can define theatre and screen configurations.

🎟️ Customer Functionalities

User Registration & Login: Customers can create accounts and log in.

Browse & Select Movies: Users can view available movies and shows.

Book Tickets: Customers can select seats and book tickets.

View Booking History: Users can check their booked tickets.

🛠️ System Architecture

The system follows an object-oriented approach, with key classes handling different functionalities:

Helper.java - Entry point (main()).

BookMyShowActions.java - Controls the application workflow (start()).

Admin.java - Handles admin authentication.

Customer.java - Manages user details and booking history.

Theatre.java - Represents theatres with screens and movies.

Show.java - Defines movie details, schedule, and pricing.

Screen.java - Represents theatre screens and seat availability.

Tickets.java - Stores booking details for users.

Utilities.java - Helper functions (seat allocation, pricing calculations).

📂 Folder Structure

BookMyShow/
│── src/
│   ├── Helper.java
│   ├── BookMyShowActions.java
│   ├── Admin.java
│   ├── Customer.java
│   ├── Theatre.java
│   ├── Show.java
│   ├── Screen.java
│   ├── Tickets.java
│   ├── Utilities.java
│── README.md

🏗️ Technologies Used

Java (Core OOP concepts)

Collections Framework (ArrayLists, HashMaps)

DateTime API (Java Time Formatter)

File Handling (For storing user and booking data, if applicable)

🔧 How to Run the Project

Clone the Repository

git clone https://github.com/yourusername/BookMyShow.git

Compile & Run

cd BookMyShow/src
javac Helper.java
java Helper

Author: Your Name | Your Contact Info

Enjoy Coding! 🚀

