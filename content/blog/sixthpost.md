---
title: Pseudocode
date: 2023-09-08
tags:
  - Codepen
---
In the session for pseudocode we learnt how it is applied to help developers understand and draft solutions to assist with problem solving. Here we were given challenges on how we would write pseudocode for different situations. 

<a href= "https://codepen.io/Steelaxel/pen/RwEzGKB">Here are some examples</a>

<div class="box">
<pre>
Task 1 - Reading List
Declare listofbooks - a list of books containing information as title(string), author(string), already read (a boolean (true/false) if already read or on reading list)

Loop through the listofbooks, set currentbook to currentBook
IF currentBook has been read (true)
 Print "Book already read {title} by the following {author}"
ELSE
 Print "Book is still in reading list {title} by the following {author}"
</pre>
</div>

<div class="box">
<pre>
Task 2 - Recipe
Declare listofrecipes - a list of recipes contain information as title(string), servings(numbers), ingredients(an array of strings), directions(string)
 Loop through listofrecipes, set current recipe to currentRecipe
 Print listofrecipes.title
 Loop currentrecipe.ingredients, set  current ingredient to currentIngredient
 Print currentIngridient
 </pre>
 </div>

<div class="box"> 
<pre>
Task 3 - Fix Start
FUNCTION fixStart(inputString)
  DECLARE firstCharacter
    firstCharacter = FIRST CHARACTER of inputString
  DECLARE output
    LOOP characters in inputString, set character to currentCharacter
        IF is first character in string
            APPEND output WITH currentCharacter
        ELSE IF currentCharacter == firstCharacter
            APPEND output WITH  "*"
        ELSE
            APPEND output WITH currentCharacter
</pre>
</div>            