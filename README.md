This C program implements a simple KYC (Know Your Customer) Verification System using a menu-driven approach and switch-case statement.
First, the program includes the header file stdio.h, which is required to use input and output functions like printf() and scanf().
Inside the main() function, the variables choice and id are declared as integers. The program displays a list of identity verification options such as PAN Number, Aadhar Number, APAAR ID, Driving License, and Passport.
The user is asked to enter a number between 1 and 5 to select the type of document they want to verify. The scanf() function reads the user's input and stores it in the variable choice.
A switch-case statement is then used to check the selected option:
If the user selects 1, the program displays “PAN Verified!”
If the user selects 2, it displays “AADHAR Verified!”
If the user selects 3, it displays “APAAR Verified!”
If the user selects 4, it displays “Driving License Verified!”
If the user selects 5, it displays “Passport Verified!”
If the user enters any number other than 1 to 5, the default case is executed and the program prints “Not Verified!”
Finally, the program ends with return 0;, indicating successful execution.
This program demonstrates the use of switch-case statements to perform different actions based on user input in C programming.
