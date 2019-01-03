Overview

As the owner (and sole developer!) of Sparkle Energy Inc, you are going to build a simple bill calculator web application. 

The following is what the application should do (trust us it is a lot simpler than it sounds),

1. Collect meter readings from the user for their gas and electricity (2 simple text boxes? maybe there is a better way you can think of)
2. Calculate and display gas and electricity units used from the input meter readings (Assume last meter read was 11000. So, gas units used would be gas meter reading - 11000)
3. Calculate and display bill amount in pounds for gas and electricity separately (Multiply units by price per unit. First 100 units are charged at 10p per unit and the rest are charged at 20p per unit)

Sample calculation below for gas,

Gas meter reading entered => 11400
Gas units used => 11400 - 11000 => 400
Gas bill amount => (100 * 10) + (300 * 20) => 70000p (£70)

What tools you can use,

Any JS/CSS framework or library you love or even vanilla JS/CSS implementations!

Some things to help your thought process,

1. Feel free to be creative with the user interface of the application, while keeping in mind that users like things to be easy to understand and use. What's the thinking behind your UI design?
2. How does the UI work on small screen devices like your mobile phone?
3. How did you organize the code for the calculations and why?
4. What edge cases can cause your calculation code to fail and how did you protect against it (if you think a simple piece of multiplication code can't fail..think again!)?
5. How did you test the code that you've written? 
6. Can you write simple automated tests for the code?
7. How did you validate the inputs from the user?

