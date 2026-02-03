# BMI Calculator Feature — Implementation Task

## Overview

The fitness tracking application is adding a new feature: a **Body Mass Index (BMI) calculator**.

Your task is to implement this feature inside the existing `ComputeBMI.java` class. The goal is to build a working BMI calculator using structured methods, user input, and Java’s Math utilities.

This task evaluates your ability to collect input, design and call methods, perform calculations, and produce properly formatted output.

---

## Feature Description

The BMI calculator collects user profile information and computes BMI.

The program must collect:

* User name
* User age
* Weight (in pounds)
* Height (in inches)

The system then calculates BMI using the standard formula and displays the rounded result along with the entered profile information.

---

## BMI Formula

```
BMI = (weight × 703) / (height × height)
```

---

## Technical Requirements

Your implementation must:

* Be written in Java
* Be implemented inside `ComputeBMI.java`
* Use **multiple methods** (not just `main`)
* Use **Scanner** for user input
* Use at least one method from the **Math class**
* Include:

  * at least one method that returns a value
  * at least one method that accepts parameters
* Organize logic into clearly separated methods

---

## Program Behavior

When the program runs, it should:

1. Prompt for the user’s name
2. Prompt for the user’s age
3. Prompt for weight in pounds
4. Prompt for height in inches
5. Calculate BMI using the provided formula
6. Round the BMI value
7. Display the collected profile information and BMI result

---

## Example Output Format

Below is an example of how the final output section should look after user input is completed.
Values will vary based on what is entered, but the **message format must match**.

```
Name: Jordan
Age: 18
Weight entered (pounds): 132.5
Height entered (inches): 62.5
Your Body Mass Index is 24
```

---

## Submission

Commit and submit your completed `ComputeBMI.java` implementation after verifying that it compiles and runs correctly.

