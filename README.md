# Vernam Cipher Program
## Overview
This program implements the Vernam Cipher, a symmetric-key encryption algorithm. The Vernam Cipher involves XORing each character of the plaintext with a corresponding character in the key to produce the ciphertext. The same key is used for both encryption and decryption.

# Files
## index.html: 
Contains the HTML structure for the user interface.

## style.css: 
Provides basic styling for the HTML elements.

## script.js: 
Implements the encryption and decryption logic, key generation, and table display.

## How to Use
Open the index.html file in a web browser.
Enter a message in the input field.
Click the "Encrypt" button to encrypt the message or "Decrypt" to decrypt.
View the key table, encryption, or decryption results in the alert.

# Program Structure
## HTML Structure:
Input field for message entry.
"Encrypt" and "Decrypt" buttons.
Sections displaying encryption and decryption formulas.
A table to display the key used for encryption and decryption.

## CSS Styling:
Provides basic styling for a clean and user-friendly interface.

## JavaScript Functionality:
encrypt() and decrypt() functions perform encryption and decryption, respectively.
generateRandomKey(length) function generates a random key of a specified length.
displayKeyTable(key) function populates the HTML table with characters, ASCII values, and corresponding key values.

## Notes
This program is for educational purposes and may not cover all edge cases or security considerations.
Random key generation is used for demonstration; in practice, a secure key generation method is essential for real-world use.

## Limitations
The provided code assumes a secure random key generation for demonstration purposes.
In a production environment, additional security measures and error handling would be required.
