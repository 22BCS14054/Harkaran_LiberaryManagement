Problem Statement:-
Libraries often face challenges in efficiently managing books, members, and borrowing activities.
Manual or outdated systems can lead to errors, difficulties in tracking availability, and poor visibility into member activities and book usage patterns.
The Library Book Tracking System aims to streamline library operations by providing a structured way to manage books, members, and borrowing records, while
also offering analytical insights to support decision-making.


 Business Problems:-
 Book Management Issues – Lack of a centralized system to track book availability, genres, and publication details.
 Member Tracking Challenges – Inefficient handling of member details and their borrowing activities.
 Borrowing Records – Difficulty in tracking which members borrowed which books, including overdue returns.
 Lack of Insights – No visibility into popular books, borrowing trends, or member engagement.


  Project Objectives:-
  
  Book Management:-
        Store details such as title, author, genre, publication year, and availability.
        Support CRUD operations for book records.
  Member Management:-
        Maintain member details (name, contact, membership start date).
        Support CRUD operations for member records.
  Borrowing Management:-
        Record borrowing and returning of books.
        Track due dates and availability status.

 Analytical Insights:-
        Generate a list of currently borrowed books.
        View the borrowing history of individual members.

 Approach:-
        Database Schema Design
        Books Table → book_id, title, author, genre, publication_year, availability.
        Members Table → member_id, name, contact_info, membership_start_date.
        Borrowed_Books Table → borrow_id, book_id (FK), member_id (FK), borrow_date, return_date.

         CRUD Operations:
               Add, update, retrieve, delete books and members.
               Record borrow/return transactions with proper availability checks.
         Analytical Queries & Reports:
              Query for all books currently borrowed.
              Query borrowing history of a given member.
              Query borrowing history of a given member.
              Query to find the most borrowed books by frequency.

Expected Outputs:-
              Book & Member Management – Clean records with easy CRUD operations.
              Borrowing Tracker – Clear visibility into borrowed vs available books.
              Insights & Reports –

                         List of all borrowed books at any time.
                         Member borrowing history reports.
                         Most borrowed books with statistics.
        
        


        
