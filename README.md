# Programming-Assignment-3
Problem Statement

Create a seating reservation system for Colossus Airlines with 48 seats and two flights (outbound and inbound). The system should allow users to view seat availability, assign seats, delete assignments, and display sorted passenger lists.

Describe the Solution

The program uses an array of structures to represent seats. Each seat stores:

Seat number
Assignment status
First name
Last name

Two separate arrays are used for outbound and inbound flights.

A menu-driven system allows users to:

View empty seats
Assign and delete reservations
Display passengers alphabetically

Sorting is implemented using a simple bubble sort based on last names.

Pros and Cons

Pros

Easy to understand and organized
Uses modular functions
Handles user input safely (with cancel option)
Clear menu navigation

Cons

Uses bubble sort (not efficient for large data)
No file saving (data resets when program ends)
Limited input validation
