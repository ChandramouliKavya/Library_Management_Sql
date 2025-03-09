# Library Management System

**📌 Project Overview**

This project is a Library Management System that organizes and manages books, members, and transactions efficiently using SQL. The database consists of multiple relational tables to ensure data integrity and smooth operations

## 🛠️ Database Schema & Relationships 

The system consists of the following main tables:

**1.Books** - Stores book details

**2.Members** - Stores member information

**3.Transactions** - Records book borrowing and returning

**4.Authors** - Stores author details

**5.Categories** - Categorizes books into genres

## Table Relationships

Each book belongs to one category but a category can have multiple books.

A book can have multiple authors (Many-to-Many Relationship).

A member can borrow multiple books, recorded in the transactions table.

The transactions table maintains foreign key constraints with books and members.


## 🚀 Features Implemented

✅ Add, update, and delete book records

✅ Manage member registrations

✅ Track book borrow and return transactions

✅ Generate reports on borrowed books, late returns, and popular books

✅ Maintain relationships between books, authors, and categories

💡 Future Enhancements

🔹 Implement user authentication for admin and members

🔹 Add book reservation system

🔹 Develop a web interface to interact with the database

🤝 Contributing

Feel free to fork the repository, raise issues, or submit pull requests. Any contributions to improve this project are welcome!
