Download Link: https://assignmentchef.com/product/solved-solvedcomputer-science-221-program-3
<br>
Learning objectives:

Write a Java class that takes an object parameter.

Write a Java class that modifies “this” object.

Write a Java class that creates and returns an object.

Assignment:

Define a class named Money whose objectsrepresent amounts in U. S. money. The class must have two instance variables oftype int for the dollarsand cents parts of the amount of money. You may not use any float or double variables or values in thisprogram.

Write two constructors. One has two parameters for the dollars andcents. The other has no parameters, and set dollars and cents to zero. Writeaccessors and mutators (getters and setters) for the dollar amount and thecents amount.

Write two methods, increment(Moneym)and decrement(Moneym),that change the amount in the calling object (this) by the amount inparameter. So if m1 holds 2 dollars90 cents and m2 holds 1 dollar20 cents, the call m1.increment(m2) changes theamount in m1 to 4 dollars 10cents. Write two similar methods, add(Money m) and subtract(Moneym),that add or subtract, respectively, the amounts in the calling object (this) and the parameter andreturn a third Money object thatcontains the sum or difference. So if m1 holds 2 dollars 90 cents and m2 holds 1 dollar 20 cents,the call m1.add(m2) does not changeeither m1 or m2. Rather a third Money object, containing 4dollars 10 cents, is created and returned.

You do not have to write a subtract(Money m) method or a decrement(Money m) method that cansubtract a larger amount from a smaller amount (negative result). You will getextra credit if you do write methods that can correctly produce negativeresults.

Write a method, toString(), that returns a String containing the amount ofmoney in a pleasing format. So if m1 holds 2 dollars 90 cents, toString() will return the String “$2.90”.

Write a method, equals(Moneym)that returns a boolean, true or false as this object is equal to theparameter.

Write a program TestMoney to test your Money class. We reserve the rightto replace your TestMoney with our own.

Submission instructions:

Upload the files Money.java and TestMoney.java to “Program 3”. Do not submit class files or any of the BlueJcontrol files. Be sure to press the submit button.

Policies:

The policies given on WebCT are in effectfor this and all assignments.

You may submit on WebCT multiple times, sothere is no excuse for not submitting partial solutions.