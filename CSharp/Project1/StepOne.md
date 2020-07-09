# CSharp
---
### <a id="Title">Project 1</a>

Okay, let's get started with your project. :)<br>
First you need to [create a project](../Your-First-Project.md).<br>
Don't forget, console application, C#.<br>
For this purpose you could call it "Project1", because this project is just meant to get to know some things.<br>

---
#### <a id="Program">Your Program</a>

Once you've created your console app, you will see a Program.cs file in your project folder.<br>
That's the program-entrance of your program. Your program will always start in the pre-made "Main" method.<br>
And everything we will do for now, has to be within the curly bracket { } of the Main-method.<br>


---
#### <a id="Program">Variables</a>

If you have absolutely no idea what data types are, you can take a look at [this](../../General-Programming/Data-Types.md).<br>
Okay. Simply put, the way you create variables in C# is pretty much always the same.<br>

```csharp
[DataType] [VariableName] = [Value];
```
So for creating string variables you would do this:<br>
```csharp
string foo = "bar";
```
You can also only declare a variable, without giving it a value. But that causes problems if you try to get its value when it has none. But it can be used to create your set of variables in advance, useful in some situations :)<br>
```csharp
string foo;

foo = "bar";
```

You can **not** save values of one data type into a variable of another data type.<br>
```csharp
string foo = 1;
```


---
#### <a id="Program">Pre-made Methods</a>

Okay. You basically know how to create variables now. :) Perfect.<br>
What about we take a look at a few of those pre-made methods we were given by our framework and console-type of project.<br>

To introduce you into C# methods, I will explain how they basically work.<br>
Theoretically, every method has a return type. Just as a variable, a method can stand for something.<br>
We will take a look at something like that later :)<br>

How methods are created:
```csharp
[Scope] [ReturnType] [MethodName]([ParameterDataType] [ParameterValue])
{
  
}
```

Example:<br>
```csharp
public int SumTwoNumbers(int Num1, int Num2)
{
  int result = Num1 + Num2;
  return result;
}
```

Don't worry about the scope. For the beginning you can just always write the scope **public** when you create a method. :)<br>

But there's also one return-type which returns nothing. It is called *void*. You can use void-methods to just complete tasks for you, including algorithms or whatever you want.

```csharp
public void PrintSumOfTwoNumbers(int Num1, int Num2)
{
  int result = Num1 + Num2;
  Console.WriteLine(result);
}
```
The parameter at the method indicates, that you will have to provide two integers when calling the method.<br>
Now you basically understand how methods work. :)<br>


Soooo. One essential pre-given method is WriteLine(). You can access it over the Console class. :)<br>
It basically prints out whatever string you put into the parameters and then enters the next line. Leave an empty line will immediately enter the next line, leaving the line empty.<br>
In most code editors / IDEs you can hover over a written keyword / Method / etc. and it will tell you some information about it. It will be handy in the future. :)<br>

```csharp
Console.WriteLine("Hello World");
```
^ You can either enter the string directly into it or you can<br>

```csharp
string username = "Peter";
Console.WriteLine(username);
```
enter a string variable of your choice. :)<br>