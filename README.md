# Movie Ticket Booking System

## About the Project

This is a simple Movie Ticket Booking System developed using Python. It allows users to book movie seats, cancel existing bookings, and check seat availability through a menu-based interface.

The system has 3 rows (A, B, C), with 5 seats in each row. It also saves booking details in a text file, so the data remains available even after closing the program.

I created this project to practice Python programming, file handling, functions, lists, and dictionaries.

## Features

- Book one or multiple seats.
- Cancel booked seats.
- View the current seat arrangement.
- Check available seats.
- Automatic ticket price calculation.
- Save booking details in a text file.
- Load previous bookings when the program starts.
- Display a message when all seats are booked.

## Technologies Used

- Python 3
- File Handling
- Lists and Dictionaries
- Functions
- Basic Exception-Free Input Handling

## Project Structure

```text
Movie-Ticket-Booking-System/
│
├── main.py
├── bookings.txt
└── README.md
```

## How to Run

1. Download or clone this repository.
2. Open the project folder in VS Code or any Python editor.
3. Make sure Python 3 is installed.
4. Open the terminal and run:

```bash
python3 main.py
```

## Seat Layout

```text
       1  2  3  4  5
Row A  _  _  _  _  _
Row B  _  _  _  _  _
Row C  _  _  _  _  _
```

`_` = Available Seat

`X` = Booked Seat

## Ticket Price

- Price per seat: ₹200
- Total seats: 15

## Menu Options

1. Book a Seat
2. Cancel a Booking
3. View Seat Map
4. Exit

## Data Storage

All booking details are stored in `bookings.txt`. When the program runs again, previously booked seats are loaded automatically.

## Future Improvements

- Add movie selection.
- Add show timings.
- Generate booking ID.
- Add payment option.
- Create a graphical user interface (GUI)# 31_Movie-Ticket-Booking-System-_RU-26-02048_1D_Ghanishka-kumari
A Python-based movie ticket booking system with seat selection, booking, cancellation and file handling.
