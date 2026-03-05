# CollegeClub-DatabaseM

## Overview


This Project implements a normalized relational database for managing college club memberships. It was developed to demonstrate database design, normalization (1NF, 2NF, 3NF), and SQL operations.

## Database Structure:

The System consists of three tables:
- Student - Stores students details
- Club - Stores club information
- Membership - Junction table linking students and clubs

## Features
- INSERT and SELECT operations
- JOIN queries to combine data across tables
- Normalization upto Third Normal Form (3NF)

## Task 1 – Secure Data Exchange
The task explores encoding techniques such as Base64, ASCII, URL encoding, and hexadecimal encoding, and explains how these formats are used during data transmission. It also examines how protocols such as HTTPS, TLS, and SMTP enable secure communication between systems.

## Task 2 – Computational Problem Solving
This section analyzes a classroom seating arrangement problem using concepts from computational complexity and algorithm design.

The problem involves arranging students in a way that prevents friends or students from the same city from sitting next to each other. Two approaches are explored:

Brute Force Approach, where every possible seating arrangement is generated and tested.

Heuristic Approach, where a smarter strategy is used to reduce the number of arrangements that need to be checked.

## Task 3 – Database Normalization
This section demonstrates the design of a relational database for managing college club memberships.
The database was normalized up to Third Normal Form (3NF) to remove redundancy and improve data integrity. The system includes three main entities:
- Student
- Club
- Membership

The SQL scripts provided demonstrate:
- Table creation with primary and foreign keys
- Data insertion
- Basic data retrieval queries
- JOIN operations to combine related data across tables
