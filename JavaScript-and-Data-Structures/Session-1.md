# Session 1, Friday July 8 2022

## 

1.Commenting java sxript code
    // This is an in-line comment.
    /* This is a
    multi-line comment */
    Regularly add comments to clarify the function of parts of your code. Good commenting can help communicate the intent of your code—both for others and for your future self.

2. Declaring JavaScript Variables
    JavaScript provides eight different data types which are undefined, null, boolean, string, symbol, bigint, number, and object.
    Computers can perform mathematical operations on a number, but not on a string.
    Variables allow computers to store and manipulate data in a dynamic fashion. They do this by using a "label" to point to the data rather than using the data itself. Any of the eight data types may be stored in a variable.
    Variable names can be made up of numbers, letters, and $ or _, but may not contain spaces or start with a number.
    End the declaration with a semi-colon
    Example:- var myName;

3. Storing Values with the Assignment Operator
    In JavaScript, you can store a value in a variable with the assignment operator (=).
    If there are any calculations to the right of the = operator, those are performed before the value is assigned to the variable on the left of the operator
    Example: myName="Arc"

4. Assigning the Value of One Variable to Another
    After a value is assigned to a variable using the assignment operator, you can assign the value of that variable to another variable using the assignment operator.
    Example:- var Name=myName;
    Note : In the exercisie i wrote a=b instead of b=a so it showed an error since a's value was 7 and b was not defined it showed an error

5. Initializing Variables with the Assignment Operator
    It is common to initialize a variable to an initial value in the same line as it is declared.
    var myVar = 0;

6. Declare string variables
    A string literal, or string, is a series of zero or more characters enclosed in single or double quotes.
    Example:- var myName = "your name";
    Note : I forgot to wrap text in double quotations so a erroe showed up pointing Arc not defined I realised without quotaions it was treating Arc as a variable whose value was undefined

7. Understanding Uninitialized Variables
    When JavaScript variables are declared, they have an initial value of undefined. 
    If you do a mathematical operation on an undefined variable your result will be NaN which means "Not a Number". 
    If you concatenate a string with an undefined variable, you will get a string of undefined.

