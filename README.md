# AirlineReservation-EERD
Enhanced Entity Relationship Diagram (EERD) for an Airline Reservation System focusing on enterprise-level system modeling and database design.

# AirlineReservation-EERD

## Overview
This project presents an **Enhanced Entity Relationship Diagram (EERD)** for an **Airline Reservation System**.
It models the core operations of airline management including **passengers, employees, flights, aircraft, airports, tickets, and payments**.

The system is designed to demonstrate **enterprise-level data modeling** and structured system abstraction suitable for large-scale applications.

---

## Design & Research Objective
- Model a real-world airline reservation system using EERD concepts
- Capture complex relationships between entities
- Represent specialization and role-based entities (Passenger, Employee)
- Build a foundation for future database or software implementation

---

## Core Entities

### Person (Super Entity)
- Person_ID
- Name
- Email
- Phone

### Passenger (Subclass)
- Passenger_ID
- Nationality
- Passport_No

### Employee (Subclass)
- Emp_ID
- Salary
- Hire_Date

### Flight
- Flight_ID
- Source
- Destination
- Departure_Time
- Arrival_Time

### Aircraft
- Aircraft_ID
- Model
- Capacity

### Airport
- Airport_ID
- Airport_Name
- City
- Country

### Ticket
- Ticket_ID
- Seat_No
- Booking_Date

### Fare
- Amount

### Payment
- Payment_ID
- Payment_Date
- Amount
- Method

---

## Key Relationships
- A **Person** can be a Passenger or an Employee
- A **Passenger** books one or more tickets
- Each **Ticket** includes fare and seat assignment
- A **Flight** operates using an aircraft
- Flights depart from and arrive at airports
- A **Passenger** pays for a ticket via a payment record
- Employees manage flight and operational activities

---

## Design Highlights
- Use of **specialization (Person → Passenger, Employee)**
- Separation of operational and transactional data
- Realistic modeling of airline operations
- Suitable for enterprise-scale systems

---

## Research Perspective
This EERD demonstrates:
- Advanced database modeling concepts
- Enterprise system abstraction
- Readiness for large data-driven applications

Such modeling is commonly used in **database research, information systems, and large-scale software platforms**.

---

## Future Work
- Convert EERD into relational schema
- Implement database using SQL
- Analyze booking and payment workflows
- Extend system for multi-airline integration

---

## Tools Used
- Draw.io (EERD design)
- Conceptual database design principles

---

## Author
Farwa Ch  
BS Computer Science, 4th Semester   
Interests: System Design, Databases, Software Engineering

