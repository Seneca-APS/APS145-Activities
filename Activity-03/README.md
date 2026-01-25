# APS145 - Applied Problem Solving

# Activity-3 (2.5%)

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

This activity will continue to build on the concepts covered in the previous activities, but will be focused on incorporating [selection](https://seneca-scpa.github.io/Applied-Problem-Solving/selection).

Selection provides applications with the ability to adapt to changes by evaluating for specific conditions and execute different logic paths. This activity will explore how to implement this behaviour into an algorithm.

Take a moment to review the course notes on this topic.

---

# [Computational Thinking](https://seneca-scpa.github.io/Applied-Problem-Solving/computational-thinking)

The below questions involve the application of:
* Understanding the problem
* Decomposition
* Data Representation
* Algorithm
* Testing

---

# Question-1

1. You need to create an application to prompt a user to indicate if they are HAPPY for the current day (ie: TODAY) which is either a YES or NO answer. Based on this answer the application should only display a message if they are happy "That's GOOD, you are happy today!". The application will also prompt the user for their level of happiness for YESTERDAY and it will consist of three inputs covering the entire day: morning, noon, and evening. The scale of happiness is based out of 5 with the range of 1.0 to 5.0 inclusive. The overall day's happiness rating will be determined based on the average of these three inputs and if the day's level of happiness is less than 2.5, then a message should be displayed: "Ahhh Sorry to hear you were SAD yesterday!", otherwise, no additional message is displayed.

    To help you out with the desired flow of the program, the following is an example execution of what should happen when both messages should be displayed:

    ```
    Are you happy today?
        [BUTTON: YES]   [BUTTON: NO]  **NOTE: User clicks YES button for this example**

    Using a scale from 1.0-5.0 (inclusive) where 1.0 is very sad and 5.0 is extremely happy, enter a number for the following:
    How happy did you feel YESTERDAY MORNING?: 1.25
    How happy did you feel YESTERDAY at NOON?: 2.0
    How happy did you feel YESTERDAY EVENING?: 2.6
    Ahhh Sorry to hear you were SAD yesterday!

    That's GOOD, you are happy today!
    Goodbye!

    ```

    > **IMPORTANT:**
    > 
    > * The **flowchart** `main` function should deal with the CURRENT DAY logic.
    >
    > * The **pseudo code** detailed function should deal with logic for YESTERDAY. You will have to come up with a good function name and be sure to describe it's purpose including parameters and return values (if any).

2. What **type** of selection is being applied in the main flowchart function... why?
3. What **type** of selection is being applied in the pseudocode detailed function... why?
4. What are the possible combinations of outputs for this logic - briefly describe each scenario?

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

# Question-2

1. You need to create an application that will simulate hacking Seneca's grading system. 
    
    **main:**
    
    When the application starts, a warning message should be displayed prompting the user to confirm if they wish to continue: "WARNING! Hacking your grade is illegal and will not be tolerated and is subject to various forms of punishment. Are you sure you want to proceed?" (two buttons will represent the answers yes/no). When the user presses the NO button, a message should be displayed "You have high moral standards - good for you!" however, if the "YES" button is pressed, a message should display "You've chosen a dark path and are at high risk of being expelled." Regardless of the initial user response, a pseudocode function should be called which will require the user answer (YES|NO) to be passed as an argument so the function will know how to proceed with the grade hack.
    
    **Pseudocode function:**

    This function must receive the required data indicating if the user is interested (YES|NO) in hacking their grade. The function does not need to return any values. When the user is interested in hacking their grade (based on the received data), display the message: "Shame on you for attempting this illegal act! You will be reported and expelled!". On the other hand, if the user was not interested in altering their grade, display the message: "You will be reported as a stellar student and put into a raffle for free tuition next term!".

    > **IMPORTANT:**
    > 
    > * The **pseudo code** detailed function will require you to come up with a good function name and be sure to describe it's purpose including parameters and return values (if any).


2. What **type** of selection is being applied in the main flowchart function... why?
3. What **type** of selection is being applied in the pseudocode detailed function... why?
4. What are the possible combinations of outputs for this logic - briefly describe each scenario?

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

# Question-3

1. You need to create an application that will:

    **main:**
    
    First ask the user if they want to select an option from a menu (YES or NO answer) and if not, then a message should be displayed "There's nothing to do then... Goodbye!" and end, otherwise, call a pseudocode function that will return a number representing the user's menu selection. The menu selection number will then be passed to a call to another pseudocode function which will process the desired menu option task and then end.

    **Pseudocode:**

    Function-1:
    
    A function (provide a meaningful name and document the function) will be needed that will be responsible for presenting a series of numeric menu options to the user and will get the user selection and return that number. The menu options are as follows:

    ```
    MENU OPTIONS
    1. Display HORSE
    2. Display COW
    3. Display CAMEL
    4. Display GOAT 
    ```

    Function-2:

    Another function (again, provide a meaningful name and document the function) will be needed to execute the desired menu option and it will need to know the menu selection number chosen (therefore, this will be a required parameter) and will evaluate that number to determine what action should be taken. Each menu option has it's own unique word that must be displayed, but if a number is given to this function that is not in the valid range of menu options a message should display "That selection has no corresponding action." This function does not return a value.


2. What **type** of selection is being applied in the main flowchart function... why?
3. What **type** of selection is being applied in the pseudo code detailed function... why?
4. What are the possible combinations of outputs for this logic - briefly describe each scenario?
5. Using your answer from #4, how might you test the logic to ensure it works properly (describe)?

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

# Question-4

1. Define the logic needed for an application that will ask a user what food they want to order. The choices are: ice cream or a burger. 

    If the user wants ice cream, a choice must be made: Do they want it in a cone or in a cup. When a cone is desired, another choice must be made: Do they want a sugar cone or a waffle cone. Should the user want a cup, a choice must be made for the size of the cup with options of medium or large. In either case, the user should be asked for the flavour of ice cream they want and if they wish to add a topping among three possible options: crushed nuts, chocolate sauce, or caramel sauce.

    If the user wants a burger, a choice must be made: Do they want a chicken burger or a beef burger. When a chicken burger is desired, another choice must be made: Do they want tomato sauce or mayonnaise. Should the user want tomato sauce, a choice must be made if the sauce should be moderately spicy or very spicy. When mayonnaise is selected, the user must qualify the kind, either Hellmann's or Kraft. When a beef burger is desired, the user must decide on the size of patty either 4oz. or 8oz. The user must also be given the option to have melted cheese. In either case (chicken burger or beef burger), the user will need to specify what side option they want: either a baked potato or home fries.

    Following the user's selections, the order details should be displayed and then a final message be displayed "Happy Eating!".

    Your solution must contain a "main" function in flowchart form and a single pseudocode function that describes the food order option logic details. Remember to provide a good name for the function and properly document the function. 

2. What **types** of selection are being applied in the pseudo code detailed function... why?
3. What are the possible combinations of outputs for this logic - briefly describe each scenario?
4. Using your answer from #4, how might you test the logic to ensure it works properly (describe)?

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