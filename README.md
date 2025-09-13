# Random Password Generator (C++)

This project is a *simple interactive password generator* written in C++.  
It allows the user to decide how long the password should be and then generates a password in *three strength levels*:

1. Basic Password – Numbers only  
2. Strong Password – Letters + Numbers  
3. Strongest Password – Letters + Numbers + Special Characters  

The user can accept or reject each password until satisfied.

---

# Features
- User-defined password length* (4–12 characters)
- Three levels of password strength
- Random password generation each time
- Interactive approval (accept or reject)
- Clean and beginner-friendly code

---

# Example 

How long should the password be? (4-12): 6
Generated Password: 472195
Is this password okay? (y/n): n
Generated Strong Password: aT3fZk
Is this password strong enough? (y/n): n
Generated Strongest Password: @gH!z3
Thank you, very feed! :)

Concepts Used

This project demonstrates several core C++ programming concepts:

Input/Output: cin, cout for user interaction.

Conditional Statements: if and if-else to check conditions.

Loops: for loop to build passwords character by character.

Functions: Separate generatePassword() function for modular code.

Random Number Generation: srand(time(0)) and rand() for random characters.

Strings: Use of std::string to build dynamic passwords.

Character Handling: tolower() to make user input (y/n) case-insensitive.

Error Handling: Validates password length (must be 4–12 characters).


# Author

Developed by Chander Parkash as a beginner-friendly C++ project to practice:
