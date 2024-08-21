# Hotel Reservation System

## Overview

The **Hotel Reservation System** is a Java-based application designed to manage hotel room bookings efficiently. It provides a command-line interface for both guests and hotel staff to reserve rooms, view reservations, update existing reservations, and delete reservations. The system interacts with a MySQL database to store and retrieve reservation data.

## Features

- **Reserve a Room**: Allows guests to make reservations by entering their name, room number, and contact details.
- **View Reservations**: Displays a list of all current reservations, including reservation ID, guest name, room number, contact information, and reservation date.
- **Get Room Number**: Retrieves the room number based on a reservation ID and guest name.
- **Update Reservations**: Updates existing reservations with new guest details, room number, and contact information.
- **Delete Reservations**: Deletes a reservation based on the reservation ID.
- **Exit**: Gracefully exits the system with a countdown.

## Technologies Used

- **Java**: Programming language used to implement the system.
- **MySQL**: Database used to store reservation data.
- **JDBC**: Java Database Connectivity API for interacting with the MySQL database.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or later installed on your machine.
- MySQL database server installed and running.
- A MySQL database named `hotel_db` with a table `reservations` for storing reservation information.
