Written by: [AlmightyLks](https://github.com/AlmightyLks)

# CSharp  
---  
### <a id="General">General</a>
If you already have experience with programming and you are a bit confused about some terminology, then you may want to take a look at [this](https://youtu.be/bEfBfBQq7EE), which explains everything very well.  
C# is a compiled language. That means, it will throw your human-readable code into a compiler and it will make a machine-readable executable (for example an .exe) out of it.  
For a deeper insight of how compilers work, again you may want to look into [this here](https://youtu.be/QXjU9qTsYCc). :)  
<br>
When working with C# you will create projects. Every program you make is a project.  
And furthermore you will always, at the very least, have 2 files:  
1 `.csproj` file, which describes your project details, such as version numbers of the language, the framework, the project type or libraries you use.  
And 1 `.cs` file. The csharp code file, where your code goes into. :)  
<br>
As soon as you `build`/`compile` your program/project, it will create two folders:  
1 `obj` folder necessary for compiling your program but only temporary and 1 `bin` folder, containing your binaries aka your .exe output.  


### <a id="Title">Setup</a>

Welcome to my first programming language-dedicated documentation. :)<br>
I will be going through the setup of a proper coding environment for either your <a href="#Win">Windows</a> or <a href="#Lin">Linux</a> machine. <br>
I do not have any experience with Mac OS at all but as to my knowledge, it is similar to the procedure of setting it up on Windows.<br>
Sooo let's get started! :)<br>

## <a id="Win">Windows</a>
---
#### <a id="IDE">Programming Environment | IDE</a>

Okay. First, you need your enviroment to program in. Your **I**ntegrated **D**evelopment **E**nvironment. <br>
What is so special about an IDE? It's a program to write programs. A pretty nice program.<br>
All you need for programming is integrated into that program for you. <br>
In example your code editor, a file explorer, your programming language's compiler, and so on...<br>

The creators of C#, Microsoft, also created a suiting IDE for it.<br>
Visual Studio (Community / Professional / Enterprise).<br>
Don't worry about the different types of that IDE.<br>
Community is free. You only need to login with a microsoft account within the first 30 days, after the first month of "testing" you're obligated to be logged in. But besides that it's free.<br>
Throughout my documentation I will be referencing to features and options within Visual Studio.<br>
You can get it [here](https://visualstudio.microsoft.com/downloads/).

While installing Visual Studio you will be prompted for the workloads about as shown here: <br>
<img width="1000em" height="auto" src="../Media/CSharp/Workloads.png">
<br>
<br>
All you need to select here is ".NET desktop development" and install that workload with Visual Studio.<br>
In future you can add other workload as well, but in order to learn C#, that's really all you need.<br>
<br>

When done, congratulations :) You've setup up your proper C#-Windows(/Mac) coding environment.<br>
Now you can begin with the programming language itself.<br>





## <a id="Lin">Linux</a>
---
#### <a id="IDE">Programming Environment | Code Editor</a>

In advance before installing this, you will have to install one thing.<br>
Just install the as "recommended" marked version for: <br>
[.NET Core](https://dotnet.microsoft.com/download/dotnet-core) ("SDK X.X.XXX")<br>
This thing is a so called Framework. Frameworks for programming languages are just special sets of given pre-made methods and just all kind of things.<br>
.NET Core -> To create Crossplatform Applications<br>

Unlike for Windows, Linux sadly has a limited support for C#. The IDE, Visual Studio, is unfortunately only available for Windows & Mac OS.<br>
Though through the on-going support for the .NET Core framework and the community, you can also program .NET Core Applications with various normal Code Editors.<br>
In my documentation I will be using either Visual Studio, which is unavailable for Linux, or [Visual Studio Code](https://code.visualstudio.com/), which is by the way also free, even without needing a connected microsoft account.<br>
It might seem similar to Visual Studio, but keep in mind. It has a reason why experienced people call Visual Studio Code "just a fancy code editor". :)<br>
It lacks some useful features which the IDE has.<br>
Anyways, it will be good enough for most of people's needs 

After installing Visual Studio Code you will have to install one more thing. The C# extension for VSCode. <br><br>
Simply click on the bottom-most icon on the left hand sidebar.<br>
<img width="150em" height="auto" src="../Media/CSharp/VisualStudioCode1.png"><br><br>
Search for the extension "C#" and install the one you see here:<br>
<img width="1000em" height="auto" src="../Media/CSharp/VisualStudioCode2.png"><br>


When done, congratulations :) You've setup up your C#-Linux coding environment.<br>
After restarting Visual Studio you can begin with the programming language itself.<br>
