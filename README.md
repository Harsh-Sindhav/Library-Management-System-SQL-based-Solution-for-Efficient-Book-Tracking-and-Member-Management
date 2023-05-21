# Library Management System

This project aims to create a Library Management System using SQL to efficiently track books, members, and book loans. It includes a set of SQL queries that enable basic functions such as issuing and returning books, calculating fines, and retrieving information about the library's collection and members.

## Features

- Create tables: `books`, `members`, `issuedbooks`, and `finetable`, to store relevant data.
- Insert dummy values into the tables for testing purposes.
- Retrieve all information from the `books` table.
- Retrieve the names of all members from the `members` table.
- Retrieve book details including name, author, quantity, and publication.
- Retrieve the member name, book name, and issue date for all books borrowed by a specific member.
- Retrieve member ID, name, and email for members with names starting with 'J'.
- Retrieve member name, book name, and fine amount paid for members who have cleared their fines.
- Find member details (name, email, contact), book name, and issue date for members who haven't returned any books yet.

## Usage

To use this Library Management System, you need to have a SQL database and execute the provided SQL queries. Modify the queries as needed to match your database structure and requirements.
