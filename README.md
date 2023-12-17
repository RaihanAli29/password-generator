# Intermediate JavaScript: Password Generator Challenge

## Table of Contents

- [Description](#description)
- [Preview](#preview)
- [Usage](#usage)
- [Explaination of Code](#explaination-of-code)
- [Deployment](#deployment)
- [Acknowledgements](#acknowledgements)
- [Resources](#resources)

## Description

For this challenge, I've developed a web application that generates a random password according to user-selected criteria.

## Preview

![App Preview](./assets/05-javascript-challenge-demo.png)

## Usage

1. Open the application in your browser.
2. Click the "Generate Password" button.
3. Follow the prompts to select password criteria:
   - Length of password (between 8 and 128 characters).
   - Character types (Uppercase, Numeric, Special characters). Lowercase is set as standard input.
4. Once all prompts are answered, the generated password will be displayed on the page.

## Explaination of Code

The given JavaScript code generates random passwords based on user input. It includes arrays for various character types, a function to prompt users for password options, another function to generate random elements from arrays, and a function to create passwords based on user input. Event listeners are also used to initiate password generation when a button is clicked.

#### Key Components of the Code
1. **Arrays of Characters**: The code initializes arrays for special characters, numeric characters, lowercase characters, and uppercase characters. These arrays are used to generate the password based on the user's input.

2. **getPasswordOptions Function**: This function prompts the user to input the desired password length and select the types of characters to be included in the password (capital letters, numbers, and special characters).

3. **getRandom Function**: This function is used to retrieve a random element from an array.

4. **generatePassword Function**: This function utilizes the user's input from getPasswordOptions to generate a password. It constructs the password based on the selected character types and the specified length.

5. **Event Listeners**: The code includes an event listener to trigger the password generation process when a button is clicked.

#### How the Code Works
1. The user is prompted to input the desired password length and select the types of characters to be included in the password.
2. Based on the user's input, the generatePassword function constructs a password by including the selected character types and ensuring the specified length is met.
3. The generated password is then displayed to the user.

## Deployment

Access the live application at: [https://raihanali29.github.io/password-generator/](https://raihanali29.github.io/password-generator/)

GitHub Repository: [https://github.com/raihanali29/password-generator](https://github.com/raihanali29/password-generator)


## Acknowledgements

Prior to beginning this task, myself and fellow team members of my working group began a introductory session into creating a function to prompt the user for password options, based on selective criteria.


## Resources

- [MDN Web Docs on NaN property](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/NaN)

- [MDN on Math.random static method](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)

- [MDN on Functions in Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

- [MDN on parseInt function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseInt)


