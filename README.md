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
And they end at the next occurence of a */ | ? | ?
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
`System.Math` | ? | ? | new slide https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md
`static` | ? | ? | ?
`Math.Max` | ? | ? | ?
`Math.Min` | ? | ? | ?
`Math.Sqrt` | ? | ? | ?
`Math.Abs` | ? | ? | ?
`Math.Round` | ? | ? | ?
`Math.Floor` | ? | ? | ?
`Math.Ceiling` | ? | ? | ?
`Math.Clamp` | ? | ? | ?
`Math.Pow` | ? | ? | ?
`string.Length` | ? | ? | ?
`string.ToUpper` | ? | ? | ?
`string.+` | ? | ? | ?
`$"{}"` | ? | ? | ?
`string.[]` | ? | ? | ?
`string.IndexOf` | ? | ? | ?
`string.SubString(int)` | ? | ? | ?
`string.Substring(int, int)` | ? | ? | ?
`string.Replace` | ? | ? | ?
immutable | ? | ? | ?
Logical Operators | ? | ? | ?
`!` | ? | ? | ?
`&&` | ? | ? | ?
`||` | ? | ? | ?
Comparison Operators | ? | ? | ?
`>` | ? | ? | ?
`==` | ? | ? | ?
`!=` | ? | ? | ?
`||` | ? | ? | ?
`>=` | ? | ? | ?
`<=` | ? | ? | ?
`if` | ? | ? | ?
`else` | ? | ? | ?
`else if` | ? | ? | ?
`? :` | ? | ? | ?
Flow Control Statements | ? | ? | ?
`System.Random` | ? | ? | ?
pseudo-random | ? | ? | ?
seed | ? | ? | ?
`Random.Next(int, int)` | ? | ? | ?
`Random.Next()` | ? | ? | ?
`Random.NextDouble()` | ? | ? | ?
`Random.Next()` | ? | ? | ?
`while` | ? | ? | ?
bool-expression | ? | ? | ?
`do..while` | ? | ? | ?
`for` | ? | ? | ?
iteration statement | ? | ? | ?
loop body | ? | ? | ?
loop | ? | ? | ?
execution | ? | ? | ?
execution jump | ? | ? | ?
`break` | ? | ? | ?
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
