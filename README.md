# Hotel Management System

## Project Overview

The **Hotel Management System** is a comprehensive database solution designed to streamline the operations of a hotel. This system manages guest information, room bookings, and associated data, facilitating efficient management of hotel resources. Built using SQL, this project serves as a foundational application for handling various aspects of hotel management, providing insights into guest stays and booking details.

## Features

- **Guest Management**: Keep track of guest details, including names, room assignments, check-in, and check-out dates.
- **Room Management**: Manage room types, prices, and availability.
- **Booking Management**: Handle bookings, total amounts, and associated guest information.
- **Data Analysis**: Fetch useful insights, such as guests who stayed for the same number of days, the second most expensive booking, and more.
- **Views and Procedures**: Create views for high-value bookings and stored procedures for updating room prices and fetching detailed booking information with error handling.

## Database Schema

The database consists of the following tables:

- **GuestMaster**: Stores guest information.
- **Room**: Contains room details including type, price, and status.
- **Booking**: Records booking information including guest ID, room ID, and total amount.
- **StateMaster**: Maintains a list of states for guest location information.

## SQL Tasks

The following SQL queries are implemented in this project:

- Fetch guests who stayed for the same number of days.
- Find the second most expensive booking and the guest associated with it.
- Get the maximum room price per room type and the guest name.
- Count of guests sorted by room type.
- Fetch guests' first names with the total amount spent.
- Retrieve bookings with odd total amounts.
- Create a view for bookings with a total amount greater than $1000.
- Procedures to update room prices and fetch detailed booking information.

## Technologies Used

- SQL Server
- Database Management
- Data Analysis

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ManchesterHotelDb.git
