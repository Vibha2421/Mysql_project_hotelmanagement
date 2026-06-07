This repository contains a comprehensive suite of MySQL queries, subqueries, joins, views, and automation triggers designed to manage and optimize backend hotel operations. The project simulates real-world hotel administration scenarios, providing data-driven solutions for accounts, reception, operations, finance, and human resource management teams.
<br>
**Database Schema**
<br>
**1. Customers Table**
CustomerID (Primary Key)

FirstName, LastName

Phone, Email, City
<br>

**2. Rooms Table**
RoomID (Primary Key)

RoomType (e.g., Suite, Family, Deluxe)

PricePerNight, Capacity
<br>

**3. Staff Table**
StaffID (Primary Key)

FirstName, LastName

Role (e.g., Manager, Chef, Waiter)

Phone, Email
<br>

**4. Bookings Table**
BookingID (Primary Key)

CustomerID (Foreign Key referencing Customers)

RoomID (Foreign Key referencing Rooms)

StaffID (Foreign Key referencing Staff)

CheckInDate, CheckOutDate

TotalAmount

<br>
**5. Payments Table**
PaymentID (Primary Key)

BookingID (Foreign Key referencing Bookings)

PaymentMethod (e.g., UPI, Card, Online, Credit Card)

Amount, PaymentDate


