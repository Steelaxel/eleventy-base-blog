---
title:  Intro to JS - Loops, Arrays and Objects
date: 2023-09-07
tags: Codepen
---
In this session we learnt about the following
Loops - Are an easy way to do something repeatedly
Arrays - Can store items under a single variable name
Objects - This is used to store various collections of properties

Here are some examples of we demonstrated our knowledge of the fundamentals of javascript.


<a href="https://codepen.io/Steelaxel/pen/eYbwojB">Task 1 - Percentage Calculator</a>
<div class="box">
<pre>
const inputNumber = prompt('Please enter a number')
const inputPercentage = prompt('Please enter a percentage')      
percentageCalculator = (inputNum, inputPerc) => {
  if (inputNum && inputPerc) {
    return inputNum * inputPerc / 100
  }
}      
var value = percentageCalculator(inputNumber, inputPercentage)
console.log(value);
</pre>
</div>



<a href="https://codepen.io/Steelaxel/pen/ZEVdZNL">Task 2 - Switch Statement</a>
<div class="box">
<pre>
const arrSize = ["Small", "Medium", "Large"];
const arrFlavour = ["cola", "lemon", "orange"];
const inputSize = prompt("Please enter a Size");
const inputFlavour = prompt("Please enter a Flavour");
drinkOrder = (size, drink) => {
let drinkLabel;
if (!arrSize.find((a) => a.toLowerCase() === size.toLowerCase())) {
alert("Please select available size");
} else if (!arrFlavour.find((f) => f.toLowerCase() === drink.toLowerCase())) {
alert("Please select available flavours");
}
else {
switch (drink) {
case "lemon":
drinkLabel = "Lemonade";
break;
case "orange":
drinkLabel = "Orangeade";
break;
default:
drinkLabel = "Cola";
break;
}
alert(`You have ordered a ${size} ${drinkLabel}.`);
}
};
drinkOrder(inputSize, inputFlavour);
</pre>
<div>

<a href="https://codepen.io/Steelaxel/pen/poqXmzE">Task 3 - Calculator</a>
<div class="box">
<pre>
const number1 = prompt('Please enter number')
const number2 = prompt('Please enter number')
const operator = prompt('Please enter operator')
function calculator(number1, number2, operator) {
switch (operator) {
case "+":
return number1 + number2;
case "-":
return number1 - number2;
case "*":
return number1 * number2;
case "/":
if (number2 === 0) {
return "Division by zero is not allowed";
}
return number1 / number2;
default:
return "Invalid operator";
}
}
alert(calculator(number1,number2,operator))
</pre>
</div>