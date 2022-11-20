# Code Quality
[Why are programmers so Slow](https://www.youtube.com/watch?v=G6HyEeEcB-w&ab_channel=GiveyourBrainLimitlessSuperpowerLearningCode)      
[Best Practices for Writing Readable Code](https://code.tutsplus.com/tutorials/top-15-best-practices-for-writing-super-readable-code--net-8118)       
[Architectural Principles](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/architectural-principles)

## Importance of Quality
The quality of any code written in the real world is crucial to being able to reduce the number of bugs and to ensure that the software is going to be easy to extend and adapt in the future.  It is quite common where managers make deadlines too tight and code quality suffers, that the application becomes so fragile that it has to be completely re-written after a few years of modifications.
## Common Quality Issues
We have identified 34 common code quality issues (see xxx), and your tutor will record any issues found.  Your mark for Code Quality starts at 100% and is reduced by 5% for each issue found. .  If for example there are 5 methods without a block comment your mark will be reduced by 20% which is the maximum penalty for any one issue.
## Commenting Issues
![Naming](https://github.com/BNU-CO452/BlueJ-Apps/blob/master/images/Commenting.jpg)

There are two forms of commenting, in Java and C#, single line comments and block comments.
### Single Line Comments
These are not normally required, and you will not normally lose marks if you have no single line comments.  There are two possible exceptions where single line comments are required, and marks will be lost if those single line comments are not there
### Indicating units or the range of valid values.
~~~java
    // Distance measured in whole metres
    private int distance
~~~
### Unnecessary Comments
Comments that do not add any further information should not be added, for example:-
~~~java
    // Get the name
    public void GetName()
    {
        return name;
    }
~~~
Coders will waste valuable seconds reading the comment when the comment does not add to understanding.  No comments are required for methods with less than 3 lines of code.
### Block Comments
Block comments must be added to every class, and to every method that has 3 or more lines of code.  These comments can be extracted to produce API documentation which can be used by other people who wish to use that code.

See [C# API Documentation](https://dotnet.github.io/docfx/tutorial/docfx_getting_started.html)

## Naming Issues

![Naming](https://github.com/BNU-CO452/BlueJ-Apps/blob/master/images/Naming.jpg)

Selecting the right name for variables, methods and classes is the most important part of making a program readable, understandable and easy to maintain.  However Java is a case sensitive language, using case correctly is very important.  To summarise the C# naming convention:-

1. Class names always start with a capital letter, and must contain a noun.
2. Method names always start with a capital letter and must start with a verb.
3. Every other word in a name with multiple words must start with a capital letter.
4. Field/Attribute/variable/parameter names always start with a lower case letter.

[Microsoft Naming Conventions](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/general-naming-conventions)
## Layout Issues

![Layout](https://github.com/BNU-CO452/BlueJ-Apps/blob/master/images/Layout.jpg)

See [Best Practices for Writing Readable Code](https://code.tutsplus.com/tutorials/top-15-best-practices-for-writing-super-readable-code--net-8118)

Although a lot of sources suggest that an open brace { can be left at the end of a line with the close brace } is at the beginning of a new line, I find it is much easier to scan code if the open brace and close brace are aligned at the beginning of lines as shown below.  It also spaces the code out vertically.

SO PLEASE USE THE STYLE INDICATED BELOW FOR BRACES.
~~~c#
function DoFoo()
{
    if (someThingIsTrue)
    {
        DoItNow();
        DoItAgain();
    }
    else
    {
        AbortMission();
    }
    Finalise();
}
~~~
## Structural Issues
![Naming](https://github.com/BNU-CO452/BlueJ-Apps/blob/master/images/Structure.jpg)

see [Architectural Principles](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/architectural-principles)

In particular:-
1. Separation of Concerns
2. Encapsulation
3. Single Responsibility
4. Don't Repeat Yourself (DRY)

We also do not want **WET Solutions** where WET stands for:-

* We enjoy typing
* Waste everyone's time
* Write everything twice
 