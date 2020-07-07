# General-Programming
---
### <a id="Title">Advanced-Theory</a>

Okaaaay. You've found your way here. Here it will get a little more complicated and complex.<br>
Don't push yourself to understand this yet if you're not at that level.<br>
As a side note:<br>
The more advanced the topics get, the more I have to rely on my own experience and knowledge and so I will give examples by looking at C# here.<br>
Due to me only being a student and somewhat of a beginning-advanced myself, it might be pretty limited in general.<br>
But this documentation is **not** intended for highly experienced and advanced programmers anyways.<br>
Okay, let's get started. :)<br>
Another important note is that I will be using graphics presented in <a href="https://youtu.be/HlzAtIHFRk0" target="_blank">this</a> video. Never forget to give credits. :)

---
### <a id="Stack">Stack</a>

> * Variables allocated on the stack are stored directly to the memory and access to this memory is very fast, and its allocation is dealt with when the program is compiled

[C#]<br>
Stack.<br>
The part of the RAM that is easily accessable (fast to access) and basically used to store <a href="#ValueTypes">Value Types</a> and pointers from <a href="#ReferenceTypes">Reference Types</a>.

---
### <a id="Heap">Heap</a>

> * The heap is a memory used by programming languages to store global variables. By default, all global variable are stored in heap memory space.

[C#]<br>
Heap.<br>
The part of the RAM that is "less easy" to access (slow to access) and stores (by default) all and only <a href="#ReferenceTypes">Reference Type</a> global variables / object values.


Note: The use of each Stack & Heap differs from language to language. But the basic sense may stay the same.

---
### <a id="ValueTypes">Value Types</a>

> * A [data type](Data-types.md) is a value type if it holds a data value within its own memory space. It means the variables of these data types directly contain values.

Okay this might sound stupid. Of course something can only have a value if it holds its value. Or does it....?<br>
For this we need to look at the difference between Value Types and Reference Types.<br>
I will get to that after introducing you to both of them.

---
### <a id="ReferenceTypes">Reference Types</a>

* Unlike value types, a reference type doesn't store its value directly. Instead, it stores the address where the value is being stored. In other words, a reference type contains a pointer to another memory location that holds the data.

Reference types store the value at a certain spot in memory and store the accessor at another spot, pointing at this value-spot.




