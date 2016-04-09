# Propositional Logic Manipulator 
This project marks my first ever use of GitHub, so it is my experimental repository. This application can take infix propositional logic expressions, convert them into postfix propositional logic expressions, and then evaluate those postfix propositional logic expressions. It can also generate text-based truth tables that not only include columns for the variables and the final expression, but also columns for all of the steps necessary to get to the final expression.<br />
<br />
Because this application is written in Java, it will need to be compiled with a JDK and run on a machine with a JRE. For additional help with the application, simply run it and enter the number 4 to print out the help document.<br />
<br />
Examples:<br />
Let's show that (p → q) → (q v ¬p) is a tautology. First, convert it into a form with characters the software understands: (p>q)>(q+~p). Now, convert it to postfix with the software and run that postfix through the truth table generator. Below is the input and output for this.<br />
<br />
1 - Convert Infix Expression to Postfix Expression<br />
2 - Evaluate a Postfix Expression<br />
3 - Create a Truth Table for a Postfix Expression<br />
4 - Help<br />
5 - Exit<br />
<b>1</b><br />
Enter an infix expression:<br />
<b>(p>q)>(q+~p)</b><br />
pq>qp~+><br />
1 - Convert Infix Expression to Postfix Expression<br />
2 - Evaluate a Postfix Expression<br />
3 - Create a Truth Table for a Postfix Expression<br />
4 - Help<br />
5 - Exit<br />
<b>3</b><br />
Enter a postfix expression:<br />
<b>pq>qp~+></b><br />
| p | q | (p>q) | (~p) | (q+(~p)) | ((p>q)>(q+(~p))) | <br />
| F | F |   T   |   T  |     T    |         T        | <br />
| F | T |   T   |   T  |     T    |         T        | <br />
| T | F |   F   |   F  |     F    |         T        | <br />
| T | T |   T   |   F  |     T    |         T        | <br />
<br />
1 - Convert Infix Expression to Postfix Expression<br />
2 - Evaluate a Postfix Expression<br />
3 - Create a Truth Table for a Postfix Expression<br />
4 - Help<br />
5 - Exit<br />
<br />