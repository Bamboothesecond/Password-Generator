# Password-Generator
*By bamboothesecond

*This Python program generates a random password of a specified length. It uses the random and string modules to generate a string of lowercase and uppercase letters, *digits, and punctuation characters. The generate_password function takes a single argument length which specifies the desired length of the password.

*The function first creates four separate strings lowercase, uppercase, numbers, and symbols, each containing characters of the respective category. It then concatenates *these strings into a single string all_characters.

*Finally, the join method of the string class is used to join a specified number of random characters from all_characters into a password string of the specified length, *which is then returned by the function.

*The program prompts the user to enter the desired length of the password, and then calls the generate_password function with the user-specified length. It prints the *generated password to the console using an f-string.
