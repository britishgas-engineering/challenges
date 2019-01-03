
# Overview

As the owner (and sole developer!) of Shine Energy Inc, you are going to build a simple bill calculator web application. 

The following is what the application should do (trust us it is a lot simpler than it sounds),

1. Collect meter readings from the user for their gas and electricity (2 simple text boxes? maybe there is a better way you can think of :thinking:)
2. Calculate and display gas and electricity units used from the input meter readings (Assume previous meter read was 11000. So gas units used would be `gas meter reading - 11000`)
3. Calculate and display bill amount in pounds for gas and electricity separately (Multiply units by price per unit. First 100 units are charged at 10p per unit and the rest are charged at 20p per unit)

## Sample calculation below for gas

Gas meter reading entered => 11400

Gas units used => 11400 - 11000 => 400

Gas bill amount => (100 * 10) + (300 * 20) => 70000p (£70)

## What tools you can use?

Any JS/CSS framework or library you love or even vanilla JS/CSS implementations!

## What we would like you to think about

1. Feel free to be creative with the user interface of the application, while keeping in mind that users like things to be easy to understand and use. What's the thinking behind your UI design?
2. How will the UI work on small screen devices like your mobile phone (and people using it only with a keyboard)?
3. How did you organize the code for the application and why did you do it that way?
4. What edge cases caused your calculation code/application to fail?
5. Can you write simple automated tests for the code?
6. How did you validate the inputs from the user (trying to subtract a text string from a number is recipe for disaster!)?
7. What can be improved?

Please upload your code to a public github repository before you arrive for the assessment day. You will get a chance to blow us away with a demo of your application on the day!

## The extra mile

😍Show us what you can do with a real API. On top of the current challenge:

1. Do a GET on the `https://shine-energy.netlify.com/.netlify/functions/meter-readings` to get the user's previous gas and electricity meter readings instead of hard coding this as 11000.
2. Only allow the user to enter a number above the user's previous meter readings.

