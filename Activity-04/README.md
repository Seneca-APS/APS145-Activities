# APS145 - Applied Problem Solving

# Activity-4 (2.5%)

# Submission Instructions

At the start of class your professor will provide you with a worksheet for you to write your answers to the activity questions.

At the end of class, you must submit your worksheet for grading (see the [grading rubric](./README.md#rubric) at the end of this page).

> [!CAUTION]
>
> **Worksheets will NOT be accepted after the end of class and no online submissions will be allowed**. 
> 
> This is an interactive class and **requires attendance** - if you are not present to actively work on the activity questions and participate in the discussions, you will not receive marks for the activity.

---

# Introduction

This activity will continue to build on the concepts covered in the previous activities, but will be focused on incorporating [iteration](https://seneca-scpa.github.io/Applied-Problem-Solving/iteration).

Iteration provides applications with the ability to repeat sections of logic where the logic is defined once. Iteration wraps around the section of logic you wish to repeat. This activity will explore how to implement this behaviour into an algorithm.

Take a moment to review the course notes on this topic.

---

# [Computational Thinking](https://seneca-scpa.github.io/Applied-Problem-Solving/computational-thinking)

The below questions involve the application of:
* Understanding the problem
* Decomposition
* Data Representation
* Pattern Recognition
* Algorithm
* Testing

---

# Question-1

1. Define the logic for an application to sum a set of user-entered numbers based on a user-defined number of numbers. For example, if the user wants specifies they want to enter 8 numbers to be summed, the application should prompt the user to enter 8 numbers followed by displaying the total result.

    * The main function should be responsible for determining how many numbers the user would like to enter and it should also display the total result (after it calls a function to get the total). 
    
    * The main will call a pseudocode function providing it the number of numbers to be entered by the user. The pseudocode function should prompt the user for each number, sum the numbers, and return the total/sum result accordingly.

    > **IMPORTANT:**
    >
    > * The **pseudo code** detailed function should have a good function name and be sure to describe it's purpose including parameters and return values (if any).

2. What **type** of iteration is being applied in the main flowchart function... why?
3. What **type** of iteration is being applied in the pseudocode detailed function... why?
4. Describe some scenario's you would use to test your logic to ensure correctness?

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---
# **IMPORTANT CHANGE**

> [!WARNING]
>
> From this point onwards (including future activities), the problems described will:
> * No longer guide you on **what logic the "main" flowchart function should be responsible for**.
> * No longer guide you on **what supporting pseudocode function(s) should be created**.
>
> You will be expected to fully apply on your own:
> * **Decomposition and pattern recognition concepts** using your own approach.
> * **Fully document** all pseudocode functions.
>
> **Hints:**
> * Keep the main flowchart function very simple.
> * The main function should be the main flow of the logic but without great detail.
> * Any logic that is complex should be put into a supporting pseudocode function(s).

---

# Question-2

1. Define the logic for an application "The Even/Odd Number Game" where the user will need to input five whole numbers between 10 and 50 inclusive. The entered numbers should be validated to ensure they are within the expected range otherwise an error message should be displayed **"ERROR: You must enter a number between 10 and 50 inclusive!"** and the user will be expected to input another number until one is valid. If the sum of all the valid five entered numbers is even (equally divisible by 2) then a point is given to the user and another round of numbers should be entered otherwise, the program should end with the message **"Your score was: \<user's score\>! Thanks for playing the even/odd number game"**. Make it easy to modify the logic if we should decide to change the valid number range and/or the number of numbers to be used in each game.

2. For each function you defined (including main), explain what **types** of iteration you applied.
3. Explain all the places where you applied **selection** and its importance.
4. Describe some scenario's you would use to test your logic to ensure correctness?

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

# Question-3

1. Define the logic for the "Guess the Secret Number" application. Here are some highlights of the key logic required:

    **Game Rules:**
    * This is a two-player game
    * 1 player will need to set the secret number (player 2 will have to look away).
    * The secret number must be between 1 and 999999 and must be validated to guarantee a valid secret number is set within that range (continue prompting as many times as necessary accordingly). Note: Player 1's  role in the game is done at this point!
    * The other player will need to guess the secret number by entering successive numbers based on feedback after each entered number.
    * Each guessed number will be evaluated relative to the secret number and respond with a hint or result: **"HIGHER!"**, **"LOWER!"**, or **"YOU GUESSED THE SECRET NUMBER!"**.
        * Example, if the secret number is 100 and the player enters 90, the response will be **"HIGHER!"**, but if the user enters 120, the response would be **"LOWER!"**, but if the user entered 100, then **"YOU GUESSED THE SECRET NUMBER!"** would be the result.
    * There are a maximum number of 10 guesses. After the 10th guess, the game ends with a message **"Ran out of guesses! Game Over!"**, however if the number is guessed correctly beforehand, the game also ends with no more guesses.
    * Each incorrect guess results in 10 points. This means the objective is to earn as few points as possible (like golf!).
    
    **Game Flow:**
    * The game should start by prompting the players if they are ready to play (YES or NO buttons).
    * If the players are ready (ie: YES), a game should be played as described above.
        * After a game is played, the score should be displayed (**"You scored: \<score\>"**) followed by a prompt asking the players if they are ready to play (they can play as many games as they wish).
        * If another game is played, it is assumed the players will switch roles and the alternate player will set the secret number so the other player gets a turn at guessing. This would continue as many times as they wish to play!
    * If the players are not ready to play anymore (ie: NO), the application should end with a message **Thanks for playing Guess the Secret Number!"**
    * Make it easy to modify the logic if we should decide to change the valid number range and/or the number of guesses and/or the point value for each incorrect guess.

2. What **types** of iteration is being applied in the main flowchart function... why?
3. Explain all the places where you applied **selection** and its importance.
4. Describe some scenario's you would use to test your logic to ensure correctness?

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

# Rubric

## Grade Categories

| Grade | Description|
| ----- | -----------|
| **Unsatisfactory** | 1. Arrived in class more than 30 minutes after start of class `OR` <br> 2. Did not attend `OR` <br> 3. Did not participate (no participation)|
| **Incomplete** | 1. Arrived in class more than 10 minutes late (but less than 30 minutes) `OR` <br> 2. Submitted work was incomplete/contains many errors `OR` <br>3. Partial participation|
| **Satisfactory** |1. Arrived in class within 10 minutes of start of class `AND` <br> 2. Submitted work that is mostly completely without flaws `AND` <br> 3. Exercised full participation|


## Grade Allocation

|  | Unsatisfactory | Incomplete | Satisfactory |
| -------- | ------- | ------- | ------- |
| **Grade** | `0.0` | `1.25` | `2.50` |