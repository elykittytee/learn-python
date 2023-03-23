---
description: Script Mode & Variables
---

# Printing & Variables



{% tabs %}
{% tab title="Objectives" %}
* Define and identify: **script**, **print**, **run**, **output**, **variable**
* Write a simple script and run it in the IDE or Text Editor.
* Print values out to the console (both composed values and from variables)
* Compare script mode vs interactive mode
* Know how to store a value into a variable

#### Key Terms

* IDE
* Python
* Intrepeter
* String
* Integer
* Float
* Value
* Errors
* console
* Expression
* Script
* Print
* Run
* output
* Variable
* Script Mode
* Interactive Mode
* Comments
* Storing
* Mutability
* Variable Assignment
* Input
* Debugging
* Syntax
{% endtab %}

{% tab title="Lesson.md" %}
## Do Now

* Project the Do Now on the board, circulate around the class to check that students are working and understand the instructions.

## Printing Lesson/Lab Part 1

* Explain that the file is the center section of the screen. Sometimes this is called a **script**.
* Reminder questions:
  1. how do you save/run a file?
  2. What happened when you ran the file from the do now?
* Explain the purpose of the `print` statement, which will print whatever is in between the parentheses to the console.
* Explain to students that what appears on the console is called **output**.
* Talk to students about reading a program and the order in which the computer executes statements.
* Ask students how they would print the following:

```python
Hello World
Hello World
Hello World
Hello World
Hello World
```

* Have students work on Part 1 of the lab for 10 Minutes.

## Variables Lesson/Lab Part 2

* **Variable**: a name that refers to a value.
* An assignment statement creates new variables and gives them values:

```python
>>> message = 'And now for something completely different'
>>> n = 17
>>> pi = 3.1415926535897932
```

* Ask the students what they think the assignment operator is.
* Using the example above, ask which are the variables, and which are the values.
* Tell students how assignments work from right to left, so the item on the right is assigned to the item on the left.
* Have students work on Part 2 of the lab for 10 Minutes.

#### Optional: Four Fours

* Four Fours is a mathematical puzzle where the goal is to find a mathematical expression for every whole number from 0 to some maximum, using only common mathematical symbols and the digit 4 (no other digit is allowed).
* In this version, students can use use 44 which counts as two fours even though equations for 0 to 4 can be solved without using 44.
* For example, zero can be solved with either: 44 - 44 or 4 + 4 - 4 - 4
* Students can easily be challenged by extending the limit from the 0-4 to 5 and above.


{% endtab %}

{% tab title="main.py" %}
```python
# Interacting with the Console

### Lab - Part 1 ###----------------------------------
# Section 1
#a. Expected: 1, Actual: 1, I expected the console to print the quotations.
#b.
#c.
#d.
#e.

# Section 2
#a.
#b.

# Section 3
#a.
#b.

# Section 4
#a.
#b.

### Lab - Part 2 ###----------------------------------

#a. Prediction: integer, 20
#a. Actual Result: 20

#b. Prediction: 
#b. Actual Result
```
{% endtab %}

{% tab title="Lab" %}
### Part 1

Read the following expressions and record as a `comment` the predicted output

Practice typing expressions by typing them into the editor part of the IDE. Hit `Run` at the top of the screen.

If the expression did something unexpected, record your answer. If not, move on to the next.

| Expression                                                        | Expected Output |
| ----------------------------------------------------------------- | --------------- |
| `print("1")`                                                      |                 |
| `print(1)`                                                        |                 |
| `print(1 + 2)`                                                    |                 |
| `print("1" + "2")`                                                |                 |
| `print("this" + " " + "is" + " " + "a" + " " + "sentence" + ".")` |                 |

###

### Part 2 - Variables Practice

**Use the console for this part of the lab.**

A - Type and run the following onto the console, NOT the editor

```python
animal = "dogs"
print(animal + " are really cool.")
```

Record the answers as a `comment`

* A-1 What happens?
* A-2 How would you make the program print out "cats are really cool" instead?



B - Type and run the following onto the console, NOT the editor

```python
print(dogs + " are cool.")
```

Record the answers as a `comment`

* B-1 What output does this produce?
* B-2 Why does this happen?


{% endtab %}

{% tab title="Optional: Four Fours" %}
### OPTIONAL - Four Fours Challenge

Using four 4's and any operations, try to write equations that have the numbers from 0 to 4 as the answer. You should use Python's arithmetic operations:

* \+ addition
* \- subtraction or negation
* \* multiplication
* / division
* ( ) parentheses for grouping
* \*\* power

You may also use 44 or 4.4, which count as two fours, or .4, which counts as one four. For example, one solution for zero is:

```python
print("Zero is", 44-44)
```

Can you find a different solution?

Here are what the results, but not the source code, will look like. (Note: answers may have trailing zeros if floating point arithmetic is used which is fine, i.e. 1 may be displayed as 1.0)

```python
Zero is 0
One is 1
Two is 2
Three is 3
Four is 4
```

### Bonus

Print the output below, but only using **one** line of code. Feel free to use online resources.

```python
Wow!
This is on a new line!

```

### Bonus 2

Can you find four fours for 5 to 10?
{% endtab %}

{% tab title="Instructor's Notes" %}
* [ ] Project the Do Now on the board, circulate around the class to check that students are working and understand the instructions.
* [ ] Lab - Part 1
  * [ ] Define **script**: in computer programming, a script is a program or sequence of instructions that is interpreted or carried out by another program rather than by the computer processor (as a compiled program is). Some languages have been conceived expressly as script languages.
  * [ ] Define/explain the purpose of the `print` statement
    * [ ] `print()`will print whatever is in between the parentheses to the console.
  * [ ] Define **output**: the results of whatever your script or program does
  * [ ] Define **IPSO**, the backbone process of every computer: input -> process -> store -> output
  * [ ] Project the following code snippet. Discuss how students would achieve this.

<pre class="language-python"><code class="lang-python"><strong>Hello World
</strong>Hello World
Hello World
Hello World
Hello World
</code></pre>

* Have students work on Part 1 of the lab for 10 Minutes.

## Variables Lesson/Lab Part 2

* **Variable**: a name that refers to a value.
* An assignment statement creates new variables and gives them values:

```python
>>> message = 'And now for something completely different'
>>> n = 17
>>> pi = 3.1415926535897932
```

* Ask the students what they think the assignment operator is.
* Using the example above, ask which are the variables, and which are the values.
* Tell students how assignments work from right to left, so the item on the right is assigned to the item on the left.
* Have students work on Part 2 of the lab for 10 Minutes.

#### Optional: Four Fours

* Four Fours is a mathematical puzzle where the goal is to find a mathematical expression for every whole number from 0 to some maximum, using only common mathematical symbols and the digit 4 (no other digit is allowed).
* In this version, students can use use 44 which counts as two fours even though equations for 0 to 4 can be solved without using 44.
* For example, zero can be solved with either: 44 - 44 or 4 + 4 - 4 - 4
* Students can easily be challenged by extending the limit from the 0-4 to 5 and above.
{% endtab %}
{% endtabs %}

