# Database Management Systems Project


Web libraries are a common way to find, review, and keep track of content that the site specializes in. The contents vary from site to site, which can be movies, books, tv shows, places, restaurants and more, with sites like IMDB, Rotten Tomatoes, TripAdvisor, Yelp, Goodreads, Foursquare. For our project, we chose to imitate Goodreads, a book review site.

Classroom project on using a database, with a user interface that allows users to get, delete, update, and add entries to the DB.

## Features
- Home, book list, book details, book add/edit, user login/logout, register and user management pages
- Database operations for books, users
- Database tables for books, users, genres, languages
- Login and logout system

![image](https://user-images.githubusercontent.com/86553042/210796739-60eb8356-6904-49c6-9f7c-abcdaca22e03.png)

## Requirements

- Microsoft Visual Studio 2022,
- Latest ASP.NET version,
- Microsoft SQL Server,
- SQL Server Management Studio.

- You can use this database (may not be up-to-date) -> https://drive.google.com/drive/folders/1YaCCetRyer9-kFhLw1ZXdmp3sHoKCO84?usp=sharing
(SQL Mangement Studio doesn't work on macbook so if you are on macOS just create the database matching the entities in concrete for the tables)

- Also you have to change the connection string at DataAccess.

## Database Scenario

Web library that is named MEFReads provides online experiences using databases. Some functions are implemented which are user, book, genre, language and library. Readers create an account using the register feature then login anytime. Users have UserID, Username, Password and Role. The site includes different books and each book has ISBN as primary key, Title, Summary, LanguageID, ImageSource and Author. Adding books is possible on the site. There are genres that have ID as primary key and name. Moreover each book can be in several genres so, it is holded using BookGenreID, BookISBN and GenreID. The site supports various languages using ID as primary key and name thus it would be a worldwide library. In addition, each user creates their own libraries so, users add books to these libraries and others are able to see. Library entity has UserID and BookID. According to this scenario, a database is builded with tables that hold information about these entities.


