##CSE 264 – Web Systems Programming – Spring 2023
##Homework Assignment 2 - Calculator
##Due Wednesday, February 8th, 11:59pm

##Objective
To gain a better understanding of HTML DOM programming with JavaScript.

##Description
You will create a simple four function calculator in html.

##Instructions

###Overview
Create a single html page that implements a simple four function calculator in the style of the old HP calculators. You perform calculations by entering numbers, pushing them on the stack and then selecting operations (+-*/) which pop the top 2 operands off the stack, performs the operation, display the result and push it on the stack.

###Instructions

Layout
- Your calculator.html page should have a display that runs across the top and 18 other buttons below it (0-9, +, -, *, /, C, ., +/-, Push).
- You may use a table to lay out the calculator.
- The calculator should be some fixed width and be centered on the page.
- The digits should be laid out in a grid on the left and the rest of the buttons in a column to the right of the digits and/or above. In other words, make it look like a typical calculator. 
- The numbers on the digit keys, 0-9, should be red; all the others, black.
- Do a commit once you have laid out the page.

Display
- The calculator display should always be right justified. (style: text-align)
- The display should be read only.
- It should initialize with a 0 in the display and re-initilized to 0 when the C key is clicked.

Keys

- The Push button should take the current number in the display and push it on the stack.
- The four function keys (+ - * /) should pop the top 2 values from the stack, perform the operation and push the result.
- As each digit key is pressed, the digit should be concatenated to the right end of the digits in the display. If the result of a calculation is being shown in the display, then the first digit pressed should replace the result with that digit.
- The calculator should not have any notion of operator precedence.
- The +/- key should flip the sign of the number in the display (and internally).
- The C key should clear out the calculator, as if it had just been turned on.
- The calculator should ignore any attempt to key a 2nd decimal point for the number in the display.
- All the keys are used by clicking on them with the mouse.

Coding Style
- ALWAYS put a comment at the top of each file with your name, the class, and the homework number and name.
- Use a linked style sheet for <b>all</b> your styles. There should be no style declarations in your html file.
- All your JavaScript code should be placed in a separate file.
- Make sure the calculator works in Chrome. Don't worry about other browsers.
- You have to code it all yourself - no libraries.

Visual Style
- Styling should look professional: no really wide buttons or ones that aren't fully filled in, adequate margins around text, buttons should be aligned with other, etc. You can use the calculator that comes with Windows or Mac or any hand held calculator as an example.

Submission
- Make sure you commit and push your final changes to github. There should be at least a couple of other commits along the way.
- Your repo will be cloned sometime after Wed night at midnight.

Rubric
Each of the 18 buttons works correctly 4 x 18 = (use your calculator to figure it out :) ____ pts
Required comments in each file. 5 pts
HTML, CSS and JS each in a separate file. 6 pts
Proper coloring of buttons. 5 pts
Multiple commits, including one after the layout. 5 pts
Reasonably clean layout. 7 pts