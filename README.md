🔐 Secure Password Manager (Java)

📌 Overview

Secure Password Manager is a Java-based console application designed to help users safely store and manage their passwords. It allows users to add, view, and delete credentials while applying basic encoding for security.

❗ Problem Statement

Managing multiple passwords manually or storing them in insecure places (like notes or browsers) can lead to serious security risks.
This project solves that problem by providing a simple and structured way to store credentials securely and access them when needed.

🚀 Features
Master password authentication
Add new credentials (website, username, password)
View saved passwords
Delete stored passwords
Basic password encoding using Base64
Simple console-based interface

🛠️ Technologies Used
Java
Object-Oriented Programming (OOP)
File Handling
Java Collections (Scanner)
Base64 Encoding

📁 Project Structure
PasswordManagerProject/
│── Main.java
│── PasswordService.java
│── FileHandler.java
│── passwords.txt

⚙️ Setup Instructions
1. Requirements
Java JDK 8 or above
Any IDE (VS Code / IntelliJ) or Terminal
2. Clone the Repository
git clone <your-repo-link>
cd PasswordManagerProject
3. Compile the Program
javac *.java
4. Run the Program
java Main

▶️ How to Use
Run the program
Enter the master password
Choose options from the menu:
Add Password
View Passwords
Delete Password
Manage your credentials easily through the console

⚙️ How It Works
User authentication is done using a master password
Passwords are encoded using Base64 before storing
Data is stored in a text file (passwords.txt)
File handling is used to read, write, and delete records
Modular design separates logic into different classes

💾 Data Handling
Uses file-based storage (passwords.txt)
Data persists even after program restart
Each record is stored in a structured format

📚 Learning Outcomes
Applied Object-Oriented Programming concepts
Implemented file handling in Java
Understood basic data encoding techniques
Learned modular code design
Improved problem-solving skills

🔮 Future Improvements
Implement advanced encryption (AES)
Add search and update functionality
Build a graphical user interface (GUI)
Integrate database storage
Add password strength checker

👩‍💻 Author
Nisha 
24BAI10441
VIT Bhopal University
