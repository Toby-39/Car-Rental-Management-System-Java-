 Car Rental Management System

A car rental management system built in Java, applying core OOP principles across a multi-class inheritance structure, with role-based access and persistent JSON storage.

 Features
- **14 classes across 2 inheritance hierarchies**:
  - `Car` → 7 subtypes (Sedan, SUV, MPV, Coupe, SportsCar, Hybrid, EV)
  - `User` → Customer, Employee → Staff, Admin
- **Role-based access control**: Admin-only permissions for account creation, membership tier changes, and password resets restricted from Staff
- **Data persistence**: all records (cars, customers, employees, rentals) saved across sessions via JSON, with zero data loss on restart
- **Secure authentication** for Admin and Staff logins
 Tech Stack
- Java
- OOP (inheritance, polymorphism)
- JSON (data persistence)



 What I Learned
Designing two separate inheritance hierarchies (Car and User) taught me how to reduce duplicate logic through polymorphism, and implementing role restrictions gave me a concrete sense of why access control needs to be enforced at the data layer, not just hidden in the UI.
