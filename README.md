# User-Management-System

This C program is a simple user management system that allows users to register and log in with a username and password. 
It runs through a console-based menu where users can choose to register, log in, or exit the program. 
The system supports up to ten users and stores their credentials in memory using a basic `struct`.
When a user registers, the program asks for a username and password. During password input, masking is enabled, so each character typed is shown as an asterisk (`*`) for privacy. 
The login feature compares entered credentials against the stored ones and prints whether the login was successful or not.
The program uses `fgets()` for input and includes a small helper function to remove the newline character it adds. 
Password input is handled using `_getch()` from the `<conio.h>` library (which works on Windows), making it possible to read characters one by one without displaying them on screen. 
Overall, this project demonstrates how to handle string input, password masking, and basic credential management in C, and it can serve as a foundation for more advanced authentication systems.
