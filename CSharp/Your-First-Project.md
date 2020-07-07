# CSharp
---
### <a id="Title">Your First Project</a>

Now we will get to creating your first project. :)<br>
I don't know with what intention you came here.<br>
But please listen to me when I tell you to learn C# with Console Applications.<br>
That's how it is recommended to do and you might one day see why...<br>
The approach is a little different depending on your OS: Windows / Mac / Linux<br>
Or to say it in another way, depending on your coding environment, Visual Studio Community / Visual Studio Code.<br>
So let's split this up a little...<br>

Oh, and to avoid any further confusion. When speaking of your application, it is basically the same as your project.<br>

## <a id="VS">Visual Studio Community (2019)</a>
---
#### <a id="ConsoleAppFramework">Creating a console application</a>

When opening Visual Studio Community (2019) you should something like:<br><br>
<img height="350px" width="auto" src="../Media/CSharp/VisualStudio2019StartMenu.png"><br><br>
If you would have recently-opened projects, you would see them on the left empty area.<br>
In order to create a project you simply have to click on "Create a new project"<br><br>
When doing so you should see something like this:<br><br>
<img height="450px" width="auto" src="../Media/CSharp/VisualStudio2019ProjectTypes.png"><br><br>
A bunch of project-types. Don't mind them. Just search for "console"  with the search bar and be sure of two facts.<br>
The "console app" you want has to have a green "C#" symbol on the icon & your console app should be ".NET Framework" for now.

Once you select those, you can choose a project name. <br>
Disclaimer!<br>
Do not put any special characters, umlauts or spaces in the name.<br>
You will learn on why later.<br>
The best you could do at the beginning is UsingPascalCaseByCapitalizingTheFirstLetterOfAWord<br>
Exmaples:<br>
FirstProject<br>
TestProject<br>
MyOwnDiscordBot<br>

After choosing the project name, you can see the path for the default-directory for all your projects.<br>
You can change it if you'd like.<br>
But I recommend not changing any other option you see there.<br>
Once you finish this, you're ready to work on your first project! :)<br>
Good luck!<br>

Also an important note already.<br>
When you want to save and work on your project at another time. Only ever open the .sln in your projects folder!<br>
Opening other files may only result in "crashes"/failing.<br>






## <a id="VSCode">Visual Studio Code</a>
---
#### <a id="ConsoleAppCore">Creating a console application</a>

Okay. There's two ways on how to begin to achieve the same thing.<br>
You can either go into VSCode directly and navigate to your desired project-folder or you create your project folder and open the folder with an option like "Open with... [XYZ] application".<br>

Disclaimer!<br>
Do not put any special characters, umlauts or spaces in the folder's name.<br>
You will learn on why later.<br>
The best you could do at the beginning is UsingPascalCaseByCapitalizingTheFirstLetterOfAWord<br>
Exmaples:<br>
FirstProject<br>
TestProject<br>
MyOwnDiscordBot<br>

Once you have your empty project folder opened in VSCode, open the VSCode Terminal.<br>
Inside of the terminal you type:<br>
```bash
dotnet new console
```

That creates a new console (.NET Core) application in your folder.<br>
You can now take a look at Program.cs and do whatever pleases you. :)<br>
In order to run the program, just use the VSCode terminal and type:<br>
```bash
dotnet run
```
Once you finish this, you're ready to work on your first project! :)<br>
Good luck!<br>
