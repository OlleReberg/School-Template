# CSharp Cheat Sheet Template

Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`;`     | Used to separate statements from each other.| `int i = 5; i++; Console.WriteLine(i);` | [Script Execution](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#0-script-execution)
`//`    | Used for single-line comments              | `float multiplier = 0.01f; // % to float (e.g. 24% = 0.24)` | [Comments](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#single-line-comments)
Variable Initialization | When a value is assigned to a variable for the first time | `int a = 5;` | [Variables](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-initialization)
`dotnet new console -o project-name` | How to start new C# project from command prompt | ? | ?
Script Execution Order | C# Code is executed from top to bottom.
Every statement in C# needs to be separated by a Semicolon ;
Empty statements are okay. | ? |https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md
Formatting |The language cares about whitespaces, tabs and newlines only as a way to separate words. Not about formatting | ? | ?
`Console.WriteLine` | Used to print out text when running program. "cw" can be used as a shortcut for it | ? | ?
`Console.Write` | If you don't want new line after output | ? | ?
Multi-Line Comment | Another useful tool for larger comments are multi-line comments.
They are started by using the /*
And they end at the next occurence of a */ (multiline comments)| ? | ?
XML Documentation Comment | // to comment, <summary>adds a neat summary</summary> can also use <param></param>| As an experienced programmer, you want to avoid spamming your code with unnecessary comment spam
As an inexperienced programmer, you just want to make sure to understand wth you doin| ?
Variable | Variables are used to store info. It allows us to assign value to something with a name of our choice | ? | ?
Variable Declaration | Variables are used to store data
Variables consist of a Type and a Name. (More on Types in the next Chapter)
This is, how you declare a variable: string strong | ? | ?
Variable Assignment | string strong = "strung"; | ? | ?
Uninitialized Variable | = sign used to initizalize stuff | ? | ?
`=` (Assignment Operator) | ? | ? | ?
Scope | {} is used to define scope of smth | ? | ?
Variable Scope | A variable is valid within its scope only, that is, between the previous { and the matching } | ? | ?
`int` | number | ? | ?
`float` | floating numbers! or really;  define numeric values with floating decimal points | ? | ?
`double` | not single :(, is more precise version of float and can store 64 bitz | ? | ?
`bool` | true or false: a bool is a true or false statement?| ? | ?
`char` | one single character ex. "|" | ? | ?
`string` | text n stuff | ? | ?
`byte` | means trade/change in english, in programming smth completely different tho(store small nr using hexadecimals. Represents data from binary or text)| ? | ?
Implicit Casting | int implicit;
implicit = 4.5; | Once given a value 4.5 the implicit version has the compiler convert what would normally be a float or double type to an integer whereas..  | ?
Explicit Casting | int explicit;
explicit = (int)4.5; | ..the explicit version has explicitly cast it to an integer with the use of (int) being what casts the type.| ?
Type Conversion | Convet.To |  Some need to be converted. Conversions are validated and will throw exceptions. If invalid, e.g is the string is "Tom". | ?
`Convert.ToInt32` | converts string to int | don't forget about decimals with swedish keyboard( 
, vs .) | Conversions are often necessary while computing.
For example Console Input string needs to be converted to a number
Or an integer needs to be converted to a float to do division with decimals
There‘s a variety of ways of doing that, you should always choose the easiest path that‘s available for your conversion
Operators | Operators are functions represented by symbols
They execute operations and return a result
The result can be assigned to a variable, or used directly | ? | ?
Arithmetic Operators | Arithmetic operators are used for mathematical operations
They take two numbers as input and return a number as output | int div = 9 / 3; | ?
`+` | addition | ? | ?
`-` | subtraction | ? | ?
`*` | multiplication | ? | ?
`/` | division | ? | ?
`%` | remainder | ? | ?
`+=` | add to already defined variable, i.e. instead of int no = 5; int no = no + 3; -> int no += 3; | ? | ?
`-=` | same but subtraction | ? | ?
`++` | +1 | ? | ?
`--` | -1 | ? | ?
Post-Increment `i++` | Depending if ++ used before or after variable(i.e. ++i vs i++), the i+1 will happen before or after CW | ? | ?
Pre-Increment `++i` | ? | ? | ?
`System.Math` | System.Math is a static class containing many useful functions for numbers | ? | new slide https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md
`static` | Static means, it can not be instantiated, you can not write Math math = new Math(); | ? | ?
`Math.Max` | Returns the higher number of two | ? | ?
`Math.Min` | Returns lower number. These can be used to determine minimum/maximum number and prevent user from going over/under | ? | ?
`Math.Sqrt` | Double Sqrt(double) returns square root | ? | ?
`Math.Abs` | Most muscular math, also: double Abs(double) returns the absolute of a number, which is always positive. Useful for calculating distances.  | ? | ?
`Math.Round` | Double Round(double) returns the rounded value of a number (closest integer) | ? | ?
`Math.Floor` | Double Floor(double) returns the value of the number rounded to the lower integer | ? | ?
`Math.Ceiling` | Raising the ceiling...and returns value rounded to higher integer | ? | ?
`Math.Clamp` | CLAMPS!!! Also clamps value to not go over/under paramaters set | ? | ?
`Math.Pow` | POWERRRRRR! Also; double Pow(double value, double power) returns the value to the power of power | ? | ?
`string.Length` | Returns the length of a string | ? | ?
`string.ToUpper` | make string all uppercase or all lowercase(useful for removing case sensitivity in input) | ? | ?
`string.+` | Allows to extend text: i.e. "bleebloob" + "blooblaab" | ? | ?
`$"{}"` | interpolation, i.e. lets us use the sweet curlies in text: {} | ? | ?
`string.[]` | return character at any index of a string | ? | ?
`string.IndexOf` | You can also get the index of the first occurance of a character or string. Again, counting starts at 0 | ? | ?
`string.SubString(int)` | You can get a sub-part of a string starting at a certain index (1) until the end of the string | ? | ?
`string.Substring(int, int)` | You can get a sub-part of a string starting at a certain index (1) with a certain length (2) | ? | ?
`string.Replace` | You can replace all occurances of a character or string with another one | ? | ?
immutable | Strings are immutable
That means: A string can never be changed.
So, when you call a function on a variable, it never changes the variable itself.
Instead, it returns a new string that you can or need to assign to the same, or a new variable | string fullName = "John Kane";
fullName.Replace('n', 'd');
Console.WriteLine(fullName); - John Kane vs string fullName = "John Kane";
fullName = fullName.Replace('n', 'd');
Console.WriteLine(fullName); - Johd Kade | ?
Logical Operators | A logical operator is a symbol or word used to connect two or more expressions such that the value of the compound expression produced depends only on that of the original expressions and on the meaning of the operator. Common logical operators include AND(&&), OR(||), and NOT(!). | don't forget that variable may need to be called again after operators been used. | ?
`!` | NOT | ? | ?
`&&` | AND? | ? | ?
`||` | OOOOOR... | ? | ?
Comparison Operators | Comparision operators can compare two values and return a bool (true or false) | ? | ?
`>` | Grater than or < Lass than | ? | ?
`==` | Equals | ? | ?
`!=` | Not equals | ? | ?
`||` | Our | ? | ?
`>=` | Grater than or Eqal too | ? | ?
`<=` | Smoler thon or Eqal too | ? | ?
`if` | if only | ? | ?
`else` | gimme me monay or else | ? | ?
`else if` | extension of if but not end of if statement | ? | ?
`? :` | ???????? used in ternary if-operator, i.e. shortcut | string greeting = condition ? then-value : else-value;
string greeting = condition ? true-value : false-value; | ? | ?
`System.Random` | Allows us to generate random numbers | ? | ?
pseudo-random | The numbers are pseudo-random: they are using complex mathematical operations to make them appear random*
They are guaranteed to be evenly ditributed across all numbers| ? | ?
seed | You use a seed to determine, which sequence of numbers you want to have That‘s a feature: we can reproduce the same random numbers if we know the seed. | ? | ?
`Random.Next(int, int)` | int Next(int min, int max) receives a new random integer between 0 (inclusive) and 5 (exclusive), so either 0, 1, 2, 3 or 4 | ? | ?
`int Next()` | int Next() gets a random integer between 0 and int.MaxValue (1.2 bln) | ? | ?
`double NextDouble()` | double NextDouble() Receive a new randomNumber between 0 (inclusive) and 1 (exclusive), so anything between 0.000000 and 0.9999999 | ? | ?
`Random.Next()` | kinda random, no? | ? | ?
`while` | You can use the while-keyword in combination with a bool-expression to form
a loop that repeats as long as the bool-expression returns true | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.3-console-basics-3.md
bool-expression | while(condition-expression) | { // while-scope-start
  // put the code here, that you want to repeat while the bool-expression is true
} // while-scope-end | ?
`do..while` |do..while-loops are very similar to while-loops
but while while-loops first check the condition and then execute the code...do..while-loops first execute the code and then check the condition
Therefore, the code in the loop is guaranteed to execute AT LEAST once! | while while while while. In essence, its all about the order of checks | ?
`for` | Very often in programming, we encounter the situation, where we want to use a loop to iterate with the same routine multiple times: Enter FOR LOOOOOOOOP! | ? | https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md
iteration statement | An Iteration is just a fancy word for a loop. An Iteration statement will perform operations a set number of times until you tell it to stop, with a true or false value. Iteration statements also depend on an expression being evaluated until a that expression evaluates to false. This is called “loop termination criteria” and depends on Boolean values being evaluated. | ? | ?
loop body | What runs if condition statement is met | ? | ?
loop | loop goes in a loop goes in a loop goes in a loop goes in a loop goes in a loop goes in a loop goes in a loop | ? | ?
execution | Not THAT kind of execution...it's just executing code | ? | ?
execution jump | Execution jumps back to the condition each time | ? | ?
`break` | Time to break the break by taking a short break! | ? | ?
`continue` | ? | ? | ?
`Array` | ? | ? | ?
`int[]` | ? | ? | ?
Array Initialization | ? | ? | ?
Array Access for Assignment | ? | ? | ?
Array Access for Reading | ? | ? | ?
`Array.Resize` | ? | ? | ?
`Array.Length` | ? | ? | ?
`foreach` | ? | ? | ?
`2D-Array` | ? | ? | ?
2D-Array Initialization | ? | ? | ?
2D-Array Access for Assignment | ? | ? | ?
2D-Array Access for Reading | ? | ? | ?
Jagged Arrays | ? | ? | ?
Method | ? | ? | ?
`void` | ? | ? | ?
Return Type | ? | ? | ?
`()` | ? | ? | ?
Parameter | ? | ? | ?
Argument | ? | ? | ?
Parameter | ? | ? | ?
Parameter-List | ? | ? | ?
Named Arguments | ? | ? | ?
Optional Arguments | ? | ? | ?
Default Value | ? | ? | ?
`return` | ? | ? | ?
Code Paths | ? | ? | ?
Method Overloading | ? | ? | ?
Object-Oriented Programming | ? | ? | ?
Data | ? | ? | ?
Function | ? | ? | ?
Structured Programming | ? | ? | ?
Objects | ? | ? | ?
Instance Method | ? | ? | ?
Class | ? | ? | ?
Type | ? | ? | ?
`class` | ? | ? | ?
`new` | ? | ? | ?
Class Member | ? | ? | ?
Class Instance | ? | ? | ?
Garbage Collector | ? | ? | ?
`null` | ? | ? | ?
Invoke | ? | ? | ?
Field | ? | ? | ?
Static Class Member | ? | ? | ?
Static Class | ? | ? | ?
Global Access | ? | ? | ?
Constructor | ? | ? | ?
Initial Class Values | ? | ? | ?
Parameterless | ? | ? | ?
Default Contructor | ? | ? | ?
Finalizer | ? | ? | ?
Object Destruction | ? | ? | ?
`GC.Collect` | ? | ? | ?
Encapsulation | ? | ? | ?
Access Modifier | ? | ? | ?
`private` | ? | ? | ?
`protected` | ? | ? | ?
`public` | ? | ? | ?
`internal` | ? | ? | ?
Class Member Access | ? | ? | ?
Inheritance | ? | ? | ?
Property | ? | ? | ?
Getter Method | ? | ? | ?
Setter Method | ? | ? | ?
Validation | ? | ? | ?
Processing | ? | ? | ?
`get` | ? | ? | ?
`set` | ? | ? | ?
Expression Body Syntax | ? | ? | ?
Auto Property | ? | ? | ?
Read-Only Property | ? | ? | ?
Auto Property | ? | ? | ?
base-Class | ? | ? | ?
Inherit From | ? | ? | ?
Derived Class | ? | ? | ?
Child Class | ? | ? | ?
Parent Class | ? | ? | ?
`sealed` | ? | ? | ?
Polymorphism | ? | ? | ?
`as` | ? | ? | ?
`virtual` | ? | ? | ?
`override` | ? | ? | ?
`base` | ? | ? | ?
Abstraction | ? | ? | ?
`abstract` | ? | ? | ?
Implementation | ? | ? | ?
Composition | ? | ? | ?
"Composition over Inheritance" | ? | ? | ?
"Parse / Parsing" | converting text / strings to another type | Also; Extracting information from text. | ?
