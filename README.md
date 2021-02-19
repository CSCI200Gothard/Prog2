# Project Char Loop
You programming team is developing language recognition software for social media posts. Your task is to get statistical information about the text in order to facilitate further processing.

## C Version
Write a program that reads in a line from standard input (**no prompting**) and determines the following:

* the number of **vowels** in the String (aeiou or AEIOU)
* the number of **uppercase** letters
* the number of **digits**
* the number of **whitespace** characters

Use a **loop**. Do **not** the use of arrays or arrayLists. See https://www.geeksforgeeks.org/character-class-java/ for handy `Character` methods, like `isWhiteSpace`, `toLowerCase`, `isDigit`, `isUpperCase`, etc. See https://www.w3schools.com/java/
java_ref_string.asp for handy `String` methods, like `charAt` and `length`.

### Example Input
```
This String has vowels and 12345 digits. 
```
### Example output
```
vowels = 8
upper = 2
digits = 5
whitespace = 6
```
## B Version
Create a support method that returns boolean indicating if a character is vowel (either upper or lower case). Use good naming and appropriate modifiers.

## A Version
In addition to the requirements for the C and B versions, output a list of all consecutively repeated characters. Consider using `StringBuilder`. Beware of `StringIndexOutOfBoundException`s: before you access a character by index, make sure the index is less than the length of the String.

### Example Input
```Some people raise raccoons for their pelts. A raccoon's home is called a nook. The person who cleans and tidies up the raccoonnooks is called the raccoonnookkeeper. Real word! l33t.```
### Example Output
```
vowels = 59
upper = 4
digits = 2
whitespace = 29
repeated characters: c o c o l o c o n o l c o n o k e 3
```
Name your source code file: **CharLoop.java**
Submit to **CodePost**.

## Extra Credit
* Submit a full 24-hours early to receive **3 points** extra credit.
* Be the first, second, and third to submit a correct A version to receive **3**, **2**, or **1** point extra credit respectively.

## Recommended Phases
1. Read a line and print it back out, one character out at a time.
2. Read a line and print the number of digits.
3. Read a line and print the number of uppercase letters, digits, and whitespace characters. 
4. Create the service method for the B version.
5. Complete the B and C versions.
6. Complete the A version.
