# Interacting with the Interpreter/Console

{% tabs %}
{% tab title="Objectives" %}
* efine and identify: **interpreter**, **string**, **integer**, **float**, **value**, **errors**, **console**, **expression**
* Use the Python interpreter to evaluate simple math expressions
* Distinguish between an integer, float, and string

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
{% hint style="info" %}
Please copy the below into the `instruction.md` markdown file
{% endhint %}

## Learning objectives

Students will be able to...

* Define and identify: **interpreter, string, integer, float, value, errors, console, expression**.
* Use the Python interpreter to evaluate simple math expressions.
* Distinguish between an integer, float, and string.

###

### Do Now - Review

Identify the key parts of the IDE (menu bar items \[run, console, +], code panel, console panel)

### Lab - Part 1

Record your answers to the following discussion questions as a Python `comment`

> Using the `console`, type in the expressions below. _The console will not save your work._
>
> Record your answers on `main.py` as a comment. If the result is unexpected, explain why.

* An example of the first one has been done for you.

**Discussion section 1**

* What does the // do? How is that different from /? And how are those different from %?
* What's the difference between 3.0 and 3?

**Discussion section 2**

* What happened when you typed in a?
* What do you think that error message mean?

**Discussion section 3**

* What was the difference between the two inputs?
* What do you think the error message means?
* You can't combine different types!
* Now, give students time to work on section 4.

**Discussion section 4**

* What error did you get? What do you think that means?
* What happens when you multiply strings?

###

### Lab part 2

> **Before going to the IDE**
>
> * For each item, predict: the data type of the result (String/Integer/Float) and the result
> * Record both as a `comment`
> * Then, record the actual result.

* An example of the first one has been done for you.
{% endtab %}

{% tab title="main.py" %}
```python
# Interacting with the Interpreter/Console

### Lab - Part 1 ###----------------------------------
# Section 1
#a. Input: 5 + 2 * 2, Output: 9
#b.
#c.
#d.
#e.
#f.

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
## Lab 1.02 - Using the Interpreter



### Part 1

Using the `console`, type in the expressions below. _The console will not save your work._

Record your answers on `main.py` as a comment. If the result is unexpected, explain why.

#### Section 1

|   | **Input**      | **Output** |
| - | -------------- | ---------- |
| a | `5 + 2 * 2`    |            |
| b | `2/3`          |            |
| c | `2.0 * 1.5`    |            |
| d | `(2 + 3) * 10` |            |
| e | `5.0 // 2`     |            |
| f | `5.0 % 2`      |            |

#### Section 2

|   | **Input** | **Output** |
| - | --------- | ---------- |
| a | `a`       |            |
| b | `'a'`     |            |

#### Section 3

|   | **Input**   | **Output** |
| - | ----------- | ---------- |
| a | `'a + b'`   |            |
| b | `'a' + 'b'` |            |

#### Section 4

|   | **Input**   | **Output** |
| - | ----------- | ---------- |
| a | `'a' * 'b'` |            |
| b | `'a' * 2`   |            |

###

### Part 2

**Before going to the IDE**

* For each item, predict: the data type of the result (String/Integer/Float) and the result
* Record both as a `comment`
* Then, record the actual result.

|   |    **Expression**   |
| - | :-----------------: |
| a |       `10 * 2`      |
| b |       `.5 * 2`      |
| c |        `10/2`       |
| d |        `10%2`       |
| e |       `2 ** 3`      |
| f |      `(2+5)*3`      |
| g |     `2 + 5 * 3`     |
| h | `'ab' + '12' + '3'` |
| i |         `x`         |
| j |    `"ab" + "cd"`    |
| k |     `'abc' * 2`     |
| l |  `'1'*2 + '2' * 3`  |
| m |  `1 * 2 + '3' * 2`  |
| n |      `'A' ** 2`     |
| o |      `'bc' % 2`     |
| p |      `'bc' / 2`     |
{% endtab %}

{% tab title="Instructor's Notes" %}
* [ ] Display the IDE
  * [ ] Review with students, identify the key parts (menu bar items \[run, console, +], code panel, console panel).
* [ ] After going over the three parts of the IDE have students check that they can still log into their IDE account.
* [ ] Complete the Guided activity, Part 1 of the lab
  * [ ] Have students all bring up their console on their computer.
  * [ ] The part on right half of the screen is called a **console**
  * [ ] The **console** is a place where you can interact with a program
  * [ ] The **interpreter** runs Python code.
  * [ ] To run the Python interpreter, type code into the console and hit "Enter" or click "Run", the code executes immediately.
  *   [ ] Make sure all the students are able to do this and then give out the lab worksheet.

      ####
* [ ] Give students time to work on section 1.
  * [ ] Discuss with students the discussion questions. Have them answer as a comment on `main.py`
*   [ ] Go over the following two terms:

    1. **Floats**: a data type, number with a decimal point.
    2. **Integers**: a data type, number without a decimal point.


* [ ] Give students time to work on section 2
  * [ ] Discuss with students the discussion questions. Have them answer as a comment on `main.py`
  * [ ] Go over **String**: a data type, characters surrounded in single or double quotes.



*   [ ] Give students time to work on section 3.

    * [ ] Discuss with students the discussion questions. Have them answer as a comment on `main.py`
    * [ ] Go over **Concatentation**: Strings can be combined using `+`.

    ``
* [ ] Give students time to work on section 4.



* [ ] Discuss with students the Order of Operations is the same as what students have learned in math class.



* [ ] Go over the instructions for part 2 of the lab
  * [ ] Make sure students write down their predictions before going to the interpreter/IDE to check the actual output.
  * [ ] Ask students to give an example of an expression.
  * [ ] Define **expression**: a combination of values and operators (and variables)



* [ ] Debrief with students
  * [ ] Discuss any surprising/unexpected results
  * [ ] Talk about how single and double quotes are interchangeable.&#x20;
  * [ ] Show an example of multiplying strings.
  * [ ] Discuss why it might be helpful to have an interactive console.
{% endtab %}
{% endtabs %}





