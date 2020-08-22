# CSharp
---
### <a id="Title">Project 1</a>

Let's continue....

---
#### <a id="LastStep">Last step</a>


```csharp
Console.WriteLine("What is your name?");
string name = Console.ReadLine();

Console.WriteLine("What is your age?");
int age = Int32.Parse(Console.ReadLine());

Console.WriteLine("Welcome, " + name + " you are " + age + " years old, right?");
```
This is one way to solve the task I mentioned in the last step.


```csharp
Console.WriteLine("What is your name?");
```
Prints text to the console

```csharp
Console.ReadLine();
```
Prompts input from the console

```csharp
Int32.Parse(Console.ReadLine());
```
Converts the console prompt input to an integer

```csharp
string name = Console.ReadLine();
int age = Int32.Parse(Console.ReadLine());
```
Saves the values returned by the prompt into variables

There's a lot of useful methods and keywords as you can see. I.e. you can't save values of one datatype into another, but however,<br>
you can convert one datatype into another and that way you can, for instance, store string inputs as numbers.<br>

Great! Now your program is one step closer to be flexible to whatever the user inputs :)<br>
Let's continue...

---
#### <a id="MainLoop">Main-Loop</a>

For console apps, it is common to have a main-loop to run through when having multiple options in your program. I.e. for a menu, so your program doesn't automatically end when executing one certain option.

This is done by creating a boolean variable and a loop with the condition of that boolean.<br>
Example:<br>
```csharp
bool mainLoop = true;
while(mainLoop)
{
  //Do stuff
}
```


---
#### <a id="LotsOfData">Lots of data</a>

So. Now, we always only saved one _name_ or _age_. Let's spice this up a little.<br>
We're going to make use of collections. Specifically **Arrays** and **Lists**.<brb>

First we're going to take a look at arrays.<br>
Arrays are declared like this:<br>
```csharp
[DataType][] [VariableName] = new [DataType][[ArraySize]];
```
Example:
```csharp
string[] carBrands = new string[10];
```
This array is of type _string_, it is declared as _carBrands_ and can hold _10_ elements/entries.<br>
This size cannot be changed just like that is kind of static.<br>

Now let's create us something useful.<br>


```csharp
string[] names = new string[10];
```

An array that can hold 10 names for us.<br>

For our project, we need to create this array at the top of our Main-Method, so we can use this array everywhere. Also, for our purpose, we need an indicator variable for which one is the next available entry.<br>
an array's indicator ranges from 0 - (array length - 1), keep that in mind.<br>

Soo. At the top of your main method should be something something like<br
```csharp
string[] names = new string[10];
int nextEntry = 0;
```










[Under Construction]





