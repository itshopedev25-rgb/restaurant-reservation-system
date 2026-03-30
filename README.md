# Restaurant Reservation System

\*\*Course:\*\* CSC239 Database Project  

\*\*College:\*\* Middlesex College — Spring 2026  

## Team

* Wiafe (itshopedev)
* Sean
* Oleskii

## Technology

* \## Technology Stack
* \- \*\*Database:\*\* PostgreSQL (hosted on EC2; tested on DBeaver locally / Apex for school grading)
* \- \*\*SQL Scripts:\*\* Table creation, sample data, queries  
* \- \*\*Version Control:\*\* Git \& GitHub

## Project Structure

* restaurant-reservation-system/
* ├── README.md # Project overview
* ├── schema/ # Table creation scripts
* │ └── create\_tables.sql
* ├── data/ # Sample data insertion scripts
* │ └── insert\_data.sql
* ├── queries/ # SQL query scripts for testing
* │ └── queries.sql
* └── diagrams/ # ERD and other design diagrams
* └── ERD.png

## Description



\---



\## Description

This database system manages \*\*restaurant reservations\*\* and related operations. It currently supports:  



\- \*\*Customers\*\* — storing personal details  

\- \*\*Reservations / Bookings\*\* — tracking table bookings  

\- \*\*Orders / Order Lines\*\* — tracking customer orders (future tables)  

\- \*\*Staff Management\*\* — staff roles and assignments (future tables)  



The system is designed so that \*\*anyone can run the SQL scripts\*\* to recreate the database schema and sample data. Queries can then be run for testing and reporting.  



\---



\## Installation / Setup

To run this project locally:  



1\. \*\*Clone the repository:\*\*

```bash

git clone https://github.com/itshopedev25-rgb/restaurant-reservation-system.git

cd restaurant-reservation-system

