# APS145 - Applied Problem Solving

# Activity-1 (2.5%)

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

These activities are focused on the following:

* Applying [data recognition](https://seneca-scpa.github.io/Applied-Problem-Solving/computational-thinking#data-representation): Identifying the important information from the problem
* Creating [variables](https://seneca-scpa.github.io/Applied-Problem-Solving/variables) for the identified important information
* Time "constants" for accessing current date and time information
* Applying [decomposition](https://seneca-scpa.github.io/Applied-Problem-Solving/computational-thinking#decomposition) to identify the needed logic to solve the problem (Q-4 and Q-5)
* Creating solutions that include user input and displaying output (Q-4 and Q-5)
* Creating flowchart solutions
* Creating pseudocode solutions

Take a moment to review the course notes on these topics

---

# [Computational Thinking](https://seneca-scpa.github.io/Applied-Problem-Solving/computational-thinking)

The below questions involve the application of:
* Understanding the problem
* Decomposition
* Data Representation
* Algorithm

---

# Question-1

An application is needed to get user input for a 4-digit year value which will later be used in displaying the title "Seneca YYYY" where the [YYYY] will be the year variable's value. Identify the variable required for this problem. Focusing only on the data (not the process), how would the variable be declared/documented for both pseudocode and flowchart forms?

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

# Question-2

**Preface**

It is common for programmers to access the **current** date and time information in solutions. You will need to refer to the keyword "`NOW`" to access the different attributes of the date and time parts. Here is how you would access these parts:

|Date/Time Part | Result |
| ----- | ----- |
|`NOW` | 2025-06-01 23:59:59 |
|`NOW::Date` | 2025-06-01 |
|`NOW::Time` | 23:59:59 |
|`NOW::Year` | 2025 |
|`NOW::Month` | 06 |
|`NOW::Day` | 01 |
|`NOW::Hour` | 23 |
|`NOW::Minute` | 59 |
|`NOW::Second` | 59 |

> [!TIP]
>
> Depending on the context and for simplification, the Month and Day parts can either be the numerical or alpha representations.

**Problem Question**

An application is needed to display the current 4-digit year as a title "Seneca YYYY" (where the [YYYY] is a predetermined year value using a variable). Identify the variable required for this problem. Focusing only on the data (not the process), how would the variable be declared/documented for both pseudocode and flowchart forms?

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

# Question-3

An application is needed to display the current 4-digit year, month, and day as a title "Seneca M D, YYYY". All these values are stored to variables (where the [YYYY] is a predetermined value, and the [M]onth and [D]ay are user-entered values). Identify the variables required for this problem. Focusing only on the data (not the process), how would the variables be declared/documented for both pseudocode and flowchart forms?

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

# Question-4

Continuing the previous question, now add the sequential steps (process) for fully describing how the user would be prompted for the inputs and the displaying of the title. Document a flowchart overview of this process and a detailed pseudocode for this problem.

> [!TIP]
>
> 1. The flowchart no longer requires variables.
>
> 2. The flowchart will be greatly simplified now that it can **refer to the detailed pseudocode function** which will fully describe the process.
>
> 3. The pseudocode details should represent a function with the name `ShowTitle`.
>

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

# Question-5

A software solution is needed to collect Seneca student application information. The solution should prompt a student for their application information which should include the following details:

* Student name
* Date of birth
* Residency Information (ex: **DOM** for domestic or **INT** for international)
* Starting term (ex: **Fall** or **Winter** or **Summer**)
* Program Code (ex: **CPP** or **CPA**)
* Choice number (ex: **1** or **2** or **3**)

After getting the user-input information, the solution should summarize all the data to the screen to confirm the information was stored to variables successfully.

Document a flowchart overview of this process and a detailed pseudocode for this problem. The pseudocode part should represent a function named `GetApplicationInfo`.

Review the following example execution of the logic if it were to be coded as an application and match this logic in your answer.

```
Please enter the following information...

First name: Jiminy
Last name : Cricket
Birthdate YEAR : 2005
Birthdate MONTH: 11
Birthdate DAY  : 20
Residency: INT
Program Start Term: Fall
Program Code: CPA
Program Choice: 1

Testing data entered...

Application Date: 2025-09-24
Student Name    : Cricket, Jiminy
Birthdate       : 2005-11-20
Residency       : INT
Term Start      : Fall
Program Code    : CPA
Program Choice  : 1

```

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
