🎬 Theatre Ticket Booking System
Overview
A Java-based ticket booking system that provides a robust platform for managing theatre bookings, customer accounts, and show schedules. The system offers a streamlined interface for both administrators and customers, enabling efficient ticket reservations and theatre management.
🚀 Features
For Customers

Account creation and management
Browse available shows and schedules
Real-time seat selection and booking
View booking history and tickets
Secure authentication system

For Administrators

Show management and scheduling
Theatre and screen configuration
Seat allocation control
User management system
View and manage bookings

🏗️ Architecture
The system follows a modular architecture with the following key components:
Core Components

Helper: Application entry point
BookMyShowActions: Main controller for application workflow
AdminActions: Handles all administrator operations
CustomerActions: Manages customer interactions and bookings

Entity Classes

Show: Manages show details including date, time, and pricing
Screen: Handles screen and seat management
Theatre: Controls theatre configuration and screen assignments
Tickets: Manages ticket generation and booking records

Utility Components

Utilities: Provides helper functions for common operations

💻 Technical Stack

Language: Java
Authentication: Custom implementation
Data Management: Java Collections Framework
Date/Time: Java LocalDateTime API

🛠️ Setup and Installation

Clone the repository

bashCopygit clone https://github.com/yourusername/theatre-booking-system.git

Compile the project

bashCopyjavac -d bin src/*.java

Run the application

bashCopyjava -cp bin Helper
📂 Project Structure
Copysrc/
├── Helper.java
├── BookMyShowActions.java
├── AdminActions.java
├── CustomerActions.java
├── entities/
│   ├── Show.java
│   ├── Screen.java
│   ├── Theatre.java
│   └── Tickets.java
└── utils/
    └── Utilities.java
🔐 Security Features

Secure user authentication
Protected admin access
Encrypted user credentials
Session management

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
📝 License
[Your chosen license]
👥 Contact
[Your Name]
[Your Email/Contact Information]
