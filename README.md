# Inheritance-in-Cpp
# Name: Rajeev Ramesh Reddy E
# PRN: 2407123081

**Aim**: To study and implement the concept of Inheritance in C++, demonstrating how one class can derive properties and behaviors from another.

**Software Used**: VS Code.

**Theory**:
Inheritance in C++ is an object-oriented mechanism that allows one class (derived) to acquire properties and behaviors of another class (base). It promotes code reuse, modularity, and hierarchical relationships. C++ supports multiple inheritance, enabling a class to inherit from multiple bases. Access specifiers (public, protected, private) control visibility of inherited members. Virtual inheritance resolves ambiguity in diamond-shaped hierarchies. Overall, inheritance enhances extensibility and abstraction in complex systems by modeling real-world relationships efficiently.

**Algorithm**:

1) Algorithm of inheritance.
   
Step I: Define Base Class

- Create a class library with a constructor that prints "Here is the library" when invoked.
  
Step II: Define Derived Class

- Create a class book that inherits privately from library.
  
- Add two public string members: title and author.
  
- Define a parameterized constructor to initialize these members.
  
Step III: Implicit Base Constructor Call

- When a book object is created, the library constructor is automatically called due to inheritance.
  
Step IV: Display Book Details

- Implement a display() method in book to print the title and author.
  
Step V: Execute in main()
  
- Instantiate a book object with title and author.
  
- Call display() to show book details.
  
- Observe that the base class constructor also executes.
  

2) Algorithm of multilevel inheritance.

Step I: Define Base Classes

- Create a class Library with a method myLibrary() that prints a message.

- Create another class Author with a method myAuthor() that prints the author's name.
  
Step II: Define Derived Class

- Create a class Book that inherits publicly from both Library and Author.
  
- Add a method myBook() to display the book title.
  
Step III: Instantiate Derived Class

- In main(), create an object obj of class Book.
  
Step IV: Call Member Functions

- Use obj to call myBook(), myAuthor(), and myLibrary() methods.
  
Step V: Output Results

- The program prints the book title, author name, and library message in sequence.


3) Algorithm of multiple inheritance

Step 1: Define Base Classes

- Create class Library with method myLibrary() to print a library message.
  
- Create class Author with method myAuthor() to print the author's name.
  
Step 2: Define Derived Class

- Create class Book that inherits publicly from both Library and Author.
  
- Add method myBook() to print the book title.
  
Step 3: Instantiate Derived Class

- In main(), create an object obj of class Book.
  
Step 4: Call Member Functions

- Use obj to call myBook(), myAuthor(), and myLibrary().
  
Step 5: Display Output

- The program prints the book title, author name, and library message in order.






   

