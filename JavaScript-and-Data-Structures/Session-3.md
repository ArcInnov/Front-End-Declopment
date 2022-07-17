# Session 3, Saturday July 16 2022

17. Create Decimal Numbers with JavaScript
    We can store decimal numbers in variables too. Decimal numbers are sometimes referred to as floating point numbers or floats.
    Note: when you compute numbers, they are computed with finite precision. Operations using floating points may lead to different results than the desired outcome.
    Example:- var myDecimal=5.7;

18. Multiply Two Decimals with JavaScript
    In JavaScript, you can also perform calculations with decimal numbers, just like whole numbers.
    Example:- 2.4 * 5.7;

19. Divide Two Decimals with JavaScript
    In JavaScript, you can also perform calculations with decimal numbers, just like whole numbers.
    Example:- 10.7 / 5.7;

20. Finding a Remainder in JavaScript
    The remainder operator % gives the remainder of the division of two numbers.
    Example
        5 % 2 = 1 because
        Math.floor(5 / 2) = 2 (Quotient)
        2 * 2 = 4
        5 - 4 = 1 (Remainder)
    Usage
        In mathematics, a number can be checked to be even or odd by checking the remainder of the division of the number by 2.
        17 % 2 = 1 (17 is Odd)
        48 % 2 = 0 (48 is Even)
    Note: The remainder operator is sometimes incorrectly referred to as the modulus operator. It is very similar to modulus, but does  not work properly with negative numbers.
    Note : Diiference between modulas and raminder operator
        There is a difference between modulus and remainder. 
        For example: -21 mod 4 is 3 because -21 + 4 x 6 is 3. 
        But -21 divided by 4 gives -5 with a remainder of -1. For positive values, there is no difference

21. Compound Assignment With Augmented Addition
    In programming, it is common to use assignments to modify the contents of a variable. Remember that everything to the right of the equals sign is evaluated first, so we can say:
    Example:-
        myVar = myVar + 5;
        to add 5 to myVar. Since this is such a common pattern, there are operators which do both a mathematical operation and assignment in one step.
    Checked output of 
        a=5;
        a+=a+5;
        result: 15 wheras a+=a gives 10
