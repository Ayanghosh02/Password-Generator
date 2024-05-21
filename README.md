Welcome to the Password Generator project! This tool is designed to help you generate strong and secure passwords effortlessly. It features a user-friendly interface that allows you to customize the length and composition of your passwords according to your needs.
Features:

•	Customizable Length: Adjust the length of your password using a simple slider.
•	Character Options: Include or exclude uppercase letters, lowercase letters, numbers, and symbols.
•	Strength Indicator: Visual indicator to show the strength of the generated password.
•	One-Click Copy: Easily copy the generated password to your clipboard with a single click.

Technologies Used:
•	HTML5: For the basic structure of the webpage.
•	CSS3: For styling the webpage and making it visually appealing.
•	JavaScript: For the interactive functionality, including password generation and copying.

How to Use:
1.	Set Password Length: Use the slider to choose your desired password length.
2.	Select Character Types: Check the boxes to include uppercase letters, lowercase letters, numbers, and symbols in your password.
3.	Generate Password: Click the "Generate Password" button to create a new password.
4.	Copy to Clipboard: Click the copy button next to the generated password to copy it to your clipboard.
   
Code Overview:
HTML:
The HTML file provides the structure of the password generator interface, including input elements for password length, checkboxes for character type options, and buttons for generating and copying passwords.
CSS:
The CSS file styles the components to create an intuitive and visually appealing user interface. It includes styles for the container, buttons, slider, checkboxes, and tooltip for the copy button.
JavaScript:
The JavaScript file contains the logic for generating the password. Key functions include:

•	handleSlider(): Updates the slider and length display.
•	setIndicator(color): Sets the color of the strength indicator.
•	getRndInteger(min, max): Generates a random integer between min and max.
•	generateRandomNumber(), generateLowerCase(), generateUpperCase(), generateSymbol(): Functions to generate random characters of different types.
•	calcStrength(): Calculates and displays the strength of the generated password.
•	copyContent(): Copies the generated password to the clipboard.
•	shufflePassword(array): Shuffles the characters in the generated password for added randomness.

Contributing:

Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue.
License

This project is licensed under the MIT License. See the LICENSE file for more details.
Contact

For any questions or feedback, please contact :  ayan_g.cse2021@msit.edu.in
