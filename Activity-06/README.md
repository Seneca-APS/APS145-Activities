# APS145 - Applied Problem Solving

# Activity-6 (2.5%)

# Submission Instructions

At the start of class your professor will provide you with a worksheet for you to write your answers to the activity questions.

At the end of class, you must submit your worksheet(s) for grading (see the [grading rubric](./README.md#rubric) at the end of this page).

> [!CAUTION]
>
> **Worksheets will NOT be accepted after the end of class and no online submissions will be allowed**. 
> 
> This is an interactive class and **requires attendance** - if you are not present to actively work on the activity questions and participate in the discussions, you will not receive marks for the activity.

---

# Introduction

This activity is focused on an intermediate concept of [data representation](https://seneca-scpa.github.io/Applied-Problem-Solving/computational-thinking#data-representation) which involves a data [**structure**](https://seneca-scpa.github.io/Applied-Problem-Solving/data-structures).

So far you've learned about a [variable](https://seneca-scpa.github.io/Applied-Problem-Solving/variables) which was used to represent a single value, and then you recently learned about [collections](https://seneca-scpa.github.io/Applied-Problem-Solving/data-collections) to support storing multiple values to a single variable.  A **structure** is yet another concept used to represent data but is specifically meant for storing **related** data (an object consisting of customized attributes or members) as a single variable.

Storing data in a structure provides programmers a way to organize related data efficiently and promotes:

* Easy to read data centric logic 
* Easy to use when dealing with a lot of related data
* Flexibility to adapt to more complex data requirements
* Easy to manage and maintain complex data

This activity will explore how to implement structures and apply them in programming logic.

Take a moment to review the course notes on this topic.

---

# [Computational Thinking](https://seneca-scpa.github.io/Applied-Problem-Solving/computational-thinking)

The below questions involve the application of:
* Understanding the problem
* Decomposition
* Data Representation
* Pattern Recognition
* Abstraction
* Algorithm
* Testing

---

# Problem #1

## Scenario
Imagine you are designing a simple 2D game that involves navigating paths and fighting enemies. Game settings (or configuration) is needed to manage various aspects of the game. This would include data to represent: player name, size of the world map (game board), number of enemies, number of player lives, the minimum number of enemy defeats needed to progress to the next level, level time limit, and number of game levels.

### Your Task #1
Design a **SINGLE structure** to manage all of the game related data. Choose appropriate meaningful names for clear, easy to use, and easy to maintain data representation. 

* Define the structure in **flowchart** form and create a variable of that structure in a function `main`.
* Define the structure in **pseudocode** form and create a variable of that structure in a function `main`.
     
</br>

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

### Your Task #2
Discuss how you might breakdown the structure defined in Task #1 into further potential structures. Modify your answer from Task #1 for each the flowchart and pseudocode forms to include the changes.

</br>

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

# Problem #2

## Scenario
A customer places a simple online order for a single product such as a shirt (but could need more than one) from Amazon. 

### Your Task #1
Design the necessary structure(s) that could represent the data involved in this transaction. Don't include unnecessary complexity (keep it simple) but complete enough to reflect a real-world order and focus on what would be useful for processing and tracking the order.

Some things to consider:
* Who is involved in the order?
* What item is being ordered?
* What basic information would Amazon need to fulfill the order?
* What might be useful for the customer to track or verify the order?

Define the structure(s) in:
* **flowchart** form and create a variable(s) of that structure in a function `main`.
* **pseudocode** form and create a variable(s) of that structure in a function `main`.
     
> [!TIP]
> * You do not need to implement any logic beyond the **structure definition**.
> * Don't worry about payment information.

</br>

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

### Your Task #2
Using the established structure(s) from the previous task, define the process (algorithm) for creating a simple order. This will require a simple main function (flowchart, that **owns the data**) and a detailed pseudocode function fully describing how an order is created.

> [!TIP]
> * There is a **closed-box function** you should use to help simplify the process which explicitly returns the details of a customer selected product: `GetProductSelection()`.
> * Detail only the major parts of logic required to set the necessary data to become a completed order.
> * Again, don't worry about payment details.
>  

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>  

---

### Your Task #3
Expanding your logic from the previous task, add a step to the simple main function which will show the order details and create an additional pseudocode function that fully describes how to display the details of an order.

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>  

# Problem #3 (time-permitting and extra practice)

## Scenario
Review the previous two activities (#4 and #5) and their respective solutions (yours or the instructor provided one). How might you change the solutions now that you know about structures?

### Your Task #1
Modify the solutions to apply structure concepts.

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