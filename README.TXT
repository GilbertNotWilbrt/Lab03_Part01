Project: number-display
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class NumberDisplay. Then inspect this 
instance and leave the inspector window open. With the inspector window open, 
call the object's methods, such as increment and setValue.


#4 private Instructor tutor; 

#6 You should call the int getValue() to see whether we have incremented more than
59 times, which would then roll over to 0.

#8 When I set the value to 8, then I proceed to call the getValue feature, it 
doesn't change. I believe this is because it won't input the value as it is
bigger than 6 which it refuses to recognize.

#9 Prediction: I believe I will get a value of 0, as the int has achieved the limit.
which will then in turn set it to 0, as per the Code Source suggests.

#10 Error: non-static method getValue() cannot be referenced from a static context.
You would need to call from the object itself, not the class. (e.g. NumberDisplay)

#11 "Error: '.class' expected"
The source code already assumes that the value within the paramater is an int.
There is no need to call int again in this case.

#12 I assume that we would get 10 as the returned value, as now the parameter is <=,
so the value is now recognized.

#13 The only valid parameter value that would no longer set the value field is 0.

#14 The invalid parameter values that now would be able to set the field
are negative values less than the limit and any values greater or equal to limit.

#15 ! false
(34 != 33) && ! false

#16 (a && b) || (!a && !b)

#17 (a && !b) || (!a && b)

#18 The getDisplayValue)() method only works when limit is below 10,
as it assumes values will fit into two digits. With a limit of 1000.
setValue(345) makes getDisplayValue() return "345", a three-digit
string not of two.

#19 No they do not have any difference in the result.

#20 Whenever an int is added to a String with +, the int is converted to a String,
so " " + value and value + " " end up producing the same string.

