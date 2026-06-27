Advanced Generative AI
Software Development Using Generative AI
Application Chosen:
College Library Management System
________________________________________
PHASE 1 – REQUIREMENTS ANALYSIS
Tool Used
ChatGPT
________________________________________
Prompt 1
I am developing a College Library Management System as part of my Software Development using Generative AI assignment.
Act as a Business Analyst and Software Requirements Engineer.
Generate a complete Requirements Analysis for this application in the following format.
1. Raw User Feedback
Write 15 realistic feedback messages from imaginary users (students, librarians, and administrators). Include a mix of:
•	Complaints
•	Feature requests
•	Positive feedback
•	Suggestions for improvement
Make the feedback sound natural and realistic.
________________________________________
2. Requirements Table
Based on the user feedback, extract and organize the software requirements in a table with the following columns:
•	Requirement ID
•	Requirement Description
•	Category (Functional / Non-Functional)
•	Priority (High / Medium / Low)
Include at least 15 requirements.
________________________________________
3. User Stories
Convert all High Priority Functional Requirements into Agile User Stories using the format:
As a ,
I want ,
So that .
Generate at least 8 user stories.
________________________________________
4. Non-Functional Requirements
Identify at least 10 Non-Functional Requirements covering topics such as:
•	Performance
•	Security
•	Reliability
•	Availability
•	Scalability
•	Maintainability
•	Usability
•	Compatibility
•	Backup & Recovery
•	Data Privacy
Present them in a table with the following columns:
•	NFR ID
•	Requirement
•	Description
Format the entire response professionally using headings, tables, and bullet points so that it can be directly included in an assignment report.
________________________________________
Output
Requirements Analysis
College Library Management System
________________________________________
1. Raw User Feedback
The following feedback was collected from students, librarians, and administrators to understand the requirements for the College Library Management System.
Feedback 1 – Student
"I often forget the due date for borrowed books. It would be helpful if the system sent reminder notifications before the due date."
Feedback 2 – Student
"The online book search is useful, but I wish I could reserve a book when all copies are already issued."
Feedback 3 – Librarian
"Managing book records is much easier than before. However, editing multiple books one by one takes too much time."
Feedback 4 – Student
"The system becomes slow during examination periods when many students access it simultaneously."
Feedback 5 – Administrator
"It would be useful if the system generated monthly reports automatically instead of preparing them manually."
Feedback 6 – Student
"I like the clean interface. Finding books by title or author is very simple."
Feedback 7 – Librarian
"There should be barcode scanning support for issuing and returning books more quickly."
Feedback 8 – Student
"I want to renew my borrowed books online instead of visiting the library."
Feedback 9 – Student
"The mobile version needs improvement because some buttons are difficult to use."
Feedback 10 – Librarian
"The overdue fine calculation works correctly, but students should be able to view their fines directly from the dashboard."
Feedback 11 – Administrator
"The system should maintain backups regularly because losing library records would be a serious problem."
Feedback 12 – Student
"Dark mode would make reading easier, especially when using the system at night."
Feedback 13 – Librarian
"I would like inventory alerts whenever the number of available books becomes very low."
Feedback 14 – Student
"It would be great if I could log in using my college email account instead of creating another password."
Feedback 15 – Administrator
"Overall, the software has reduced paperwork significantly. Better security and role-based access would make it even more reliable."
________________________________________
2. Requirements Table
Requirement ID	Requirement Description	Category	Priority
FR-01	Users shall search books by title, author, ISBN, and category.	Functional	High
FR-02	Students shall reserve unavailable books online.	Functional	High
FR-03	Students shall renew borrowed books online.	Functional	High
FR-04	The system shall send due-date reminder notifications.	Functional	High
FR-05	Librarians shall manage book records (Add, Edit, Delete).	Functional	High
FR-06	The system shall support barcode scanning for issue and return operations.	Functional	High
FR-07	Students shall view overdue fines on their dashboard.	Functional	Medium
FR-08	Administrators shall generate monthly library reports automatically.	Functional	High
FR-09	The system shall provide inventory alerts for low-stock books.	Functional	Medium
FR-10	Users shall log in using college email credentials.	Functional	High
NFR-01	The system shall respond to user requests within 3 seconds.	Non-Functional	High
NFR-02	The application shall support mobile-responsive design.	Non-Functional	Medium
NFR-03	The system shall provide regular automated backups.	Non-Functional	High
NFR-04	The application shall implement role-based security.	Non-Functional	High
NFR-05	The system shall support dark mode for better usability.	Non-Functional	Low
________________________________________
3. User Stories
User Story 1
As a student,
I want to search books using title, author, ISBN, or category,
So that I can quickly find the books I need.
________________________________________
User Story 2
As a student,
I want to reserve books that are currently unavailable,
So that I can receive them when they become available.
________________________________________
User Story 3
As a student,
I want to renew borrowed books online,
So that I do not need to visit the library in person.
________________________________________
User Story 4
As a student,
I want reminder notifications before the due date,
So that I can avoid paying overdue fines.
________________________________________
User Story 5
As a librarian,
I want to manage book records efficiently,
So that the library database remains accurate and up to date.
________________________________________
User Story 6
As a librarian,
I want barcode scanning during issue and return operations,
So that transactions become faster and more accurate.
________________________________________
User Story 7
As an administrator,
I want monthly reports to be generated automatically,
So that I can monitor library activities without manual effort.
________________________________________
User Story 8
As a user,
I want to log in using my college email account,
So that I can access the system securely without remembering another password.
________________________________________
4. Non-Functional Requirements
NFR ID	Requirement	Description
NFR-01	Performance	The system shall respond to user requests within 3 seconds under normal load.
NFR-02	Security	All passwords shall be encrypted and stored securely.
NFR-03	Reliability	The system shall maintain accurate transaction records with minimal failures.
NFR-04	Availability	The application shall be available 24×7 with at least 99.5% uptime.
NFR-05	Scalability	The system shall support increasing numbers of users and books without performance degradation.
NFR-06	Maintainability	The software shall use modular architecture for easier updates and maintenance.
NFR-07	Usability	The interface shall be intuitive and easy for students, librarians, and administrators to use.
NFR-08	Compatibility	The system shall work on modern web browsers and mobile devices.
NFR-09	Backup & Recovery	Automatic backups shall be performed daily, with data restoration available in case of failure.
NFR-10	Data Privacy	User information shall be protected according to institutional privacy policies, and access shall be restricted based on user roles.
________________________________________
Summary
The Requirements Analysis identifies the needs of three primary stakeholders—students, librarians, and administrators. The analysis resulted in 15 software requirements, including both functional and non-functional requirements. High-priority functional requirements were transformed into 8 Agile user stories, while 10 non-functional requirements define the expected quality attributes of the College Library Management System. These requirements provide a strong foundation for the design, development, testing, and deployment phases of the software development lifecycle.
________________________________________
Prompt 2
Design a modern, clean, and responsive College Library Management System with three connected wireframes.
Screen 1 – Home Screen
Create the main landing page for students and librarians.
Include:
•	Header with logo "Smart Library"
•	Navigation Menu (Home, Books, Categories, About, Contact)
•	Login and Register buttons
•	Search bar with "Search books, authors, or ISBN"
•	Featured Books section
•	Book Categories
•	Latest Announcements
•	Quick Statistics (Total Books, Available Books, Active Members)
•	Footer with contact information and social media links
Screen 2 – Book Borrowing Screen (Main Action Screen)
Design the primary action page where students borrow books.
Include:
•	Student Profile section
•	Search Book field
•	Filter by Category and Author
•	Available Books table
•	Book Details panel
•	Borrow Book button
•	Return Date selector
•	Borrowing Status message
•	Navigation buttons (Back to Home, Dashboard)
Screen 3 – Student Dashboard (Summary Screen)
Design a dashboard showing the user's current status.
Include:
•	Welcome message with student name
•	Profile summary
•	Currently Borrowed Books
•	Due Dates
•	Fine Amount
•	Borrow History
•	Notifications and Alerts
•	Recently Viewed Books
•	Recommended Books
•	Logout button
Design Requirements
•	Minimalist modern UI
•	Blue and white color theme
•	Material Design style
•	Desktop web application layout
•	Consistent navigation across all three screens
•	Professional wireframe with placeholders and icons only (no detailed graphics)
Also ensure that the three screens are connected in the following user flow:
Home Screen → Borrow Book Screen → Student Dashboard.
.
________________________________________Output
 
  
________________________________________
Prompt 3
I am developing a College Library Management System. Act as a Software Architect and Database Designer.
Generate a complete technical design for this application.
Part 1 – System Architecture Diagram
Create a professional system architecture diagram that includes the following components and clearly shows the data flow between them.
Frontend
•	HTML5
•	CSS3
•	Bootstrap
•	JavaScript
Backend
•	Python
•	Flask Framework
Database
•	SQLite
External Services
•	Email Notification Service (for due date reminders)
•	Authentication Service (Login/Registration)
Show arrows indicating communication between the Frontend, Backend, Database, and External Services.
________________________________________
Part 2 – Entity Relationship (ER) Diagram
Design an ER Diagram for the College Library Management System.
Include the following tables with fields, Primary Keys (PK), Foreign Keys (FK), and relationships.
Students
•	student_id (PK)
•	name
•	email
•	phone
•	department
•	year
Librarians
•	librarian_id (PK)
•	name
•	email
•	phone
Authors
•	author_id (PK)
•	author_name
Categories
•	category_id (PK)
•	category_name
Books
•	book_id (PK)
•	title
•	isbn
•	publication_year
•	available_copies
•	author_id (FK)
•	category_id (FK)
Borrow_Records
•	borrow_id (PK)
•	student_id (FK)
•	book_id (FK)
•	librarian_id (FK)
•	borrow_date
•	due_date
•	return_date
•	status
Show all one-to-many relationships clearly.
________________________________________
Part 3 – Database SQL
Generate SQLite CREATE TABLE statements for all the above tables.
Include:
•	PRIMARY KEY constraints
•	FOREIGN KEY constraints
•	Appropriate data types
•	NOT NULL constraints wherever applicable
________________________________________
Part 4 – Database Explanation
Provide a short explanation (3–5 lines each) describing:
•	Why each table exists
•	What data it stores
•	How it relates to the other tables
Format the entire output professionally using headings and code blocks.
________________________________________
Output
 
 
Technical Design Document: College Library Management System
1. Overview
This Technical Design Document (TDD) describes the database design and implementation for the College Library Management System. The system enables students to borrow and return books, librarians to manage library operations, and administrators to oversee the entire system. This document focuses on the database layer, providing complete SQLite schema definitions and detailed explanations of the data model.
The system architecture, as shown in the architecture diagram, consists of a Frontend (HTML5, CSS3, Bootstrap, JavaScript), a Backend (Flask/Python with REST API), and a Database Layer (SQLite). This document details the SQLite database implementation that supports the application.
________________________________________
2. Goals and Non-Goals
Goals
•	Define a normalized, efficient database schema for library management
•	Establish referential integrity through foreign key constraints
•	Support all core library operations: cataloging, borrowing, returning, and user management
•	Provide clear documentation for each database entity
Non-Goals
•	Database migration strategies (covered in deployment documentation)
•	Query optimization and indexing strategies (future enhancement)
•	Data archival and retention policies
________________________________________
3. Database Schema (SQL Definitions)
The following SQLite CREATE TABLE statements implement the data model shown in the entity-relationship diagram.
3.1 Authors Table
CREATE TABLE Authors (
    author_id    TEXT PRIMARY KEY,
    author_name  TEXT NOT NULL
);
3.2 Categories Table
CREATE TABLE Categories (
    category_id    TEXT PRIMARY KEY,
    category_name  TEXT NOT NULL
);
3.3 Students Table
CREATE TABLE Students (
    student_id  TEXT PRIMARY KEY,
    name        TEXT NOT NULL,
    email       TEXT NOT NULL UNIQUE,
    phone       TEXT,
    department  TEXT NOT NULL,
    year        TEXT NOT NULL
);
3.4 Librarians Table
CREATE TABLE Librarians (
    librarian_id  TEXT PRIMARY KEY,
    name          TEXT NOT NULL,
    email         TEXT NOT NULL UNIQUE,
    phone         TEXT
);
3.5 Books Table
CREATE TABLE Books (
    book_id           TEXT PRIMARY KEY,
    title             TEXT NOT NULL,
    isbn              TEXT NOT NULL UNIQUE,
    publication_year  TEXT,
    available_copies  INTEGER NOT NULL DEFAULT 0,
    author_id         TEXT NOT NULL,
    category_id       TEXT NOT NULL,
    FOREIGN KEY (author_id) REFERENCES Authors(author_id)
        ON DELETE RESTRICT ON UPDATE CASCADE,
    FOREIGN KEY (category_id) REFERENCES Categories(category_id)
        ON DELETE RESTRICT ON UPDATE CASCADE
);
3.6 Borrow_Records Table
CREATE TABLE Borrow_Records (
    borrow_id     TEXT PRIMARY KEY,
    student_id    TEXT NOT NULL,
    book_id       TEXT NOT NULL,
    librarian_id  TEXT NOT NULL,
    borrow_date   TIMESTAMP NOT NULL DEFAULT CURRENT_TIMESTAMP,
    due_date      TIMESTAMP NOT NULL,
    return_date   TIMESTAMP,
    status        TEXT NOT NULL DEFAULT 'BORROWED' 
                  CHECK (status IN ('BORROWED', 'RETURNED', 'OVERDUE')),
    FOREIGN KEY (student_id) REFERENCES Students(student_id)
        ON DELETE RESTRICT ON UPDATE CASCADE,
    FOREIGN KEY (book_id) REFERENCES Books(book_id)
        ON DELETE RESTRICT ON UPDATE CASCADE,
    FOREIGN KEY (librarian_id) REFERENCES Librarians(librarian_id)
        ON DELETE RESTRICT ON UPDATE CASCADE
);
3.7 Complete Schema Script
-- College Library Management System
-- SQLite Database Schema
-- Enable foreign key support (required for SQLite)
PRAGMA foreign_keys = ON;

-- Authors Table
CREATE TABLE Authors (
    author_id    TEXT PRIMARY KEY,
    author_name  TEXT NOT NULL
);

-- Categories Table
CREATE TABLE Categories (
    category_id    TEXT PRIMARY KEY,
    category_name  TEXT NOT NULL
);

-- Students Table
CREATE TABLE Students (
    student_id  TEXT PRIMARY KEY,
    name        TEXT NOT NULL,
    email       TEXT NOT NULL UNIQUE,
    phone       TEXT,
    department  TEXT NOT NULL,
    year        TEXT NOT NULL
);

-- Librarians Table
CREATE TABLE Librarians (
    librarian_id  TEXT PRIMARY KEY,
    name          TEXT NOT NULL,
    email         TEXT NOT NULL UNIQUE,
    phone         TEXT
);

-- Books Table
CREATE TABLE Books (
    book_id           TEXT PRIMARY KEY,
    title             TEXT NOT NULL,
    isbn              TEXT NOT NULL UNIQUE,
    publication_year  TEXT,
    available_copies  INTEGER NOT NULL DEFAULT 0,
    author_id         TEXT NOT NULL,
    category_id       TEXT NOT NULL,
    FOREIGN KEY (author_id) REFERENCES Authors(author_id)
        ON DELETE RESTRICT ON UPDATE CASCADE,
    FOREIGN KEY (category_id) REFERENCES Categories(category_id)
        ON DELETE RESTRICT ON UPDATE CASCADE
);

-- Borrow_Records Table
CREATE TABLE Borrow_Records (
    borrow_id     TEXT PRIMARY KEY,
    student_id    TEXT NOT NULL,
    book_id       TEXT NOT NULL,
    librarian_id  TEXT NOT NULL,
    borrow_date   TIMESTAMP NOT NULL DEFAULT CURRENT_TIMESTAMP,
    due_date      TIMESTAMP NOT NULL,
    return_date   TIMESTAMP,
    status        TEXT NOT NULL DEFAULT 'BORROWED' 
                  CHECK (status IN ('BORROWED', 'RETURNED', 'OVERDUE')),
    FOREIGN KEY (student_id) REFERENCES Students(student_id)
        ON DELETE RESTRICT ON UPDATE CASCADE,
    FOREIGN KEY (book_id) REFERENCES Books(book_id)
        ON DELETE RESTRICT ON UPDATE CASCADE,
    FOREIGN KEY (librarian_id) REFERENCES Librarians(librarian_id)
        ON DELETE RESTRICT ON UPDATE CASCADE
);
________________________________________
4. Database Entity Explanations
4.1 Authors
The Authors table stores information about book authors in the library system. Each author is uniquely identified by an author_id and has a required author_name field. This table exists to normalize author data, preventing redundancy when multiple books share the same author. It maintains a one-to-many relationship with the Books table, where one author can write multiple books.
4.2 Categories
The Categories table maintains the classification system for organizing books in the library. It stores category identifiers and names (e.g., "Fiction", "Science", "History"). This table enables efficient book organization and search functionality. Categories have a one-to-many relationship with Books, allowing multiple books to belong to the same category while ensuring consistent categorization across the system.
4.3 Students
The Students table stores registered student information who are authorized to borrow books from the library. It captures essential details including student identification, contact information (email, phone), academic department, and current year of study. This table is central to the borrowing workflow, as every borrow transaction must be linked to a valid student record through the Borrow_Records table.
4.4 Librarians
The Librarians table maintains records of library staff members who process borrowing and return transactions. Each librarian has a unique identifier and contact information. This table supports accountability and audit trails by recording which librarian processed each transaction. It relates to Borrow_Records, ensuring every library transaction is associated with a responsible staff member.
4.5 Books
The Books table is the core catalog of the library, storing all book information including title, ISBN, publication year, and available copy count. It references both the Authors and Categories tables through foreign keys, establishing the book's authorship and classification. The available_copies field is critical for managing inventory and determining whether a book can be borrowed.
4.6 Borrow_Records
The Borrow_Records table is the transactional heart of the system, tracking all borrowing activities. It records which student borrowed which book, processed by which librarian, along with critical dates (borrow, due, return) and current status. This table establishes relationships with Students, Books, and Librarians, creating a complete audit trail. The status field enables tracking of overdue books for the Email Service notifications shown in the architecture diagram.
________________________________________
5. Security Considerations
•	Data Integrity: Foreign key constraints with ON DELETE RESTRICT prevent orphaned records
•	Input Validation: CHECK constraints on status field prevent invalid data entry
•	Unique Constraints: Email and ISBN uniqueness prevents duplicate entries
•	Authentication Integration: The schema supports the Authentication service shown in the architecture diagram through the Students and Librarians tables
________________________________________
6. Testing Strategy
Test Type
+
+
+	Description
+
Schema Validation
+	Verify all tables create successfully with constraints
Referential Integrity
+	Test foreign key enforcement on insert/update/delete
Constraint Testing
+	Validate CHECK constraints and NOT NULL enforcement
CRUD Operations
+	Test all basic operations through the REST API layer
________________________________________
7. Rollout Plan
1.	Phase 1: Deploy schema to development environment
2.	Phase 2: Seed reference data (Categories, sample Authors)
3.	Phase 3: Integration testing with Flask backend
4.	Phase 4: Production deployment with initial data migration

________________________________________
Prompt 4
Module 1 – Database Setup
Generate complete Python code for Google Colab to create a College Library Management System using SQLite.
Requirements:
•	Import all required libraries.
•	Create a SQLite database named library.db.
•	Create the following tables:
o	Students
o	Librarians
o	Authors
o	Categories
o	Books
o	Borrow_Records
•	Add appropriate PRIMARY KEY and FOREIGN KEY constraints.
•	Insert at least 5 sample records into each table.
•	Commit all changes.
•	Print the total record count for each table.
•	Include comments explaining each section of the code.
•	Ensure the code runs successfully in Google Colab without modification.

Module 2 – Core Data FunctionsGenerate complete Python code for Google Colab that connects to the existing library.db SQLite database.
Create the following functions:
1.	Search books by title.
2.	Search books by author.
3.	Filter books by category.
4.	List all available books.
5.	List books currently borrowed by a specific student.
6.	Display all borrowing records.
After creating the functions, test each one with sample inputs and print the results.
Use clear comments and ensure the code runs successfully in Google Colab.
Module 3 – Main Business Function
Generate complete Python code for the main business function of a College Library Management System.
Create a function named borrow_book() that:
•	Accepts Student ID and Book ID as input.
•	Validates whether the student exists.
•	Validates whether the book exists.
•	Checks if copies are available.
•	Prevents duplicate borrowing of the same book before it is returned.
•	Inserts a new record into the Borrow_Records table.
•	Updates the available copies in the Books table.
•	Displays a success confirmation message.
Also generate test cases showing:
•	Successful borrowing
•	Invalid Student ID
•	Invalid Book ID
•	No copies available
•	Duplicate borrowing attempt
Ensure the code runs successfully in Google Colab.
Module 4 – HTML Frontend
Generate complete Python code for Google Colab that creates a simple HTML frontend for the College Library Management System using IPython.display.HTML.
The webpage should include:
•	A professional header with the application name.
•	A navigation bar.
•	A welcome section.
•	A responsive grid displaying books retrieved from the SQLite database.
•	A Student Status section showing:
o	Total books borrowed
o	Active borrowings
o	Due books
•	A footer with copyright information.
Style the page using embedded CSS with a modern blue-and-white theme.
Display the page inside Google Colab using IPython.display.HTML.
Ensure the code runs successfully without modification.
________________________________________
Output
 

 
 
 
PHASE-5
PROMPT:
Using the College Library Management System Python code above, generate a complete automated testing script for Google Colab.

The test suite must match the existing database schema and function names exactly.

The database is **library.db**.

Tables:

* Students
* Librarians
* Authors
* Categories
* Books
* Borrow_Records

Existing functions:

* search_book_by_title()
* search_book_by_author()
* filter_books_by_category()
* list_available_books()
* books_borrowed_by_student()
* display_all_borrow_records()
* borrow_book()

Generate a complete Python script that performs the following tests.

## Test Group 1 – Database Structure

Verify that the following tables exist:

* Students
* Librarians
* Authors
* Categories
* Books
* Borrow_Records

## Test Group 2 – Data Quality

Verify:

* Student Name is not NULL
* Librarian Name is not NULL
* Author Name is not NULL
* Category Name is not NULL
* Book Title is not NULL
* Copies are never negative
* ISBN values are unique
* Student emails are unique

## Test Group 3 – Business Logic

Automatically test borrow_book().

Verify:

* Valid borrow succeeds.
* Copies decrease by one.
* Borrow record is inserted.
* Invalid Student ID is rejected.
* Invalid Book ID is rejected.
* Borrow fails when Copies = 0.
* Duplicate borrowing is prevented.

## Test Group 4 – Edge Cases

Test:

* search_book_by_title("XYZ123")
* search_book_by_author("Unknown Author")
* filter_books_by_category("Sports")
* books_borrowed_by_student(999)
* borrow_book(999,1001)
* borrow_book(101,9999)

Generate a professional PASS/FAIL report.

Display a table with:

Test Name
Category
Expected Result
Actual Result
Status

Finally display:

Total Tests
Passed
Failed
Pass Percentage

Print

"All critical tests passed successfully."

if every critical test passes.

Include comments throughout the code and ensure it runs directly after my existing notebook without modifying my application.
OUTPUT:
 
 
PHASE-6
PROMPT:
Generate complete Python code for Google Colab to simulate **Deployment Monitoring and a CI/CD Pipeline** for my **College Library Management System**. 
Requirements: 
### 1. Traffic Monitoring Simulation 
* Simulate API response time data for 10 consecutive minutes. 
* Generate realistic response times between 120 ms and 180 ms. 
* Inject a response time spike between **minutes 4 and 6** with values between **450 ms and 650 ms**. 
* Store the data in a Pandas DataFrame. 
* Display the DataFrame. 
### 2. Threshold Monitoring 
* Set a threshold of **300 ms**. 
* For every minute: 
* If response time is less than or equal to 300 ms, display **Normal**. 
* If response time is greater than 300 ms, display **ALERT**. 
### 3. AI Automated Actions 
Whenever an ALERT occurs, automatically display AI recovery actions such as: 
* Scaling application servers. 
* Restarting unhealthy service instances. 
* Clearing cache. 
* Load balancing incoming traffic. 
* Sending notification to DevOps team. 
### 4. CI/CD Pipeline Simulation 
Simulate the following deployment pipeline: 
* Source Code Commit 
* Build 
* Unit Testing 
* Integration Testing 
* Deployment 
* Monitoring 
* Production Ready 
Display each stage with a success message and appropriate emojis. 
### 5. Final Deployment Summary 
Display: 
* Total Monitoring Duration 
* Number of Alerts 
* Maximum Response Time 
* Average Response Time 
* Deployment Status 
If alerts are handled successfully, display: 
✅ Deployment Successful – AI Monitoring Stabilized the Application. 
Otherwise display: 
❌ Deployment Failed – Manual Intervention Required. 
### 6. Visualization 
Generate a Matplotlib line chart showing: 
* X-axis: Minutes (1–10) 
* Y-axis: API Response Time (ms) 
* Clearly highlight the spike during minutes 4–6. 
* Draw a horizontal threshold line at **300 ms**. 
Requirements: 
* Include comments throughout the code. 
* Use only Python, Pandas, and Matplotlib. 
* Ensure the code runs successfully in Google Colab without modification. 






OUTPUT:
 
PHASE-7
PROMPT:
Generate complete Python code for Google Colab to simulate Maintenance and Prediction for my College Library Management System.
Requirements:
1. Simulate Server Metrics
•	Simulate server metrics for 30 consecutive days.
•	Generate realistic values for:
o	Daily Users (between 300 and 1200)
o	Error Rate (%) (between 0.2% and 6%)
o	Database Load (%) (between 30% and 95%)
o	API Response Time (ms) (between 120 ms and 450 ms)
•	Store the data in a Pandas DataFrame.
2. Display Metrics
•	Display a table containing only the last 7 days of metrics with the following columns:
o	Day
o	Daily Users
o	Error Rate (%)
o	Database Load (%)
o	Response Time (ms)
3. Predict Future Issues
Using the simulated data, predict approximately how many days remain before each metric reaches its critical threshold.
Use these thresholds:
•	Daily Users: 1500 users
•	Error Rate: 8%
•	Database Load: 95%
•	Response Time: 500 ms
Display the predictions in a formatted table with:
•	Metric
•	Current Value
•	Critical Threshold
•	Estimated Days Remaining
•	Risk Level (Low / Medium / High)
4. Maintenance Recommendations
Generate a prioritized list of at least 5 maintenance recommendations.
For each recommendation include:
•	Recommendation
•	Reason
•	Urgency Level (Low / Medium / High)
Example recommendations:
•	Scale application servers.
•	Optimize SQL queries.
•	Archive old borrowing records.
•	Increase database indexing.
•	Enable automatic backups.
•	Upgrade server resources.
•	Improve caching strategy.
5. Reflection
Generate a short reflection paragraph (approximately 100–150 words) explaining:
•	Which predicted issue is the most concerning.
•	Why it could affect the College Library Management System.
•	How proactive maintenance can reduce downtime and improve user experience.
6. Visualization
Generate four separate Matplotlib charts:
1.	Daily Users over 30 days.
2.	Error Rate over 30 days.
3.	Database Load over 30 days.
4.	Response Time over 30 days.
Requirements:
•	Use Python, Pandas, NumPy, and Matplotlib only.
•	Include comments throughout the code.
•	Ensure the code runs successfully in Google Colab without modification.

OUTPUT:
 
 
 
