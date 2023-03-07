# Java-Hotel-Management-System
A basic Java Program for Hotel Management System

The code implements a basic hotel management system program in Java. It contains three classes: Room, Booking, and HotelManagementSystem.

The Room class is a simple class that represents a hotel room. It has two fields: number (int) and type (enum RoomType), and a constructor that initializes these fields. The Booking class represents a booking made by a customer. It has four fields: id (int), customerName (String), checkInDate (String), checkOutDate (String), and room (Room), and a constructor that initializes these fields. The HotelManagementSystem class is the main class that contains the hotel management system logic.

The HotelManagementSystem class has three static ArrayLists: rooms, bookings, and scanner. The rooms list contains all the available rooms in the hotel, the bookings list contains all the current bookings made by the customers, and the scanner object is used to read user input from the console.

The main method of the HotelManagementSystem class contains a loop that repeatedly displays a menu of options to the user and reads their choice from the console. The available options are: book a room, cancel a booking, view all bookings, view available rooms, view occupied rooms, and exit.

The initializeRooms method initializes the rooms list with 30 rooms: 10 single rooms, 10 double rooms, and 10 suites.

The bookRoom method prompts the user to enter the customer name, check-in date, check-out date, and then displays a list of available rooms for the given dates. If the user selects a valid room number, a new booking object is created and added to the bookings list.

The cancelBooking method prompts the user to enter the booking ID of the booking to be canceled. If the booking ID is valid, the corresponding booking object is removed from the bookings list.

The printBookings method prints all the current bookings in the bookings list.

The printAvailableRooms method prints a list of all the available rooms for the given dates.

Similarly, the printOccupiedRooms method prints a list of all the occupied rooms for the given dates.

Overall, this program provides a basic framework for a hotel management system with functionality for booking and canceling rooms, as well as viewing current bookings and available/occupied rooms. However, it is a simplified version and may require additional features and error handling to make it more robust and functional for real-world use.
