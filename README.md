📚 Console-Based Library Management System (Java)
A simple console-based Library Management System written in Java, designed for beginner programmers to understand basic concepts like user authentication, menu-driven programs, collections (Vector), exception handling, and control flow.

📝 Project Description
This Java project simulates a basic Library Management System that allows an admin to:

Login securely

View available books

Add new books

Borrow books (remove from list)

Logout or exit the program

The program uses:

Scanner for user input

Vector to store and manage books

Exception class for custom error handling (future scope)

switch-case and loops for logic flow

🛠 Technologies Used
Java (JDK 8+)

Console-based input/output

No external libraries or frameworks

🔐 Login Credentials
To use the system, enter the following hardcoded credentials:

Username: Pavan@123

Password: 12345

💻 How to Run

1. Compile
   bash
  
   javac Library1.java

2. Run
   bash
 
   java Library1
   📂 Features Overview
   Feature	Description
   Login System	Verifies admin credentials
   View Books	Shows list of available books
   Add Book	Allows admin to add new books
   Borrow Book	Allows admin to borrow (remove) a book
   Logout / Exit	Securely ends session or closes program

🔍 Sample Output Demos
▶ Program Start
markdown
Copy
Edit
************************************************************
******Welcome to the Library******
Choose any one : (eg.. 1,2)
1. Login.
2. Exit.
   ▶ Successful Login
   yaml
   Copy
   Edit
   Enter your username : Pavan@123
   Enter your password : 12345
   Login Successful
   ▶ Incorrect Login Attempt
   yaml
   Copy
   Edit
   Enter your username : wrongUser
   Enter your password : 12345
   Invalid Username
   ▶ Main Menu After Login
   markdown
   Copy
   Edit
************************************************************
Choose any one : (eg.. 1,2)
1. Display list of Books.
2. Add a Book.
3. Borrow a Book.
4. Logout.
   ▶ Displaying Books
   markdown
   Copy
   Edit
************************************************************
List of Books :
1. Shadow
2. Legacy
3. Origin
4. Storm
5. Echo
   ▶ Adding a Book
   markdown
   Copy
   Edit
************************************************************
Enter the book name : Horizon
Book added successfully
▶ Borrowing a Book
markdown
Copy
Edit
************************************************************
Available Books:
1. Shadow
2. Legacy
3. Origin
4. Storm
5. Echo
   Enter the book number to borrow : 2
   Successfully borrowed: Legacy
   ▶ Logout
   markdown
   Copy
   Edit
************************************************************
Log Out Successful
🧠 Concepts Practiced
Java Classes & Objects

Method Design

Conditional Logic

Loops

Exception Handling

Collection: Vector

Scanner for input

📈 Possible Enhancements
Implement file-based or database storage

Add multiple user support (admin vs student)

Use the custom InvalidBookName exception for validations

Add a GUI using Java Swing or JavaFX

Track borrowed books with user history

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

📃 License
This project is open-source and free to use for learning and practice purposes.