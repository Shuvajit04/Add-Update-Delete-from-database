# Add-Update-Delete-from-database
📘 Library Management System 
This project is a Library Management System built using MySQL. I created it as part of a database design task to practice schema creation, table relationships, and SQL data manipulation operations. The project was implemented using MySQL Workbench, where I first created a database named LibraryDB.

To begin, I identified the core entities required for a library system: Authors, Books, Categories, Members, Loans, and a junction table called BookAuthors to handle the many-to-many relationship between books and authors. Each table was created using CREATE TABLE statements, with appropriate data types, primary keys (like AuthorID, BookID, MemberID), and foreign key constraints to maintain referential integrity.

After setting up the schema, I used INSERT INTO statements to populate the tables with sample data. I added rows to each table, such as author names, book titles with ISBNs, categories, member details, and loan records. For certain fields that were optional or unknown at the time of insertion—like return dates for borrowed books—I used NULL values to handle the missing data gracefully.

To modify existing data, I used the UPDATE statement along with the WHERE clause. For example, I updated a member’s email address and modified a loan record to include a return date after the book was returned. Similarly, to remove incorrect or outdated records, I used the DELETE command with a condition, such as deleting a book by its title or removing a member by ID.

Throughout the process, I used commands like SHOW TABLES, DESCRIBE, and SELECT to verify the schema structure and inspect the inserted data. I also created an ER diagram in MySQL Workbench to visually represent the relationships between tables and ensure the design was consistent.

This project demonstrates a complete workflow for setting up a relational database system, performing data insertion, handling missing values, and using update and delete operations in a real-world context.
