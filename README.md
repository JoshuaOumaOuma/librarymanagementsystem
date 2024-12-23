# Library-Management-System-Django
A Simple Library Management System that helps in managing a library.

### Available Functionalities:
Definition: CRUD(Create, Read, Update and Delete)
1. Members Management (Allows CRUD operations on Library Members)
2. Books Management (Allows CRUD operations on Books)
3. Lending of Books to Members.
4. Returning of Books by Members.
5. Payment for Borrowing A Book/Books by Members
6. Payments for fines on overdue books By Members.

### To run the project locally, follow the following instructions:
- Clone the repository
  ```sql
  
  ```
- Navigate to the project directory.
  ```sql
  cd Library-Management-System-Django
  ```
- Create virtual environment and activate it:
  ```sql
  python3 -m venv venv or python -m venv venv
  ```
  Activate: On Windows
  ```sql
  venv\Scripts\activate
  ```
  On Mac
  ```sql
  source venv\bin\activate
  ```
- Install libraries from the requirements.txt file.
  ```sql
  pip install -r requirement.txt
  ```
- Edit the *.env.sample* file to add your environment variables.
- Set up the database:
  ```sql
  python manage.py migrate
  ```
- Run the server:
  ```sql
  python manage.py runserver
  ```

### Hosted version
Hosted version of the project: https://library-wnd0.onrender.com/

Use the following credentials:
```sql
Email: admin@gmail.com
Password: Admin@LMS
```
Or register an account.


Other Pages.
