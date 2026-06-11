# Cinema Management System – Seat Reservation Module

## Overview

This repository contains the analysis and design of the **Seat Reservation Module** of a Cinema Management System (CMS), developed as part of a university project in Business Information Systems Modeling.

The project focuses on modeling business processes and designing a software architecture that supports customer reservations, seat management, and reservation-related services within a cinema environment.

---

## Project Scope

The Seat Reservation Module provides functionality for managing customer reservations and related services.

### Implemented Use Cases

* Create Reservation
* Cancel Reservation
* Check Reservation Status
* Modify Reservation
* Add Snacks & Beverages to a Reservation

The system supports interactions between customers and cinema employees while ensuring seat availability and reservation validation.

---

## UML Modeling

The project was designed using **Astah UML** and includes multiple UML artifacts covering both analysis and design perspectives.

### Use Case Diagram

Models the interactions between customers, cinema employees, and the reservation subsystem.
![Use Case Diagram](screenshots/Screenshot%205.png)


### Analysis Class Diagram

Represents the business entities and their relationships, including:

* Reservation
* Customer
* Cinema Employee
* Seat
* Screening
* Cinema Hall
* Snack Item

![Analysis Class Diagram](screenshots/Screenshot%204.png)

### Design Class Diagram

Defines the software architecture and object-oriented design, including:

* Controllers
* Domain Classes
* Interfaces
* Business Logic
* Data Access Components

![Design Class Diagram](screenshots/Screenshot%202.png)

### Sequence Diagrams

#### Reservation Creation

Illustrates the complete workflow of creating a reservation, including:

* Seat availability checks
* Reservation validation
* Temporary seat blocking
* Reservation persistence

![Reservation Creation Sequence Diagram](screenshots/Screenshot%201.png)
#### Add Snacks & Beverages

Illustrates how additional products can be attached to an existing reservation.

![Add Snacks & Beverages Sequence Diagram](screenshots/Screenshot%203.png)



## Learning Outcomes

During this project, the following skills were applied and improved:

* Requirements Analysis
* Business Process Modeling
* UML Modeling
* Object-Oriented Analysis and Design
* Software Architecture Design
* Sequence Modeling
* System Documentation



## Disclaimer

This repository was created for educational purposes as part of a university software modeling project. The focus of the project is system analysis and design rather than software implementation.
