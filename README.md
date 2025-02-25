![BookMyShow](https://github.com/user-attachments/assets/fc0f6583-58ae-414d-bd74-6533b4256529)
# 🎬 BookMyShow - Theatre Ticket Booking System

## 📌 Overview
BookMyShow is a Java-based theatre ticket booking system that provides a user-friendly platform for managing bookings, customer accounts, and show schedules. The system enables smooth and efficient ticket reservations with a well-structured modular architecture.

## 🚀 Features

### 🎭 For Customers
- **User Registration & Login**
- **Browse & Book Shows**: View available movies and schedules
- **Real-time Seat Selection**
- **Booking History Management**
- **Secure Authentication**

### 🎟️ For Administrators
- **Manage Shows & Scheduling**
- **Configure Theatres & Screens**
- **Control Seat Allocations**
- **User Account Management**
- **Monitor and Manage Bookings**

## 🛠️ System Architecture
BookMyShow follows a modular architecture with key components:

### 🔑 Core Components
- **Helper.java**: Application entry point
- **BookMyShowActions.java**: Central controller handling workflows
- **AdminActions.java**: Manages administrator operations
- **CustomerActions.java**: Handles customer interactions and bookings

### 🎬 Entity Classes
- **Show.java**: Stores show details (date, time, pricing, seating)
- **Screen.java**: Manages individual screens and seat layouts
- **Theatre.java**: Configures theatres and assigns screens
- **Tickets.java**: Handles ticket generation and records bookings
- **Customer.java**: Maintains customer profiles and booking history
- **Admin.java**: Secures administrator access

### 🔧 Utility Components
- **Utilities.java**: Provides helper functions like seat allocation

## 💻 Technical Stack
- **Language**: Java
- **Authentication**: Custom user authentication
- **Data Management**: Java Collections Framework
- **Date & Time Handling**: Java LocalDateTime API

## 🛠️ Setup and Installation

### Clone the Repository
```bash
git clone https://github.com/yourusername/bookmyshow.git
```

### Compile the Project
```bash
javac -d bin src/*.java
```

### Run the Application
```bash
java -cp bin Helper
```

## 👤 Project Structure
```
src/
├── Helper.java
├── BookMyShowActions.java
├── AdminActions.java
├── CustomerActions.java
├── entities/
│   ├── Show.java
│   ├── Screen.java
│   ├── Theatre.java
│   ├── Tickets.java
│   ├── Customer.java
│   ├── Admin.java
└── utils/
    └── Utilities.java
```

## 🔐 Security Features
- **Encrypted User Credentials**
- **Secure Admin Access Control**
- **Session Management**

## 📊 Future Enhancements
- **Integration with Payment Gateways**
- **Movie Ratings & Reviews**
- **Mobile App Support**
- **AI-based Seat Recommendation**

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repo and submit a Pull Request.

## 👥 Contact
Navya M V 
navyamathan@gmail.com
