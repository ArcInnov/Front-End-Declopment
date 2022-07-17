# 17 July 2022

22. Compound Assignment With Augmented Subtraction
    Like the += operator, -= subtracts a number from a variable.
    Example:- myVar-=5

23. Compound Assignment With Augmented Multiplication
    The *= operator multiplies a variable by a number.
    Example:- myVar *= 5; 

24. Compound Assignment With Augmented Multiplication
    The *= operator divides a variable by a number.
    Example:- myVar /= 5; 

25. Escaping Literal Quotes in Strings
    When you are defining a string you must start and end with a single or double quote. 
    In JavaScript, you can escape a quote from considering it as an end of string quote by placing a backslash (\) in front of the quote.
    Example:-
        const sampleStr = "Alan said, \"Peter is learning JavaScript\".";
        This signals to JavaScript that the following quote is not the end of the string, but should instead appear inside the string. So if you were to print this to the console, you would get:
        Alan said, "Peter is learning JavaScript".

26. Quoting Strings with Single Quotes
    String values in JavaScript may be written with single or double quotes, as long as you start and end with the same type of quote. Unlike some other programming languages, single and double quotes work the same in JavaScript.
    Example:-
        const singleQuoteStr = 'This is also a string';
    Usage:-
        The reason why you might want to use one type of quote over the other is if you want to use both in a string. This might happen if you want to save a conversation in a string and have the conversation in quotes. Another use for it would be saving an <a> tag with various attributes in quotes, all within a string.
        const conversation = 'Finn exclaims to Jake, "Algebraic!"';
    However, this becomes a problem if you need to use the outermost quotes within it. 
    Remember, a string has the same kind of quote at the beginning and end. 
    But if you have that same quote somewhere in the middle, the string will stop early and throw an error.
    Note:- The backslash \ should not be confused with the forward slash /. They do not do the same thing.

27. Escape Sequences in Strings
    Quotes are not the only characters that can be escaped inside a string. There are two reasons to use escaping characters:
    To allow you to use characters you may not otherwise be able to type out, such as a carriage return.
    To allow you to represent multiple quotes in a string without JavaScript misinterpreting what you mean..
    Example:-
        Code	Output
        \'	single quote
        \"	double quote
        \\	backslash
        \n	newline
        \r	carriage return
        \t	tab
        \b	word boundary
        \f	form feed
    Note that the backslash itself must be escaped in order to display as a backslash.

28. Concatenating Strings with Plus Operator
    In JavaScript, when the + operator is used with a String value, it is called the concatenation operator. You can build a new string out of other strings by concatenating them together.
    Example:-
        'My name is Alan,' + ' I concatenate.'
    Note: Watch out for spaces. Concatenation does not add spaces between concatenated strings, so you'll need to add them yourself.

29. Concatenating Strings with the Plus Equals Operator
    We can also use the += operator to concatenate a string onto the end of an existing string variable. This can be very helpful to break a long string over several lines.
    Note: Watch out for spaces. Concatenation does not add spaces between concatenated strings, so you'll need to add them yourself.
    Example:
        let ourStr = "I come first. ";
        ourStr += "I come second.";
        ourStr now has a value of the string I come first. I come second.

30. Constructing Strings with Variables
    Sometimes you will need to build a string. By using the concatenation operator (+), you can insert one or more  variables into a string you're building.
    Example:
        const ourName = "freeCodeCamp";
        const ourStr = "Hello, our name is " + ourName + ", how are you?";
        ourStr would have a value of the string Hello, our name is freeCodeCamp, how are you?

31. Appending Variables to Strings
    Just as we can build a string over multiple lines out of string literals, we can also append variables to a string using the plus equals (+=) operator.
    Example:
        const anAdjective = "awesome!";
        let ourStr = "freeCodeCamp is ";
        ourStr += anAdjective;
        ourStr would have the value freeCodeCamp is awesome!.


