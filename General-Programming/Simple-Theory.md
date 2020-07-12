# General-Programming
---
### <a id="Title">Simple-Theory</a>

Okay. Here I will talk about some general simple programming theory which is generally shared across all languages.<br>
I will give examples of various programming languages, but I will not go into one specific language here.<br>





---
### <a id="Syntax">Syntax</a>

Syntax refers to the spelling and grammar of a programming language. <br>
Computers are inflexible machines that understand what you type only if you type it in the exact form that the computer expects.<br>
The expected form is called the syntax.<br>


---
### <a id="Variables">Variables</a>

Variables are used to store information to be referenced and manipulated in a computer program.<br>
They also provide a way of labeling data with a descriptive name, so our programs can be understood more clearly by the reader and ourselves.
It is helpful to think of variables as containers that hold information. Their sole purpose is to label and store data in memory.<br>
Usually every variable you create, you create with a certain purpose.This purpose reflects on the data type and the variable name you give it.<br>

---
### <a id="DataTypes">Data Types</a>

> * Data types define the type of data a variable can hold
> * A data type is a type of data. Of course, that is rather circular definition, and also not very helpful. Therefore, a better definition of a data type is a data storage format that can contain a specific type or range of values. When computer programs store data in variables, each variable must be assigned a specific data type.

Every programming language has data types. Some make it obvious, some don't.<br>
But every modern programming language shares the same core data types.<br>
You can take a look at some basic data types [here](Data-Types.md).


---
### <a id="Functions">Functions (/Methods)</a>

> * A function is a block of organized, reusable code that is used to perform a single, related action. Functions provide better modularity for your application and a high degree of code reusing. 
> * In programming, a named section of a program that performs a specific task. In this sense, a function is a type of procedure or routine.

A function, depending on the context (/programming language), also called *procedure* or *method*, encapsulates a certain algorithmic or Task.<br>

Let's say you have created your own sorting algorithm. And you need to use it multiple times in your code.<br>
Instead of copy and pasting the algorithm over and over in your program, you put it in a method and you only call the method wherever<br>
One example in Python:<br>

So instead of doing this:<br>


```python
def main():
  print("Enter the number 1!")
  myVariable = input()
  if myVariable == 1:  
    #Your algorithm which you made...
    #Which takes up...
    #Many...
    #Lines...
    #Of...
    #Code...
  else:
    print("Your number is not 1, but we will change that.")
    myVariable = 1
    #Your algorithm which you made...
    #Which takes up...
    #Many...
    #Lines...
    #Of...
    #Code...

if __name__ == '__main__':
  main()
```

You should rather do this:<br>

```python
def MyOwnAlgorithm():
    #Your algorithm which you made...
    #Which takes up...
    #Many...
    #Lines...
    #Of...
    #Code...

def main():
  print("Enter the number 1!")
  myVariable = input()
  if myVariable == 1:
    MyOwnAlgorithm()
  else:
    print("Your number is not 1, but we will change that.")
    myVariable = 1
    MyOwnAlgorithm()

if __name__ == '__main__':
  main()
```







[Under construction]
















