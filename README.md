Download Link: https://assignmentchef.com/product/solved-pl-assignment-3-a-simple-math-quiz-using-javascript-and-html
<br>
<strong>Assignment 3</strong>

Implement a simple math quiz, whose interface is given below, using JavaScript and HTML.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/270.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/270.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>The user can choose to do a quiz on integer/float/complex-number addition or subtraction. If the user chooses integer addition, then the program randomly generates two integers X and Y (0&lt; X,Y &lt; 10), and display X+Y on the screen using the prompt dialog box (shown below). You can use Math.floor(Math.random() * 10) to generate a random integer.

After the user provides the answer and clicks OK, an alert dialog box is displayed that shows (1) whether the answer is correct, and if the answer is wrong, then give the correct answer; (2) the total number of questions the user has answered; (3) the number of correct answers; and (4) the number of wrong answers.  Sample outputs are given below.

If the user chooses float addition, then the program randomly generates two floating points X1.X2 and Y1.Y2, where 0&lt; X1, X2, Y1, Y2 &lt;10, and X1, X2, Y1, and Y2 are integers.  If the user chooses complex number addition, then the program randomly generates two numbers X1+X2i and Y1+Y2i, where 0&lt; X1, X2, Y1, Y2 &lt;10, and X1, X2, Y1, and Y2 are integers.  The sum of the two numbers is (X1+Y1) + (X2+Y2)i.

Subtraction is done similarly.

The user can also check his or her scores by clicking the “Check Score” button, which shows (1) the total number of questions the user has answered; (2) the number of correct answers; and (3) the number of incorrect answers.  A sample output is given below.  If the user has not answered any questions, then 0 will be displayed in all fields.

Finally, the user can reset his/her scores by clicking “Reset Score” button, which resets Total, Correct, and Wrong to 0.