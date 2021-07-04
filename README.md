# Password Generator Starter Code
Created calculator that prompts the user meets the user criteria 
THAT: meets the criteria for uppercase, lowercase, numbers and special characters
THAT: prompts the user to choose password length of password
THEN: gives the option for length amount between 8 - 128
THEN: a confirmation whether or not to include uppercase, lowercase, numbers, or special characters.
THEN: gives the option to include uppercase, lowercase, numbers or letters. Will return an alert if nothing chosen and a prompt to resubmit.
WHEN: all prompts are answered correctly
THEN: password will be generated matching criteria
THEN: password will be displayed inside of box

CODE:

function "generatepassword"() : returns the function and return its value

var passwordText = document.querySelector(#password): will return the password to the text area located on the index.html 

var passwordText = password; :will return password from function "writePassword"

function writePassword(): inside the { } will write the password and return the password to the text area located on the index.html

generateBtn.addEventListener: waits for an even to occur (clicking of button from index.html) to execute an argument from the script.js

function generatePassword(): creates the function containing the code inside {}  that will contain the code to execute command.

var length = creating variable to call on later in the function.

if (isNaN(length)){
    alert("You must input a number!");
    return generatePassword()
} :if the arthimetic is not met then NaN is false and will return an alert to choose number

if (length<8 || length>128){
    alert(###)
    return generatePassword()
} = an array that states if the length is less than 8 but more than 128, will return false and send an alert to user before returning generatePassword prompt

var = hasUpper, hasLower, hasNumbers, hasSpecial = confirm (###): window.confirm which characters to choose. creating variable to use later in the function.

if(!&&!&&!&&!&&){
    alert("you must choose at least 1 character type!!")
    return generatePassword()
} :from left to right will execute true and false to return var values.

for (var i = 0; i < length: i++) for loop that returns length in increments of 1 with {result +=chosenCharacters.charAt(math.floor(math.random() * chosenCharacters.length);

} the result of the function will take chosenCharacters and execute the math.floor which returns lowest intregral of the number from chosenCharacter not exceeding length.


