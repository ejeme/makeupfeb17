# makeupfeb17
Create the JavaScript logic necessary to add functionality to the jQuery Calculator.

Your calculator should be able to handle basic mathematical operations like addition, subtraction, multiplication, etc.

You should be making use of the existing buttons.

You should be making use of the existing placeholders for entering content (i.e. "firstNumber", "operator", "secondNumber", "result").

what I learnt
We made the variable global so we could use them every where.

Then we created a function to initialize
the function


So first we declared the variable firstnumber,secondnumber,opertaor,result,isOperatorChosen and isCalculator exists then we initialized the value of the variables

We initialized the var inside the function instead of the globally so that we could make multiple operations happen

An event listener for all the numbers,operator and clear button
If we did it with less event listners we would have to write switch cases.

//On line 107
if no operator is chosen after the first number it means we could do double digit or triple digit additions so long as the operator isn't clicked//.

//concatenating is linking strings together.//

when inside an event listener and there is a "this" is the target that was clicked

line 123 is checking for either or 

line 126 is set to true because its one of the things we are using to define our logic for the code

parseInt is a javascript function

line 153,val returns a string and so we write if else statement to do math operations if we have the user chose them.
we chose if else,because as soon as it matches a true condition it would skip the rest of the code which is what we want 
//switch statement only work if we have a single variable being compared to multiple values.












