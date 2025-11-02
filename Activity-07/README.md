# APS145 - Applied Problem Solving

# Activity-7 (2.5%)

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

This activity is focused on more advanced concepts of [data representation](https://seneca-scpa.github.io/Applied-Problem-Solving/computational-thinking#data-representation) which involves a complex data [structure](https://seneca-scpa.github.io/Applied-Problem-Solving/data-structures). Structures can be more complex than a grouping of simple data. Structures can contain other structures ([composition](https://seneca-scpa.github.io/Applied-Problem-Solving/data-structures#structure-composition)). You can also have a [collection](https://seneca-scpa.github.io/Applied-Problem-Solving/data-collections#collection-declaration) of structures either by itself or even within a structure. 

This activity will explore how to implement complex structures and apply them in programming logic.

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
You need to make a web application to manage the DATA INPUT for a number of recipes. A recipe includes the category of food it falls within, general information about the dish, how many people it can serve, and the details of what ingredients are needed and/or are optional.

### Your Task #1
Identify the specific data needed to appropriately represent all the recipe information, then group the data into two significant structures. Define those structures for both a flowchart and pseudocode.

</br>

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

### Your Task #2
Modify your structure(s) applying [composition](https://seneca-scpa.github.io/Applied-Problem-Solving/data-structures#structure-composition) and [collections](https://seneca-scpa.github.io/Applied-Problem-Solving/data-collections#collection-declaration) to represent a single recipe. Then, show how you would declare a single variable to represent a complete recipe. Do this for both flowchart and pseudocode.

</br>

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

### Your Task #3
What must you do to represent many recipe's? Modify your work accordingly to address this requirement (to both flowchart and pseudocode) as required.

</br>

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

### Your Task #4
Review the `Problem #1` statement above again, and applying your data representation for a recipe, create/define the necessary logic for this application to work. Although the focus is on recipe DATA INPUT, you should also provide the functionality to display ALL the recipe's so the user will know the data was properly stored.

> [!TIP]
> Think about usability:
> - What should the user of the application see?
> - What options should the user have?
> - What feedback/reactions should the application provide to the user at various steps?
> 

</br>

> [!WARNING]
> You do not have to worry about UPDATING existing recipe data or ingredients.
> Focus only on the process of entering recipe data and displaying the data.
>

</br>

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

# Problem #2

## Scenario
You need to create an application to view any Seneca student course listing (courses they are registered in) for a user specified term. Here are some things to consider while you digest the scope of this problem:

* There are many campuses (King, Newnham, York)
* Rooms are coded with building letter identifiers (ex: K3000, A2024 etc.)
* A class is different from a course (you can have many classes of the same course)
* Courses are run by section (ex: IPC144 has many classes of different students based on section groupings)
* A room is different from a class (a room can be used for many other classes)
* Schedules are based on time intervals for each class
* Classes can be scheduled more than once in a week
* Classes can have different designations (lecture, lab, etc.)
* Classes are scaled for a limited number of students
* A course can be delivered in many "modes" (ex: in-person, online, hybrid, flex)
* Courses are offered three times a year (Fall, Winter, Summer), therefore, student could have up to three schedules in a year period.

Viewing a student course listing will not be in a tabular "week view" format as this would prevent you from displaying all the possible details for a course. The objective is to view all the information for a specific student's course listing for a specified study term.

---

### Your Task #1
Identify all the data you would need for the application. Group tightly-related data into specific structures. Think about how to arrange the information - do you apply COMPOSITION, COLLECTIONS, both? Define all the structures and represent them in both flowchart and pseudocode format (don't worry about creating variables - just the definitions). These will be used in Task #2!

</br>

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

> [!WARNING]
> DO NOT continue to Task #2 until you have had your class discussion and all students are using the SAME data structure's. Take the time to understand how the data is organized!
> 

---

### Your Task #2
Define the logic needed for this application. You will need to provide a feature to search student data  before you can show the course listing details. Are there (should there) be different ways to look up a specific student? You should provide as much context as possible in addition to how you display the data  itself (ex: student information, the term information, campus etc.) and think about how the information should be displayed to make it easy to read.

> [!TIP]
> In order to search for a student schedule, you will need the ability to "load" Seneca's student data which would consist of thousands of student records with schedule information.
>
> You can use this **closed-box function** to get the data: `LoadStudentData()` which explicitly returns a collection of student data.
>
> **You may assume this data will match your structure scheme but it is up to you how to use the data with your logic.**
>

</br>

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