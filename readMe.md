# Library Management System

This project is a Library Management System built using the MERN stack (MongoDB, Express, React, Node.js). It includes features for managing books, users, and borrowing transactions with two types of users: Admin and regular users.

## Features

- **Books Management**: Add, update, delete, and view books.
- **User Management**: Display user information with options to delete users.
- **Borrowing Books**: Borrow books and track borrowing details.
- **Returned Books**: Display information about returned books.
- **Admin Dashboard**: View overall statistics including borrow count, total books, total users, and total returned books.
- **Authentication**: Sign up and login with JWT and bcrypt for secure authentication.

## User Types

### 1. Admin

The Admin has full access to all features of the system:

- **View Everything**: The Admin can view all available information in the system.
- **User Management**: The Admin can view all users and delete them from the database if needed.
- **Books Management**: The Admin can:
  - View all books available in the library.
  - Add new books.
  - Update book details.
  - Delete books.
- **Borrowed Books**: The Admin can view all borrowed books (books that have not been returned) in a table format, which includes:
  - Book details
  - Member details
  - Borrow date
  - Due date
  - Fine calculation in a "Fine" column
- **Reports**: The Admin can view reports which include:
  - Overdue people (users with books that have a due date less than the current date) with a column for fines.
  - Returned Books: The Admin can view all returned books.
- **Dashboard**: The Admin dashboard shows:
  - Total books in the library
  - Total borrowed books
  - Total returned books

### 2. Regular User

Regular users have limited access with a focus on borrowing and viewing books:

- **View Available Books**: Users can view all available books in the library and have a search option to find specific books.
- **Borrow Books**: Users can borrow books.
- **Borrowed Books**: Users have a "Borrowed Books" column that shows books they have borrowed but not returned, with an option to return a book.
- **Returned Books**: Users have a "Returned Books" column that shows their borrowing history.

## Technologies Used

- Frontend:
  - React
  - Bootstrap
  - CSS
- Backend:
  - Node.js
  - Express
  - MongoDB
  - Axios
- Tools:
  - Git
  - Visual Studio Code

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/your-username/e-commerce-site.git
   cd e-commerce-site
2. **Install dependencies for both frontend and backend:**


    For the Backend:

    ```sh
      cd backend
      npm install 
    ```
    For the Frontend:

    ```sh
      cd frontend
      npm install
    ```
3. **Set up environment variables:**


    Create a .env file in the backend directory and add your MongoDB URI and other necessary environment variables:

    ```sh
      MONGO_URI=your-mongodb-uri
      JWT_SECRET=your-jwt-secret
    ```

4. **Run the application:**

    For the backend

      ```sh
        cd backend
        npm start
      ```

    For the frontend
      ```sh
        cd backend
        npm start
      ```
## Pages 

### Login & Signup :

1. **User Signup** :

<img width="963" alt="Screenshot 2024-07-25 at 3 48 54 PM" src="https://github.com/user-attachments/assets/e9daa172-5880-4cdf-9586-93f18a97d5b5">

2. **Login** :

<img width="963" alt="Screenshot 2024-07-25 at 3 41 17 PM" src="https://github.com/user-attachments/assets/429795c3-3f1e-4124-a504-78e4bc353021">


### Admin : 

1. **Dashboard** : 

<img width="1436" alt="Screenshot 2024-07-25 at 3 41 48 PM" src="https://github.com/user-attachments/assets/94142522-bb98-4397-a71b-172581f9bc70">

2. **Books** :

<img width="1429" alt="Screenshot 2024-07-25 at 3 41 59 PM" src="https://github.com/user-attachments/assets/3a3a7583-0a70-4eec-b815-2a670a611faf">

3. **USERS LIST** :

<img width="1440" alt="Screenshot 2024-07-25 at 3 42 13 PM" src="https://github.com/user-attachments/assets/ed1e1862-6a35-49d2-9ef7-2c4de6b48bf7">

4. **Borrowed List** :

<img width="1439" alt="Screenshot 2024-07-25 at 3 42 26 PM" src="https://github.com/user-attachments/assets/c4c126c0-2165-4782-9c24-24698a70bcd3">

5. **Reports** :

<img width="1437" alt="Screenshot 2024-07-25 at 3 42 38 PM" src="https://github.com/user-attachments/assets/dd30697a-1832-4b12-917e-c2e7cdd507ff">


### User :

1. **Dashboard** :

<img width="920" alt="Screenshot 2024-07-25 at 3 51 27 PM" src="https://github.com/user-attachments/assets/662c64a1-a494-481b-8411-e4d9276c629b">

2. **Available Books** :

<img width="1387" alt="Screenshot 2024-07-25 at 3 51 45 PM" src="https://github.com/user-attachments/assets/52009707-04e3-417a-ace6-7dd84934e232">

3. **Books Borrowed** :

<img width="1389" alt="Screenshot 2024-07-25 at 3 52 01 PM" src="https://github.com/user-attachments/assets/c05efd78-d223-4247-b3e6-9f8c101e7b7c">

4. **Books Returned** :

<img width="1439" alt="Screenshot 2024-07-25 at 4 00 35 PM" src="https://github.com/user-attachments/assets/8f28e1de-ee8a-4323-ac6f-780547a7b0ae">
