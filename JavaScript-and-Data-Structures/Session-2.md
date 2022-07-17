# Session 2, Friday July 8 2022

8. Understanding Case Sensitivity in Variables
    In JavaScript all variables and function names are case sensitive. This means that capitalization matters.
    Best Practice:
    Write variable names in JavaScript in camelCase. In camelCase, multi-word variable names have the first word in lowercase and the first letter of each subsequent word is capitalized
    Example:- var myVar=6;

9. Explore Differences Between the var and let Keywords
    One of the biggest problems with declaring variables with the var keyword is that you can easily overwrite variable declarations:
    In a small application, you might not run into this type of problem. 
    But as your codebase becomes larger, you might accidentally overwrite a variable that you did not intend to. 
    Because this behavior does not throw an error, searching for and fixing bugs becomes more difficult.
    A keyword called let was introduced in ES6, a major update to JavaScript, to solve this potential issue with the var keyword
    So unlike var, when you use let, a variable with the same name can only be declared once.

10. Declare a Read-Only Variable with the const Keyword
    const has all the features that let has, with the added bonus that variables declared using const are read-only. 
    They are a constant value, which means that once a variable is assigned with const, it cannot be reassigned:
    Example:- const FAV_PET = "Cats"
    You should always name variables you don't want to reassign using the const keyword. 
    This helps when you accidentally attempt to reassign a variable that is meant to stay constant.
    Note: It is common for developers to use uppercase variable identifiers for immutable values and lowercase or camelCase for mutable values (objects and arrays). 

11. Add Two Numbers with JavaScript
    Number is a data type in JavaScript which represents numeric data.
    JavaScript uses the + symbol as an addition operator when placed between two numbers.
    Example:- const myVar = 5 + 10;

12. Subtract One Number from Another with JavaScript
    JavaScript uses the - symbol as an subtraction operator when placed between two numbers.
    Example:- const myVar = 25 - 10;

13. Multiply Two Numbers with JavaScript
    JavaScript uses the * symbol as an multiplication operator when placed between two numbers.
    Example:- const myVar = 25 * 10;

14.  Divide Two Numbers with JavaScript
    JavaScript uses the / symbol as an division operator when placed between two numbers.
    Example:- const myVar = 25 / 5;

15. Increment a Number with JavaScript
    You can easily increment or add one to a variable with the ++ operator.
    i++;    is the equivalent of    i = i + 1;
    Note: The entire line becomes i++;, eliminating the need for the equal sign.

16. Decrement a Number with JavaScript
    You can easily decrement or subtract one to a variable with the -- operator.
    i--;    is the equivalent of    i = i - 1;
    Note: The entire line becomes i--;, eliminating the need for the equal sign.







