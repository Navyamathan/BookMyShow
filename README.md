# BookMyShow - Movie Ticket Booking System

A **Java-based console application** that simulates an efficient and user-friendly movie ticket booking system. This project allows **admins** to manage theatres, screens, and movie schedules, while **users** can register, browse movies, book tickets, and manage preferences seamlessly.

---

## 📌 Features

### 🎭 Admin Operations

Admins have full control over theatre and movie management:

- **Admin Login** - Secure login for admin users.
- **Manage Locations** - Add and update locations.
- **Manage Theatres** - Configure theatres in specific locations.
- **Manage Screens** - Set up screens in theatres.
- **Manage Movies** - Schedule movies in theatres.
- **View Theatres** - Retrieve theatre details.
- **View Movies** - List currently scheduled movies.

### 🎬 User Operations

Users can interact with the system efficiently:

- **User Registration & Login** - Register a new account or log in as an existing user.
- **Browse Movies** - View available movies and their details.
- **Book Tickets** - Check theatre availability and book tickets.
- **Set Preferences** - Choose preferred location and movie genres.
- **View Tickets** - Review past and current bookings.

---

## 📂 Project Structure

### 🏛 Core Classes

- **`MainClass`** - Entry point of the application.
- **`AdminActions`** - Handles all admin-related functionalities.
- **`UserActions`** - Manages user-related operations like booking and registration.
- **`Utilities`** - Helper methods for seat generation and validations.

### 📌 POJO (Plain Old Java Object) Classes

- **`Theatre`** - Stores theatre details (name, location, screens, etc.).
- **`Screen`** - Represents theatre screens with seat numbers and show mappings.
- **`Show`** - Stores details of a movie show, including time, price, and schedule.
- **`Tickets`** - Contains booking information such as theatre name, screen, timing, and price.
- **`Movies`** - Represents movie details like name, duration, and associated theatres.

---

## 🛠 Installation & Setup

### **Prerequisites**

- Java Development Kit (JDK 8+)
- Git (for cloning the repository)

### **Steps to Install & Run**

```sh
# Clone the Repository
git clone https://github.com/your-username/book-my-show.git
cd BookMyShow

# Compile the Project
javac MainClass.java

# Run the Application
java MainClass
```

---

## 🖥 Class Diagram

![BookMyShow Architecture](https://github.com/Navyamathan/BookMyShow/blob/main/BookMyShow/BookMyShow.png)

---

## 📊 Output Preview



https://github.com/user-attachments/assets/c8d9b2b8-acd5-4da0-8c46-bbc79ff99683



---

## 🔄 How It Works

### **👨‍💼 Admin Workflow:**

1. Admin logs in using predefined credentials.
2. Admin performs actions like adding locations, managing theatres, scheduling movies, and retrieving details.

### **👤 User Workflow:**

1. New users register an account, while existing users log in.
2. Users browse movies, check theatre availability, and book tickets.
3. Users can set preferences and view past bookings.

---

## 📞 Contact & Author

**Author:** Navya M V\
📧 Email: navyamathan@gmail.com\
🔗 LinkedIn: [Navya M V](https://www.linkedin.com/in/navya-m-v-55515b353/)

---

### 🚀 Happy Coding & Enjoy Your Movie Booking Experience! 🎟️

