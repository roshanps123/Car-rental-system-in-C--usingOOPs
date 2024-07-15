This project implements a Car Rental System in C++ using Object-Oriented Programming (OOP) concepts. The system is designed to manage car rentals for customers and employees, maintaining separate databases for each, along with the cars available for rent. Key features include:

Record Management:

Customers and Employees: Keeps track of car rentals, updates records based on factors like return delays, damages, and condition of returned cars.
Cars: Maintains a list of cars available for rent, their condition, and other details.
Functionalities:

Customers: Can view available cars, browse currently rented cars, and rent cars based on their customer record. New customers can be registered with an average record value, and fines are imposed for late returns.
Employees: Similar to customers but with a 15% discount on rentals.
Managers: Can add, update, or delete customers, employees, and cars. They can also view all cars and their rental statuses.
OOP Concepts:

Classes: Separate classes for customers, employees, and managers, utilizing inheritance, polymorphism, and data abstraction.
Methods: Each method is appropriately placed within its class, using private and public attributes as needed.
Data Handling:

File Handling: Utilizes file handling for data storage and retrieval.
Database Options: Optionally supports local databases like MySQL or MongoDB for data management.
This project ensures efficient and organized code, handling edge cases such as unavailability of cars, and demonstrates a strong understanding of OOP principles.
