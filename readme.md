
#  Movie Ticket Booking System

A **Java console-based application** that simulates a real-world movie ticket booking system. It allows users to log in, browse movies, book and cancel tickets, select seats, and view booking history, all within a simple yet functional interface.

---

##  Description

This system is designed to automate movie ticket bookings with functionalities like:

- **User authentication**
- **Movie listings with showtimes**
- **Ticket booking and seat selection**
- **Booking cancellation**
- **Viewing booking history**

All data (user credentials, movie details, and bookings) are managed using text files (`users.txt`, `movies.txt`, `bookings.txt`).

---

##  Objectives

- Simulate a movie ticket booking environment.
- Allow authenticated users to perform ticket operations securely.
- Practice file-handling and OOP concepts in Java.

---

##  Features

- ** User Authentication**  
  Login credentials are verified against a `users.txt` file.

- ** Movie Listings**  
  Displays a list of movies with showtimes and seat availability.

- ** Seat Selection & Booking**  
  Users choose a movie, select available seats, and confirm the booking.

- ** Booking Cancellation**  
  Cancels a booking, updates seat availability and booking history.

- ** Booking History**  
  Shows a user's booking history with movie, time, and seat details.

---

##  Technologies Used

| Technology  | Purpose                        |
|-------------|--------------------------------|
| Java        | Core application logic         |
| File I/O    | Data persistence               |
| OOP         | Modular and reusable code      |
| Terminal UI | User interaction via CLI       |

---

##  Project Structure

```
movie-ticket-booking-system/
├── MovieSystem/
│   ├── User.java
│   ├── Movie.java
│   ├── Booking.java
│   └── TicketSystem.java
├── MiniProject.java
├── users.txt
├── kollywood.txt
├── hollywood.txt
└── userhistory.txt
├── seatmatrix.txt
└── last_booking_id.txt
```

---

##  How to Run

###  Prerequisites
- Java JDK 8 or later installed

###  Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/movie-ticket-booking-system.git
   cd movie-ticket-booking-system
   ```

2. **Check if Java is installed**

   ```bash
   java -version
   ```

3. **Compile the classes**

   ```bash
   javac MovieSystem/*.java MiniProject.java
   ```

4. **Run the main program**

   ```bash
   java MovieSystem.TicketSystem
   ```

---

##  Output Preview

```plaintext
Welcome to the Movie Ticket Booking System
Please log in with your username and password.

> Login Successful!

Available Movies:
1. Inception - 7:00 PM
2. Interstellar - 9:30 PM

Select a movie to book seats...
```
