# 🏨 Hotel Reservation System

A simple **Hotel Reservation System** developed using Python.  
This project allows users to view rooms, search for rooms, book and cancel reservations, view bookings, search bookings, and check booking statistics.

## 📌 Features

- Display all hotel rooms
- Search available rooms by room type
- Book a hotel room
- Cancel a booking
- View all bookings
- Search booking using Booking ID
- Calculate total bill based on number of nights
- Generate unique Booking IDs
- Save booking details to a text file
- Display booking statistics
- Calculate total revenue
- Find the highest booking bill
- Payment example using polymorphism

## 🛠️ Technologies Used

- Python
- Object-Oriented Programming (OOP)
- File Handling
- Lists
- Dictionaries
- List Comprehension
- Lambda Functions
- `reduce()`
- Generators
- Decorators
- Polymorphism

## 📂 Project Structure

```text
Hotel-Reservation-System/
│
├── project -2.py
├── hotel_bookings.txt
└── README.md
```

> `hotel_bookings.txt` is created automatically when a room is booked.

## 🏨 Room Details

| Room No | Room Type | Price per Night |
|--------:|-----------|----------------:|
| 101 | Single | ₹1500 |
| 102 | Single | ₹1500 |
| 201 | Double | ₹2500 |
| 202 | Double | ₹2500 |
| 301 | Deluxe | ₹4000 |
| 302 | Deluxe | ₹4000 |

## ▶️ How to Run

### 1. Install Python

Make sure Python is installed on your computer.

Check the Python version:

```bash
python --version
```

### 2. Download or Clone the Project

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Go into the project folder:

```bash
cd Hotel-Reservation-System
```

### 3. Run the Program

```bash
python "project -2.py"
```

## 📋 Menu Options

When the program starts, you will see:

```text
1. Display Rooms
2. Search Room
3. Book Room
4. Cancel Booking
5. View Bookings
6. Search Booking
7. Statistics
8. Exit
```

Choose an option by entering the corresponding number.

## 💰 Bill Calculation

The total bill is calculated using:

```text
Room Price × Number of Nights
```

For example:

```text
Room Price = ₹1500
Nights = 3

Total Bill = ₹1500 × 3
           = ₹4500
```

## 🎯 Concepts Demonstrated

### Object-Oriented Programming

The project uses classes such as:

- `Room`
- `Customer`
- `Reservation`
- `Hotel`
- `Payment`
- `UPI`
- `Card`

### Decorator

A custom decorator is used to display the action being performed.

```python
@log_action
def book_room(self):
```

### Generator

A generator is used to create booking IDs:

```text
B1001
B1002
B1003
...
```

### List Comprehension

Used to find available rooms of a particular type.

### Lambda

Used while finding the highest booking bill.

### Reduce

Used to calculate total revenue.

### Polymorphism

`UPI` and `Card` classes override the `pay()` method of the `Payment` class.

## 🔮 Future Enhancements

The project can be improved by adding:

- MySQL database integration
- Graphical User Interface (GUI)
- Web application using Flask
- Online payment integration
- Customer login and registration
- Hotel room images
- Check-in and check-out dates
- Email confirmation
- Admin dashboard
- Multiple hotel support

## 👩‍💻 Author

**Prasanna**

## 📄 License

This project is created for learning and educational purposes.
