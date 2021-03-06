# General-Programming
---
### <a id="Title">Data types</a>

You might already know them, you might not. But pretty much every programming language shares the same core-data types.<br>
Let's take a look at them. :)<br>

---

#### integer:<br>
An integer is a number. A whole number.<br>
Normally that whole number has to be in the range within *-2,147,483,647 to 2,147,483,647*.<br>
So there is probably plenty of room for your normal needs :P<br>
The range of this comes from the way integers are saved within your ram.<br>
And the reason that the majority of programming languages stay conservative and pick up that range is,<br>
because as soon as a language has such values of a different memory managment,<br>
it cannot be passed to another system, due to incompability.<br>
Code examples of how a declaration looks in<br>

Python:
```python
foo = 10
```

C#:
```csharp
int foo = 10;
```

Javascript:
```javascript
let foo = 10;
```

#### character:<br>
A character is simply one single character. It can hold pretty much whatever you want it to.<br>
A letter, a number, a symbol, whatever you want.<br>
There surely are exceptions of what can not be stored, but this falls to the programming language you're using.<br>
Code examples of how a declaration looks in<br>

Python:
```python
foo = 'A'
```

C#:
```csharp
char foo = 'A';
```

Javascript:
```javascript
let foo = 'A';
//Funnily enough, in javascript characters do exist, but are rather seen as a single-letter string and not specifically as its own type.
```

#### string:<br>
A string is text. To use more terminology, a string is a sequence of characters.<br>
The maximum length of how long a string can be, differs from language to language.<br>
However, text may always be within **"quotation marks"** or **'simple quotation marks'**.<br>
Everything in between those quotation marks is seen as literal text. Everything outside of the quotation marks is seen as part of the language's syntax.<br>
Code examples of how a declaration looks in<br>

Python:
```python
foo = "Hello World"
```

C#:
```csharp
string foo = "Hello World";
```

Javascript:
```javascript
let foo = "Hello World";
```


#### float:<br>
A float is a floating-point number, which means it is a number that has a decimal place.<br>
A float is for simple, small floating-point numbers. It can hold around 6 - 9 digits in most languages.<br>
A wide-spread similar alternative is the double. The double, as its name suggests, was originally capable of holding values which are twice as big as those of a float, around 15 - 17 digits.<br>
Code examples of how a declaration looks in<br>

Python:
```python
foo = 10.01
```

C#:
```csharp
float foo = 10.01f;
```

Javascript:
```javascript
let foo = 10.01;
//Fun fact, in the front, there is no difference between integers and floating-point numbers. In the back, every number is saved as a float in Javascript.
```


#### boolean:<br>
A boolean indicating a state, it can either be True or False.<br>
It is as simple as that.
Code examples of how a declaration looks in<br>

Python:
```python
foo = True
```

C#:
```csharp
bool foo = true;
```

Javascript:
```javascript
let foo = true;
```

#### object:<br>

Depending on your programming language, this can mean different things. Generally, just think of an object of, whatever you want to create, with multiple properties. Such as... a student-object. You can give your student-object the properties *name* and *age* for example. Those are the names of your properties.<br>
Your student's objects's property *name* can have a value.<br>
Same goes for the age property :)<br>
Code examples of how objects look in<br>

C#:
```csharp
public class Student
{
  public string Name;
  public int Age;
}

public class Program
{
  private static void Main(string[] args)
  {
    Student MyFirstStudent = new Student(){
    Name = "Peter Johnson",
    Age = 20
    };
  }
}
```

Javascript:
```javascript

var MyFirstStudent = {
  Name: "Peter Johnson",
  Age: 20
};
//This is the simplest version of an object in JS, it can also be created via a class.
```
