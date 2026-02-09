# APS145 - Applied Problem Solving

# Activity-5 (2.5%)

# Submission Instructions

At the start of class your professor will provide you with a worksheet for you to write your answers to the activity questions.

At the end of class, you must submit your worksheet(s)for grading (see the [grading rubric](./README.md#rubric) at the end of this page).

> [!CAUTION]
>
> **Worksheets will NOT be accepted after the end of class and no online submissions will be allowed**. 
> 
> This is an interactive class and **requires attendance** - if you are not present to actively work on the activity questions and participate in the discussions, you will not receive marks for the activity.

---

# Introduction

This activity will continue to build on the concepts covered in the previous activities, but will be focused on incorporating [collections](https://seneca-scpa.github.io/Applied-Problem-Solving/data-collections).

Storing data in collections provides applications with the ability to retain information for future uses/reference in an easy to manage construct. Using data stored as a collection, will usually involve iteration as a means to cycle through all the data which can be required for searching, aggregating, or counting/summing data. This activity will explore how to implement this behaviour into an algorithm.

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

# Question-1

1. Define the logic for an application a user can use to develop a list of "To Do Items". A list item can be a single word or a short sentence, so if it contains many words, that's okay, it will still be assumed to be a single item (example "Homework" vs. "Do Homework after dinner"). The list should be flexible enough to allow the user to add as many items to the list as needed. After all the items are entered by the user, the application should provide proof of the stored data and display the list back to the user. After displaying the list items, the application should also confirm if the user is done and no longer wishes to add any more items - if the user is not done and wants to add more items you should permit this, otherwise, exit the application with an appropriate closing message.

2. Identify **all the key data collection statements** you had to use to work with the "To Do" list and provide a brief description why each is a key statement.

3. Briefly describe how you managed to limit repetition so your solution doesn't repeat defining statements/logic multiple times.

4. What **Computation Thinking** component was applied in determining question #3?

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

# Question-2

1. Define the logic for an application a user can use to manage their Seneca semester-1 courses. The application should permit the user to add at least one course but no more than six (6). The application should not be allowed to end if no courses are added. Since it is very human to make errors, you should also build into the logic the ability to remove a course from the list. A course is defined using the Seneca course code (example: IPC144, OPS102, etc.). Should you  display the course listing at any point in the application, the total number of courses in the list should be include. Think about how the logic SHOULD work so the user and code logic is as efficient as possible. Don't forget to keep the user informed by using appropriate messaging.

    **NOTE**: You **don't** need to validate the course code value entered by the user.

2. Describe what you found particularly challenging in answering this question.

3. What parts of the Computational Thinking model do you think you were not able to apply effectively in the development of your solution?

> [!IMPORTANT]
> Your professor will lead a discussion on your solutions and review potential answers. This is a good chance to evaluate with feedback on what makes a poor solution from a good solution. If you have questions, this is the time to ask and explore - **don't hold back!**
>

---

# Question-3

1. Define the logic for an application a user can use to manage their shopping list. An item on the shopping list is defined by having three related pieces of information: 
    * Item description (product name or other helpful identifier)
        * NOTE: This piece of information is what makes an item unique and should be used when identifying duplicates or finding matching items.
    * Unit price (price of one)
    * Quantity needed

    The application should provide the user the means to manage the shopping list supporting all the basic needs like adding, removing, modifying/changing existing item information and displaying the list details. Duplicate items should not be allowed - if the user attempts to add a duplicate, the existing item details should be displayed and the user should be given the option to make changes to any of the three related pieces of information. When the shopping list is displayed, it should include the number of items on the list, the total number of items (ie: quantities), and the total expected cost if all items on the list are purchased (don't worry about taxes).

> [!WARNING]
> Future topic: "Structures" is not permitted in this activity! You must use another method to manage the data (if you don't know what structures are that is good! We will deal with structures next week).

> [!TIP]
> This question is more complex and you might want to work in groups to help you get through it. Think about how you can break apart the problem into smaller assignable parts so each group member can work on a part of the problem without duplicating your efforts!
> 
> There are also many similarities with the previous question so you might want to incorporate some aspects of that solution.

2. Whether you completed this question or not, can you now identify how you could have broken down this problem into smaller parts of responsibility so other members could work on it at the same time without too much overlap or conflict in responsibilities? What parts can you identify?

3. Data is integral to this problem/solution. How did you accomplish organizing the related item information to manage all the items? What is the technical term for the technique you applied?

4. Overview how would you best go about testing the logic to ensure correctness?


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