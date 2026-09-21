# APS145 - Applied Problem Solving

# Activity-2 (2.5%)

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

Continuing with [data recognition](https://seneca-scpa.github.io/Applied-Problem-Solving/computational-thinking#data-representation) and identifying the important information that must be managed in the solution, this activity will also incorporate [functions](https://seneca-scpa.github.io/Applied-Problem-Solving/functions) and [closed-box functions](https://seneca-scpa.github.io/Applied-Problem-Solving/functions#closed-boxes).

Take a moment to review the course notes on these topics.

## Solution Template
All solutions to problems going forward will follow this template:

**"main" Function**
* All solutions will have a **SINGLE** main function.
* The main function will always be done as a **FLOWCHART**.
* The main function should always be the overview of the solution and will not go into any great detail.
* Main will almost always need to call upon one or more complex function(s) using the appropriate symbol.
   * *Note*: Those functions will be defined separately in Pseudocode
* The main function "orchestrates" the solution acting as the starting and ending point of the solution. It will provide non-technical persons with an easy view of how the solution works.

**Additional Functions**
* All additional functions will be done in **PSEUDOCODE**
* It is imperative the function identifiers (names) are clear, concise, and meaningful so when they are referenced from "main" or another function, it is clear what the function does.
* All functions should apply a [preceding block of text](https://seneca-scpa.github.io/Applied-Problem-Solving/functions#function-documentation) that describes the parameters and brief purpose.

---

# [Computational Thinking](https://seneca-scpa.github.io/Applied-Problem-Solving/computational-thinking)

The below questions involve the application of:
* Understanding the problem
* Decomposition
* Data Representation
* Pattern Recognition
* Abstraction
* Algorithm

---

# Question-1

An application is needed to create and send an email. Identify the variables required for this problem and detail the sequential steps. The solution will require a documented flowchart overview process (main) and any additional functions (at least one additional to main will be needed) detailed Pseudocode for this problem.

> **NOTE**
> 1. **DO NOT** describe or detail the sign-in process to the email account for the sender - we will assume this has already been done.
>
> 2. To help simplify your solution, you should use a helper **closed-box** function (review course notes on this subject) called: `SendEmail` to send the email (this means you don't need to describe the details of how to send an email).
>     - HINT: The closed-box `SendEmail` function will require arguments to be sent to it. You determine what you think the function must receive for it to properly perform its task! Normally, closed-box functions will provide you with this detail, but this is an activity focused on functions so this part has been purposely left out! What do you think the function needs to receive for it to correctly be able to send an email? 
>
> &nbsp;

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

# Question-2

You must use standard variables only (no arrays etc…) and no iteration (looping). Your solution should consist of only the following functions:

| Function      | Documentation Type   | Comment |
| ------------- | :------------------: | --------------------------- |
| main          | **Flowchart**        | Overall flow only - no great detail should be described! |
| YearDataInput | **Pseudocode**       | What does this do? What argument(s) does it need? What does it return? |
| ShowResults   | **Pseudocode**       | What does this do? What argument(s) does it need? What does it return? |

With the preceding functions in-mind, find the most efficient way to accomplish the following:

An application needs to summarize rainfall precipitation accumulations for the **Malta region**. Monthly precipitation (mm) will need to be entered by the user covering a period of **three years**. The specific years are **defined by the user**.

Based on all the entered data, the application should calculate and display the following summary details:

* *Total* precipitation for the **first year** of entered data.
* *Average monthly* precipitation for the **first year** of entered data.
* *Total* precipitation for the **second year** of entered data.
* *Average monthly* precipitation for the **second year** of entered data.
* *Total* precipitation for the **third year** of entered data.
* *Average monthly* precipitation for the **third year** of entered data.
* *Total* precipitation for **all three years** combined.
* *Average yearly* precipitation for **all three years** combined.

Here is an example execution of the required logic:
```
   Rainfall Analysis for the Malta Region
   --------------------------------------

   What year is this data for?: 2020
   Enter the rainfall in mm for each month...
   January  : 25
   February : 12
   March    : 46
   April    : 52
   May      : 32
   June     : 120
   July     : 36
   August   : 12
   September: 33
   October  : 25
   November : 11
   December : 23

   What year is this data for?: 2022
   Enter the rainfall in mm for each month...
   January  : 20
   February : 64
   March    : 72
   April    : 52
   May      : 130
   June     : 56
   July     : 32
   August   : 53
   September: 45
   October  : 31
   November : 43
   December : 48

   What year is this data for?: 2024
   Enter the rainfall in mm for each month...
   January  : 35
   February : 41
   March    : 21
   April    : 108
   May      : 25
   June     : 5
   July     : 22
   August   : 14
   September: 7
   October  : 12
   November : 17
   December : 14

   Rainfall Summary
   ----------------
   2020 total precipitation:  427 mm
   2020 average monthly precipitation:  35.6 mm

   2022 total precipitation:  646 mm
   2022 average monthly precipitation:  53.8 mm

   2024 total precipitation:  321
   2024 average monthly precipitation:  26.8 mm

   Total precipitation for all three years: 1394 mm
   Average yearly precipitation: 464.7 mm
```

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---
# Question-3
Reflecting on the previous Question-2, you should have identified a **pattern**. 

1. What is the pattern?
2. What must you do to address this improvement?
3. How would you implement this change? (record on your sheet a **short excerpt** from your prior solution and how you would upgrade it to apply the changes).

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---
# Question-4

Reflecting on the previous Question-3:

1. Can you identify an **abstraction** which could be applied to further simplify the logic?
2. What must you do to address this improvement?
3. How would you implement this change? Record on your sheet an updated answer from Question-2 that implements these improvements.

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
