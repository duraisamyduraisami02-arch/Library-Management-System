# Library-Management-System
code link   https://duraisamyduraisami02-arch.github.io/Library-Management-System/
# 📚 Library Management System

## 📌 Project Description

The **Library Management System** is a simple web-based application designed to manage books, library members, and book transactions.

This project is developed using a **single HTML file** containing HTML, CSS, and JavaScript. It does not require a separate backend server or database.

The system uses the browser's **Local Storage** to save and manage library data.

---

## 🎯 Objectives

- Manage library books efficiently.
- Add, edit, search, and delete books.
- Manage library members.
- Issue books to members.
- Return issued books.
- Track book transactions.
- Display library statistics through a dashboard.
- Store data using browser Local Storage.

---

## 🛠️ Technologies Used

- **HTML5** – Creates the structure of the application.
- **CSS3** – Provides styling and responsive design.
- **JavaScript** – Handles application logic and CRUD operations.
- **Local Storage** – Stores books, members, and transaction data in the browser.

> All technologies are implemented inside a **single HTML file**.

---

## ✨ Features

### 1. Dashboard

The dashboard displays:

- Total Books
- Available Books
- Total Members
- Currently Issued Books

### 2. Book Management

The system allows the librarian to:

- Add new books
- View all books
- Search books
- Edit book details
- Delete books

Book information includes:

- Book ID
- Book Title
- Author
- Category
- Quantity

### 3. Member Management

The system allows the librarian to:

- Add members
- View members
- Delete members

Member information includes:

- Member ID
- Member Name
- Phone Number
- Email

### 4. Book Issue

A librarian can issue an available book to a registered member.

When a book is issued:

- Book quantity decreases by one.
- Issue date and time are recorded.
- Transaction status becomes **Issued**.

### 5. Book Return

When a member returns a book:

- Book quantity increases by one.
- Return date and time are recorded.
- Transaction status changes to **Returned**.

### 6. Search

Books can be searched using:

- Book title
- Author name
- Category

### 7. Data Storage

The application uses **Local Storage** to store:

- Books
- Members
- Transactions

Therefore, the data remains available after refreshing the browser.

---

## 📂 Project Structure

```text
Library Management System/
│
└── library_management.html
```

The complete application is contained in one HTML file.

---

## 🚀 How to Run the Project

### Step 1

Download or clone the project.

### Step 2

Open the project folder in **Visual Studio Code**.

### Step 3

Open:

```text
library_management.html
```

### Step 4

Open the file in any modern web browser.

You can also use the **Live Server** extension in VS Code.

---

## 🧑‍💻 How to Use

### Add a Book

1. Enter the book title.
2. Enter the author's name.
3. Enter the category.
4. Enter the quantity.
5. Click **Add Book**.

### Add a Member

1. Enter the member name.
2. Enter the phone number.
3. Enter the email.
4. Click **Add Member**.

### Issue a Book

1. Select an available book.
2. Select a member.
3. Click **Issue Book**.
4. The book quantity will automatically decrease.

### Return a Book

1. Go to the **Book Transactions** section.
2. Find the issued book.
3. Click **Return**.
4. The book quantity will automatically increase.

---

## 🔄 CRUD Operations

The project implements CRUD functionality for book management.

| Operation | Description |
|---|---|
| Create | Add a new book |
| Read | View and search books |
| Update | Edit book details |
| Delete | Remove a book |

Member management also supports adding, viewing, and deleting members.

---

## 💾 Data Storage

This project uses browser **Local Storage** instead of a traditional database.

The following data is stored:

```text
libraryBooks
libraryMembers
libraryTransactions
```

No MySQL, PostgreSQL, MongoDB, or separate server is required.

---

## 📱 Responsive Design

The application is designed to work on:

- Desktop
- Laptop
- Tablet
- Mobile devices

CSS media queries are used to make the interface responsive.

---

## 🔒 Basic Validation

The system performs basic validation such as:

- Required book fields
- Valid quantity
- Required member name
- Preventing issue of unavailable books
- Preventing duplicate active book issues
- Preventing deletion of books currently issued
- Preventing deletion of members with active issued books

---

## 🔮 Future Enhancements

The following features can be added in future versions:

- Admin login
- Librarian login
- MySQL database
- Backend using Python/Java/PHP
- Fine calculation for late returns
- Due date management
- Book cover images
- Advanced reports
- PDF report generation
- Email notifications
- Cloud database
- Multi-user support

---

## 🎓 Project Type

**Project:** Library Management System

**Application Type:** Web Application

**Architecture:** Single-page client-side application

**Storage:** Browser Local Storage

---

## 👨‍💻 Conclusion

The Library Management System provides a simple and efficient way to manage books, members, and library transactions.

The project demonstrates important web development concepts such as:

- HTML structure
- CSS styling
- JavaScript programming
- CRUD operations
- Form handling
- Search functionality
- Local Storage
- Responsive web design

It is suitable as a **student mini project / CRUD project** and can be extended with a backend and database for real-world use.
