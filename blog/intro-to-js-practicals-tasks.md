---
layout: layouts/post.njk
tags: blog
title: Intro to JS Practicals - Tasks
date: 2021-06-17T20:04:11.687Z
rating: 5
---
Really interesting and engaging lesson about Javascript. We learned about Switch statements and basic programming methods. It was very useful to try something out and then see how someone else might do the same thing. I felt as though I was able to see a better way to think about tackling a problem and where I could improve my ways of thinking about solutions.



I know that it isn't much, but I was very proud of myself for figuring out how to create the calculator. I am putting the code here too in case anyone wants to look at it or play around with it.

https://codepen.io/Blutakduck/pen/WNpmQqy



```
function calculator(number1, operator, number2) {
  
    var calc
   

    switch (operator) {
        case "plus":
          
            var calc = number1 + number2;
            break;

        case "minus":
            var calc = number1 - number2;
            break;

        case "times":
            var calc = number1 * number2;
            break;

        case "divide":
            var calc = number1 / number2;
            break;

        case "modulus":
            var calc = number1 % number2;
            break;
           
            return calc;  
        
    }
    console.log(calc)
    
  }

  

  calculator(6, "plus", 5)
 

```

Looking at it now I know it is just a simple thing, but I was so pleased with myself for getting my head around it.