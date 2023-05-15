---
description: Set Up
---

# Calculator Porject



{% tabs %}
{% tab title="Objectives" %}
*

#### Key Terms

*
{% endtab %}

{% tab title="Lesson.md" %}
{% hint style="warning" %}
Please copy the below into the `instructions.md file`
{% endhint %}

### Python/IDE Intro

**Introduce Python**

* **Python** is a text-based programming language, uses tabbing/indentation to control execution, and is known for its readability.
* _**Look**_ at this example of a Python program. Make 3 observations about the program.

```python
print("hello world")

def my_function(name):
    print("hello world, " + name)

my_function("Susan")
```

* Discuss your observations with a classmate
* Record your observations as a comment in `main.py`

**Comments**

```python
#This is a comment.
#The IDE or console will -not- run this as part of the program

print('This is not a comment. This will show and be run as Python code.')
```

**IDE - Integrated Development Environment**

* An **IDE** is an application that allows you to create, edit, save, and run programs.
* Note that with Python, we can't use drag and drop blocks anymore - it is a language that must be typed into an IDE.
* Identify the different parts of the Replit IDE

#### Activity

* Copy the program code from Python/IDE Intro above into the IDE (the left side)
* Run the program (press _Run_ at the top)
* What do you think happened?
* Record your answer as a comment
{% endtab %}

{% tab title="main.py" %}
```python
# Variables
num1 = 0
num2 = 0
result = 0

# Functions
def addTwo():
	result = num1 + num2
	print()
	print("---------------")
	print("The result is: "+result)
	

def subTwo():
	pass # remove this line and replace the function with the algorithm

def mulTwo():
	pass # remove this line and replace the function with the algorithm

def divTwo():
	pass # remove this line and replace the function with the algorithm

### PROGRAM START ###

#-------------- Introduce the program

	

#-------------- Ask the user what operation they want to do

	

#-------------- Ask the user what numbers they want to apply the operation to
	


#-------------- Depending on the user's choice, the program should apply the proper operation

# if ():
	#
# elif ():
	#
# elif ():
	#
# elif():
	#
	
	
### PROGRAM END ###
```
{% endtab %}

{% tab title="Example Solution" %}
```
# Variables
num1 = 0
num2 = 0
result = 0

# Functions
def addTwo():
	result = num1 + num2
	print()
	print("---------------")
	print("The result is: "+str(result))
	
def subTwo():
	result = num1 - num2
	print()
	print("---------------")
	print("The result is: "+str(result))

def mulTwo():
	result = num1 * num2
	print()
	print("---------------")
	print("The result is: "+str(result))

def divTwo():
	result = num1 / num2
	print()
	print("---------------")
	print("The result is: "+str(result))

### PROGRAM START ###

#-------------- Introduce the program
print("Hello! Welcome to my calculator!\n---------------------\n")
	

#-------------- Ask the user what operation they want to do
userInput=input("Do you want to (A)dd, (S)ubtract, (M)ultiply, or (D)ivide? ")
print()


#-------------- Ask the user what numbers they want to apply the operation to
num1 = int(input("What is the first number you are applying the math to? "))
num2 = int(input("What is the first number you are applying the math to? "))


#-------------- Depending on the user's choice, the program should apply the proper operation

if (userInput=='a')or(userInput=='A'):
	addTwo()
elif (userInput=='s')or(userInput=='S'):
	subTwo()	
elif (userInput=='d')or(userInput=='D'):
	divTwo()
elif (userInput=='m')or(userInput=='M'):
	mulTwo()
```
{% endtab %}
{% endtabs %}
