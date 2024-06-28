# Coding Journal
## Name: Laina 
## Module 1
## May 28 2024
### 1.1 Programming (general)
Computer program basics  
  A computer **program** consists of instructions executing one at a time. Basic instruction types are:  
 **Input**: A program gets data, perhaps from a file, keyboard, touchscreen, network, etc.  
 **Process**: A program performs computations on that data, such as adding two values like x + y.  
 **Output**: A program puts that data somewhere, such as to a file, screen, network, etc.   
 Programs use **variables** to refer to data, like x, y, and x.   

Computational thinking  
 **computation thinking** - creating a sequence of instructions to solve a problem.  
 **algorithm** - a sequence of instructions that solves a problem.   

### 1.2 Programming basics
A simple Java program  
  A **program** starts in main(), executing statements within main's braces {}, one at a time.  
  Each statement typically appears alone on a line and ends with a **semicolon**, as English sentences end with a period.  
  The _int wage_ statement creates an integrar variable named wage. The _wage = 20_ statement assigns wage with 20 and holds that value.   
  The print and println statements output various values.  

Basic input  
  A **scanner** is a text parser that can get numbers, words, or phrases from an input source such as the keyboard.  
  _Scanner scnr = new Scanner(System.in);_  
  _x = scnr.nextInt()_  

Basic output: Text  
 The **System.out.print** construct supports output. Outputting text is achieved via: _System.out.print("desired text");_ Text in double quotes " " is known as a **string literal**. Multiple output statements continue printing on the same output line.  
 **System.out.println** (not the ln at the end, short for "line"), starts a new output line after the outputted values, called a **newline**.   

Outputting a variable's value  
 Outputting a variable's value is achieved via: _System.out.print(x);_. _println()_ could also be used.  

Outputting multiple items with one statement  
 Programmars commonly use a single output statement for each line of output by combining the outputting of text, variable values, and a new line. This is down by serperates the items with a _+_ sybmol.   

### 1.3 Comments and whitespace
Comments  
 A **comment** is text a programmer adds to code, to be read by humans to better understand the code but ignored by the compiler. Two common kinds of comments exist:  
 A **single-line comment** starts with // and includes all the following text on that line. Single-line comments commonly appear after a statement on the same line.   
 A **multi-line comment** starts with /* and ends with */, where all text between /* and */ is part of the comment. A multi-line comment is also known as a **block comment**.   

Whitespace  
 **Whitespace** refers to blank spaces (space and tab characters) between items within a statement and blank lines between statements (called newlines).  
 Good practice is to deliberatly and consistently use whitespace to make a program more readbale. Examples:  
  Use blank lines to separate conceptually distinct statements.  
  Indent lines the same amount.  
  Align items to reduce visual clutter.  
  Use a single space before and after any operators  

### 1.4 Why whitespace matters
Whitespace and precise formatting  
 For program output, **whitespace** is any blank space or newline.   

 Programming is all about precision  

### 1.5 Errors and Warnings
Syntax errors  
 **Syntax error** is to violate a programming language's rules on how symbols can be combined to create a program.   

Unclear error messages  
 Compilor error messages are often unclear or even misleading. The message is like the compiler's "best guess
 of what is really wrong.  

Fixing the first error
Good practice is to focus on fixing just the first error reported by the compiler and then recompiling.

Logic errors   
A syntax error is known as a type of **compile-time error**.  
A **logic error**, also called a **bug**, is an error that occurs while a program runs.   

Compiling frequently  
Good practice, especially for new programmers, is to compile after writing only a few lines of code, rather than writing tens of lines and then compiling.     

Compiler warnings  
A compiler will sometimes report a **warning**. which doesn't stop the compiler from creating an executable program but indicuates a possible logic error.   

### 1.6 Computeres and programs (general)
Switches  
When people in the 1800s began using electricity for lights and machines, they created switches to turn objects on and off. A _switch_ controls whether or not electricity flows through a wire.   
0s and 2s are known as **bits** (binary digits). They build connections of switches, known as _circuits_, to perform calculations such as multiply two numbers.   

Processors and memory  
To support different calculations, circuits called **processors** were created to process (aka _execute_) a list of desired calculations, with each calculation called an **instruction**.   
Instructions are stored in a memory. A **memory** is a circuit that can store 0s and 1s in each of a series of thousands of addressed locations.  

Instructions  
The programmer-created sequences of instructions is called a **program**, **application**, or just **app**.   
A processor executes instructions like Add 200, #9, 201, represented as 0s and 1s.   

Writing computer programs    
Instructions represented as 0s and 1s are known as **machine instructions**, and a sequence of machine instructions together form an **executable program** (sometimes just called an _executable_).   
Because 0s and 1s are hard to comprehend, programmers created programs called _assemblers_ to automatically translate human readable instructions, such as "Mul 97, #9, 98", known as **assembly** language instructions, into machine instructions.   
Programs created **high-level languages** to suport programming using formulas or algorithims, so a programmer could write a formula like: _F = (9 / 5) * C + 32_. Early high-level languages included _FORTRAN_ (for "Formula Translator") or _ALGOL_ (for "Algorithmic Langauge").   
To support high-level languages, programmers created **compilers**, which are programs that automatically translate high-level language programs into executable programs.  
**Bytecode** an executable that involves having the compiler generate an executable using machine instructions of a "virtual" processor in order to run on different processor types.   
**Virtual machine** the program that the real processor runs.  

### 1.7 Computer tour
The term _computer_ has changed meaning over the years. In the early days of computing the physical equipment was prone to failures. As equipment became more stable and as programs became larger, the term _software_ became popular to distinguish a computer's progams from the _hardware_ on which they ran.  
A computer typically consists of several components:
  **Input/output devices**: A **screen** displys items to a user. A **keyboard** allows a user to provide input to the computer, typically accompanied by a _mouse_.  
  **Storage**: A **disk** (aka _hard drive) stores files and other data. Disks are _non-volatile_, meaning they maintain their contents even when powered off.  
  **Memory**: **RAM** (random-access memory) temporarily holds data read from storage and is designed such that any address can be accessed much faster than disk. Memory size is typically listed in bits or in bytes, where a **byte** is 8 mits.   
  **Processor**: The **processor** runs the computer's programs, reading and executing instructions from memory. _BIOS_ - (basic input/output system). The **operating system** allows a user to run other programs and interfaes with the many other peripherals. Processors are also called _CPUs_ (central processing units) or _microprocessors_. **Cache** memory - a small amount of ram on a processor's chip accessible in one clock tick.   
  **Clock**: A processor's instructions execute at a rate governed by the processor's **clock**, which ticks at a specific frequency.   

After computers were invented and occupied entire rooms, engineers created smaller switches **transistors**, which in 1958 were integrated onto a single chip called an **integrated circuit** or IC. Engineers continued to make transistors smaller, leading to **Moore's Law**: the doubling of IC capacity roughly every 18 months, which continued for several decades.   

### 1.8 Language history

In 1978, Brian Kernighan and Dennis Ritchie at AT&T Bell Labs published a book describing a new high-level langauge with the simple name **C**, being named after another language called B. C became the dominant programming language in the 1980s and 1990s.    
In 1985, Bjarne Stroustrup published a book describing a C-based langauge called **C++**, adding constructs to support a style of programming known as _object-oriented programming_, along with other improvements.   
In 1991, James Gosling and a time of engineers at Sun Microsystems (aquired by Oracle in 2010) began developing the **Java** language with the intent of creating a language whose executable could be ported to different processors, with the first public release in 1995.   
Java was initially intended to be run on consumer appliances like interactive TVs. Java should not be confused with JavaScript, which is an entirely different langauge used for developing web applications that was named similarly.   

### 1.9 Problem Solving
Programming langauges vs. problem solving  
Programming is largely about **problem solving**: creating a methodical solution to a given task.   
        
Precision, logic, and computational thinking  
**Computational thinking** - the thought processes needed to build correct, precise, logical programs

### 1.10 Why programming
Computing careers  

## Module 1 Lecture Video What is Computer Science?
So what is Computer Science (CS), anyway?  

Computers are a powerful automation tool, but we need to tell them what to do...  
  How can we communicate with them to take advantage of this power?  
  How do we break down out problems so that they can be automatically solved by computers?
  How can we organize our solutions so that others can take advantave of them? (and so we don't always need to reinvent the wheel either).  

What is a computer?  
  A computer is driven by **code**   
  Code is made of simple, mechancial instructions   
  Computers only understand 1s and 0s, so we use **high-level programming languages** that we can understand and **compile** (or translate) them into something the machine can understand.   

Program Development in Java  
There are many high-level computer programming langauges.  
    Java, C/C++, C#, Pything, JavaScript, etc.  
So why Java?  
    Concepts you learn can be applied to other programming languages.   
    One of the world's most popular programming languages.  
    At the core of many applications you use every day.  

First Program - Hello World!  
Break it down.  
  javadoc comment
  Class header  
  Class body  
    Method header (like a function)   
      Method body  
        inline comment  
        method call (action)   
          parameter (argument)
  Whitespace   

Compile and Execute  
  source code file  
  compile  
  bytecode file   
  execute  
  JRE (Java Runtime Environment)  

Syntax and Semantics  
Every language has its own set of **syntax rules** and **semantics**.  
  Syntax - Grammer. The rules for what kinds of words/symbols you can put together and in what order.  
  Semantics - Meaning of the statement.  

Errors and Feedback  
There are 3 major types of errors  
- **Compile-time**. Incorrect syntax or other basic problems.  
- Spelling errors, unmatched braces/parenthesis, etc.   
- **Run-time**. A problem during program execution that causes it to terminate abnormally.  
- Divide by zero, main class not found, etc.   
- **Logical**. The program runs but produces the incorrect results.   
- Using the wrong formula, producing the wrong output, etc.  

### Module 1 Lab
- Run javac fileName.java in java to compile

## Module 2
### 2.1 Variables and assignments (general)

Variables and assignments  
- In a program, a **variable** is a named item, such as x or numPeople, used to hold a value.  
- An **assignment** assigns a variable with a value, such as x = 5.  
- As assignment's left side must be a variable. The right side can be an expression.  

= is not equals  
- In programs, = is an assignment of a left-side variable with a right-side value.

### 2.2 Variables (int)
Variable declarations  
- A **variable declaration** is a statement that declares a new variable, specifying the variable's name and type. Ex: _int userAge;_, declares a new variable named userAge that can hold an integer value.
- **Allocation** is the process of determining a suitable memory location to store data like variables.

Assignment statements
- An **assignment statement** assigns the variable on the left-side of the = with the current value of the right-side expression. Ex: _numApples = 8;_.
- An **expression** may be a number like 80, a variable name like numApples, or a simple calculation like numApples +1. An integer like 80 appearing in an expression is known as an **integral literal**.

Initializing variables  
- Although not required, an integer variable is often assigned an initial value when declared. Ex: _int maxScore = 100;_ declares an int variable named maxSCore with an inital value of 100.

Assignment statement with same variable on both sides  
- Commonly, a variable appears on both the right and left side of the = operator. Ex: If numItems is 5, after _numItems = numItems + 1;_ executes, numItems with be 6.

Common errors
- A common error is to read a variable that has not yet been assigned a value.
- A common error by new programs is to write an assignment statement in reverse.

### 2.3 Identifiers
Rules for identifiers  
- A name greated by a programmer for an item like a variable or method is called an **identifier**. An identifer must:
- be a sequence of letters (a-z, A-Z), underscore (_), dollar signs ($), and digits (0,9)
- start with a letter, underscore, or dollar sign
- A good practice followed by many Java programmers is to not use _ of $ in programmer-created identifiers.
- Identifiers are **case sensitive**, meaning upper and lower case letters differ.
- A **reserved word** is a word that is part of the language, like int, short, or double. A reserved word is also known as a **keyword**. A programmer cannot use a reserved word as an identifier.

Style guideines for identifiers  
- While various (crazy-looking) identifiers may be vaild, programmers may follow identifier naming conventions (style) defined by their comany, team, teacher, etc. Two common conventions for naming variables are:
- Camel case: **Lower camel case** abuts multiple words, capitalizing each word except the first, as in numApples or peopleOnBus.
- Underscore seperated: Words are lowercase and seperated by an underscore, as in num_apples or people_on_bus.
- Good practice is to create meaningful identifer names that self-describe an item's purpose. Good practice minimizes use of abbreviations in identifers except for well-known ones like num in numPassenders.

### 2.4 Arithmetic expressions (general)
Basics  
- An **expression** is any individual item or combination of items, like variables, literals, operators, and parentheses, that evaluates to a value, like _2 * (x + 1)_. A common place where expressions are used is on the right side of an assignment statement, as in _y = 2 * (x + 1)_.
- A **literal** is a specific value in code like 2. An **operator** is a symbol that performs a built-in calculation, like +, which performs addition.

Evaluations of expressions  
- An expression evalutes to a value, which replaces the expression. Ex: If x is 5, then x + 1 evaluates to 6, and y = x + 1 assigns y with 6.
- An expression is evaluated using the order of standard mathematics, such order known in programming as **precedence rules**.
- Use parentheses to make the order of evaluation explicit.

## 2.5 Arithmetic expressions (int)  
Style: Single place around operators  
- A good practice is to include a single space around operators for readability, as in numItems + 2, rather than numItems+2. An exception is minus used as negative, as in xCoord = -yCoord. Minus (-) used as negative is known an **unary minus**

Compound operators  
- Special operators called **compound operators** provide a shorthand way to update a varibale, such as userAge **+=** 1 being shorthand for userAge = userAge +1. Other compound operators include **-=**, ***=**, **/=**, and **%=**.

No commas allowed  
- Commas are not allowed in a integrer literal.  

### 2.7 Floating-point numbers (double)
Floating-point (double) variables  
- A **floating-point number** is a real number containing a decimal point that can appear anywhere (or "float") in the number. A **double** variable stores a floating-point number. Ex: _double milesTravel;_ declares a double variable.
- A **floating-point literal** is a number with a fractional part, even if the fraction is 0, as in 1.0, 0.0, or 99.573. Good practice is to always have a digit before the decimal point, as in 0.5, since .5 might mistakenly be viewed as 5.
- Scanner's nextDouble() method read a floating-point value from input. Ex: _currentTemp = sncr.nextDouble();_ reads a floating-point value from the input and assigns currentTemp with that value.

Choosing a variable type (double vs. int)  
- A programmer should choose a varible's type based on the type of value held.
- Integer variables are typically used for values that are counted, like 42 cars, 10 pizzes, or -95 days.
- Floating-point variables are typically used for measurements, like 98.6 degrees, 0.00001 meters, or -55.667 degrees.
- Floating-point variables are also used when dealing with fractions of countable items, such as the average number of cars per household.

Floating-point division by zero  
- Dividing a nonzero floating-point number by zero is undefined in regular arithmetic. Many programming languages produce an error when performing floating-point division by 0, but Java does not. Java handles this operation by producing infinity or -infinity, depending on the sign of the operands. Printing a floating-point variable that holds infinity or -infinity outputs _Infinity_ or _-Infinity_.
- If the dividend and divisor in floating-point division are both 0, the division results in a "not a number." **Not a number (NaN)** indicates an unrepresentable or undefined value. Printing a floating-point variable that is not a number outputs _NaN_.

Manipulating floating-point output  
- Some floating-point numbers have many digits after the decimal point. By default, most programming languages output at least 5 digits after the decimal point. A common approach is to output floating-point numbers with a specific number of digits after the decimal to reduce complexity or produce a certain numberical type. The syntax for outputting the double myFloat with two digits after the decimal point is _System.out.printf("%.2f", myFloat);_.

### 2.9 Constant variables  
- A good practice is to minimize the use of literal numbers in code. One reason is to improve code readability. When a variable represents a literal, the variable's value should not be changed in the code. If the programmar precedes the variable declaration with the keyword final, then the compiler will report an error if a later statement tries to change that variable's value. An initialized variable whose value cannot be changed is called a **constant variable**. A constant variable is also known as a **final variable**. A common convention or practice, is to name constant variables using upper case letters with words seperated by underscores, to make constant variables clearly visible in code.  

##3 2.10 Integer divison and modulo  
Division: Integer rounding  
- When the operands of / are integrers, the operator performs integer dicison, which does not generate any fraction.
- The / operator performs floating-point division if at least one operand is a floating-point type.

Division: Divide by 0  
- For integer division, the second operand of / or % must never by 0, because division by 0 is mathematically undefined. A **divide-by-zero error** occurs at runtime is a divisor is 0, causing a program to terminate. A divide by zero error is an example of a **runtime error**, a severe error that occurs at runtime and causes a program to terminate early.

Modulo (%)  
- The basic arithmetic operators include not just +, -, *, /, but also %. The **modulo operator (%)** evaluates the remainder of the division of two integer operands.

### 2.11 Type Conversions
Type Conversions  
- A **type conversion** is a conversion of one data type to another, such as an int to a double. The compiler automatically performs several common conversions between int and double types, such automatic conversions are known as **implicit conversion**.

Type casting
- A **type cast** explicity converts a value of one type to another type.
- A programmar can precede an expression with (_type_) to convert the expression's value to the indicated type. Ex: If myIntVar is 7, then _(double)myIntVar_ converts int 7 to double 7.0.

Common errors
- A common error is to accidentally perform integer division when floating-point division was intended.

### 2.13 Characters  
Basics  
- A variable of **char** type, as in _char myChar;_, can store a single character like the letter m. A **character literal** is surrounded with single quotes, as in _myChar = 'm';_.

Getting a character from input  
- Java does not have a method for getting one character from input. Instead the following sequence can be used: _myChar = scnr.next().charAt(0);_ The charAt(0) is explained in another section. Briefly, next() gets the next sequence of non-whitespace characters (as a string) and charAt(0) gets the first character in that string.

A character is internally stored as a number  
- A char variable stores a number. In an output statement, the compiler outputs the number's corresponding character.
- **ASCII** is an early standard for encoding characters as numbers. Java uses a more recent standard called Unicode.

Escape sequences  
- In addition to regular characters like Z,$, or 5, character encoding includes numbers for several special characters. Ex: a newline character is encoded as 10. Because no visible character exists for a newline, the language uses an **escape sequence**. A two-character seqience starting with \ that represents a special character.

Outputting multiple character variables with one output statement  
- A programmer can output multiple character variables with one statement as follows: _System.out.print(" " c1 + c2);_. The initial "" tells the compiler to output a string of characters, and the +'s combine the subsequent characters into such a string.

Common errors  
- A common error is to use double quotes rather than single quotes around a character literal, as in _myChar = "x"_, yielding a compiler error.
- Similarly, a common error is to forget the quotes around a character literal, as in _myChar = x_, usually yielding a compiler error (unless x is also a declared variable, then perhaps yielding a logic error).

### Module 2 - Data and Expressions - Strings Lecture Video
String literals  
- A sequence of characters surrounded by double quotes.
- Strings are objects in java. More about this later.

Printing Strings  
- System.out.println("A String"); // Prints a newline after the string.
- System.out.print("A string"); // Doesn't print a newline after the string.
- System.out represents the cestination of the print output - the console.
- print and println are methods (or operations) of System.out.

String Concatenation  
- We can concatenate (link together in a chain) two strings using the + operator.
- 3 concatenated strings: "peanut butter" + " " + "and jelly"
- Produce one new string: "peanut butter and jelly"
- Allows strings to be broken across multiple lines.
- "If this was a long string, we may want it on " +
- "two lines so that we can see it more easily"

Concatenating Numbers  
- We can concatenate numbers to strings.
- 3 concatenated values: "My dog is " + 5 + " years old"
- Produces one new string: "My dog is 5 years old"
- What if we concatenate two numbers?
- 4 concatenated values: "My dog is " + 5 + 3 + " years old"
- Procudes one new string: "My dog is 53 years old"

Escape Sequences  
- What if we want to include " in a string?
- System.out.println("I said "Hello" to you");
- We get a compile-time error. Where does the string end?
- Escape sequences allow us to include special characters in our strings.
- Begin with a backslash (\) character.
- System.out.println("I said \"Hello"\ to you");

Common Escape Sequences
- \" double-quote
- \t tab
- \n newline
- \\ backslash

### Module 2 - Data and Expressions - Variables Lecture Video
What is a variable?  
- Most (if not all) of our programs manage data.
- The data must be stored somewhere in the computer's memory.
- Memory is made up of a bunch of slots that can store data.
- To find the correct data, we must know which slot (or address) it is stored in.
- Instead of memorizing all of the specific addresses, we give each slot a meaningful name - a variable.

Properties of Variables
- Every variable has a name and value that it refers to.
- The value of a variable can change.
- Every variable has a type. Once created, a variable can only store data of the type it was created for. (or data that is compatable with the type).

Declaring Variables
- In Java, every variable must have a type, a name, and a value.
- String quote = "Don't quit.";
- The assignment operators (=) sets the value of the variable.
- We can set the value of a variable after we declare it.
- String quote;
- quote = "Don't quit";
- If no value is set, the variable will have a default value (which depends on the type).
- String myName; //Value is null
- We can declate multiple variables of the same type on a single line.
- String myName, yourName;
- myName = "Me";
- yourName = "You";

Changing Variables  
- Variables always store the last value that was assigned to them.
- String quote = "Don't quit.";
- quote = "Always persevere.";
- What is the value of quote?
- Variables can only store data of the types they are compatible with.
- quote = 1000; // Not allowed.

Variable Names  
- In Java, variable names
- must be unique,
- can only consist of a combination of letters, numbers, _, and $, 
- can not begin with a number,
- are case sensitive,
- should use camelCase style for longer variable names.

What is a constant?
- Constats are identifiers (similar to variables) that hold the same value for the duration of their existence.
- Used to store values that should never change.
- If you try to change the value, there will be a compile-time error.
- Prevents you from accidentally changing a value that should be constant.

Declaring a Constant  
- In Java, every constant must have a type, a name, and a value.
- The final modifier is what makes it constant.
- final String Default_Quote = "Hello World";
- You must initialize a constant once and only once.

### Module 2 - Data and Expressions - Primitive Data Types Lecture
Primitive Data Types  
- There are 8 primitive data types in Java.
- Numbers
- byte, short, int, long
- float, double
- Characters
- char
- Boolean values
- boolean

Numbers  
- Whole Numbers
- byte (-128 to 127)
- short (approx -32 thousand to 32 thousand)
- int (approx -2 billion to 2 billion_
- long (approx -9 quintillion to 9 quintillion)
- Floating Point Numbers
- float (6-9 significant digits)
- double (15-17 significant digits)

Number Variables
- We will primarily use int and double.
- int numStudents = 10;
- final int SECOND_PER_MIN = 60;
- double tax = 0.06;
- final double PI = 3.14159;

Characters  
- char
- Stores a single symbol.
- 'a' '9' '\n' 'x'
- Can store a symbol from the Unicode character set
- English speakers typically use characters from the ASCII character set (A smaller subset of Unicode).
- To print a special character, use the **\u** escape sequence followed by the code.
- char smiley = '\u263A'; // :)

Booleans
- boolean
- Only two valid values for the boolean type.
- Reserved words: true and false
- Commonly used to represent two states (e.g. on/off)
- boolean isDone = false;
- boolean tooSmall, hasFur, canTalk;

### Module 2 - Data and Expressions - Expressions (Part 1) Lecture
Expressions  

Arithmetic Expressions  
- You should be familiar with most of the operators.
- +, -, *, /
- We are going to add one more - the modulo or remainder, operator.
- %

Mathematical Expressions
- To start, we will focus on integrers, not floating points.
- We know volume of a rectangular prism is equal to length x width x height.
- int length = 10;
- int width = 5;
- int height = 15;
- int volume = length * width * height = 750
- Right-hand side evaulated first

- To split a package of cookies amoung freinds, we use the equation" # cookies / n.
- int numCookies = 12;
- int numFriends = 6;
- int cookiesPerFriend = numCookies / numFriends; = 2
- RHS evaulated first
- int numFriends = 5;
- int cookiesPerFriend = numCookies / numFriends; = 2.4 = 2

Integer Division - Casting
- If we want to keep the precision, we need to treat the integers as **doubles** and store the result in a double.
- int numCookies = 12;
- int numFriends = 5;
- double cookiesPerFriend = ( (double) numCookies) / numFriends; = 2.4

### Module 2 - Data and Expressions - Expressions (Part 2) Lecture
Modulo (aka Remainder)
- Examples:
- 139 / 6 = 23 with remainder 1, thus 139 % 6 =1
- 7 / 2 = 3 R1, 7 % 2 = 1

-  a modulo b is a remainder of the result of a divided by b.
-  Used to determine how many are left over.
-  Used to determine if numbers are divisible by a number.
-  Clocks are modulo 12 (or 24 if using "military time").
-  Used in cryptography/encryption.

-   What are the results?
-   14 % 3 = 2
-   8 % 12 = 8
-   10 % 2 = 0
-   7 % 6 = 2
-   0 % 6 = 0
-   9 % 0 = error

Order of Operations  
- Evaluated from left to right in order of precedence.
- What you are used to in math.
- Can lead to bugs in code if you aren't careful.
- When in doubt, use parentheses for clarity.

Knowledge Check - Order of Operations

### Module 2 - Data and Expressions - Assignment Operators Lecture Notes
Assignment Operators  
- It is common for the RHS and LHS of an expression to contain the same variable.
- count = count - 1;
- money = money * 1.5;
- sentence = sentence + " next word";
- Java provides **assignment operators** to simplify expressions.
- +=, -=, *=, /=, %=
- count -= 1;
- money *= 1.5;
- sentence += " next word";

Increment and Decrement Operators  
- The **increment operator** (++) adds one to its operand.
- int count = 10;
- count++; //same effect as count = count + 1;
- The **decrement operator** (--) adds one to its operand.
- int count = 10;
- count--; // same effect as count = count - 1;
- Note: It is best not to use these in larger expressions. They can cause confusion and unexpected results. Use only as a standalone statement.

### Module 2 - Data and Expressions - Data Conversion (part 1) Lecture Notes
Relative Data Sizes  
- Smaller data types can be stored in larger types without risk of lsoing data.

"Widening" Conversions  
- If the type of the variable is "wider" than the type of the value being assigned, the **assignment conversion** occurs automatically.
- int smallNumber = 10025;
- long bigNumber = smallNumber;
- double bigDecimal = bigNumber;

Automatic Assignments  
- Not all dyles will be automatically assigned.
- For the data types we have discussed, here are valid automatic assignments.

"Narrowing" Conversions  
- If the type of the variable is "narrower" than the type of the value being assigned, the assignment conversion fails to occur automatically.
- long bigNumber = 9223372036854L;
- int smallNumber = bigNumber; // error only first 4 numbers
- double decimal = 9223.34;
- int whole number = decimal; // error only whole number

Casting  
- We can explicity force narrowing conversions by **casting** data to a different type.

Casting - Integer Division  
- numCookies is **cast** as a double in this expression. It does not become a double, it behaves as a double temporarily.
- int numCookies = 12;
- int numFriends = 5;
- double cookiesPerFriend = ( (double) numCookies) / numFriends;

Casting - Limitations  
- Not all types can be cast as different types.

Wrapper Classes  
- the conversions we've discussed so far are specific to primitive data types. It is not possible to use a cast to convert between a primitive type and a String, for instance.
- String answer = (String)42; // Not allowed.
- However, data on the right-hand side can be manually (or automatically) converted to a compatible data type before it is assigned. Each primitive type has a cooresponding Wrapper type that can perform the conversion.
- String answer = Integer.toString(42);
- int value = Integer.parseInt(answer);

Assignment Conversion and Casting
- Which of the following conversion are valid? Which are not?
- String amount = (String) 10000; // Not valid
- int result = 3.467; // valid
- int count = (int) 56.23; // valid
- double pi = count; // valid
- boolean isOn = (boolean) "true"; // Not valid

### Module 2 - Data and Expressions - Data Conversion (part 2) Lecture Notes  
Promotion - Conversion in Expressions  
- When an operator applies **promotion** to a pair of operands, each of which must denote a value that is convertible to a numeric type, the following rules apply, in order:
- If either operand is of type double, the other is converted to double.
- Otherwise, if either operand is of type float, the other is converted to float.
- Otherwise, if either operand is of type long, the other is converted to long.
- Otherwise, both operands are converted to type int.

Promotion in Expressions  
- When multiple data types are used in an expression, **promotion** happens automatically.
- Consider the following expression:
- double sum = 10.5;
- int count = 3;
- double average = sum / count; // count is promoted to a double when the expression is evaluated.

Promotion in Expressions - Pitfalls  
- When **only int data types** are used in an expression, the result will be an integer. There is nothing to promote.
- Consider the following expression:
- int sum = 10;
- int count = 3;
- double average = sum / count; // result will be an integer

Order of Operations and Promotion  
- Recall: Expressions are evaluated from left to right in order of operator precedence.
- The order can change results of an expression, especialy where integer division is involved.
- final double PI = 3.14159;
- double radiusCubed = 1.0;
- double volume1 = 4 / 3 * PI * radiusCubed;
- double volume2 = PI * radiusCubed * 4 / 3;
- volume1 does not equal volume 2.

### Module 2 - Data and Expressions - User Input Lecture Notes  
Reading User Input  
- The **Scanner** class allows us to read text from a given input.
- It is commonly used to read keyboard input from the user to creative interactive programs. (We will see later that it can also read from files and parse through Strings).
- By default, whitespace is used to seperate input elements, called **tokens**. Whitespace includes tabs ('\t') spaces, and newline characters ('\n'. '\r').

Reading Various Data Types  
- Several methods are provided to read tokens of various types.
- String: **next()** Finds and returns the next complete token from this scanner.
- String: **nextLine()** Advances this scanner past the current line and returns the input that was skipped.
- int: **nextInt()** Scans the next token of the input as an int.
- double: **nextDouble()** Scans the next token of the input as a double.

### Module 2 - Data and Expressions - TempConverter Example Lecture Notes

## Module 3
### 3.1 Objects: Introduction  
Grouping things into objects  
- In programming, an **object** is a grouping of data (variables) and operations that can be performed on that data (methods).

Abstractions/Information hiding  
- **Abstraction** means to have a user interact with an item at a high-level, with lower-level internal details hidden from the user (aka **information hiding** or **encapsulation**.)
- An **abstract data type (ADT)** is a data type whose creation and update are constrained to specific well-defined operations.

### 3.2 Using a Class  
Class intro: Public member methods  
- The **class** construct defines a new type that can group data and methods to form an object. A class' **public member methods** indicate all operations a class user can perform on the object.

Using a class  
- A **reference variable** can refer to an instance of a class. The **new** operator explicitly allocates an **object** of the specified class type.
- The "." operator, known as the **member access operator**, is ued to invoke a method on an object.

Class example: String  

### 3.3 Objects and References
References  
- A **reference** is a variable type that refers to an object.

Multiple object references  
- Two or more reference variables may refer to the same object, as illustrated below.

### 3.4 Primitive and reference types  
Wrapper classes
- Java variables are one of two types.
- A **primitive type** variable directly stores the data for that variable type, such as int, double, or char. Ex: _int numStudents = 20;_ declares and int that directly stores the data 20.
- A **reference type** variable can refer to an instance of a class, also known as an object.
- Java provides several **wrapper classses** that are built-in reference types that augment the primitive types. The **Integer** data type is a built-in class in Java that augments the int primitive type. Ex: _Integer maxPlayers = 10;_ declares an Integer reference variable named maxPlayers that referes to an instance of the Integer class, also known as an Integer object.

Memory allocation for the wrapper class objects  
- A wrapper class object (as well as a String object) is **imutable**, meaning a programmer cannot change the object via methods or variable assignments after object creation. When the result of an expression is assigned to an Integer reference variable, memory for a new Integer object with the computed value is allocated, and the reference (or address) of this new object is assigned to the reference variable.

Comparing wrapper class objects  
- For reference variables of wrapper classes (e.g., Integer, Double, Boolean), a common error is to use the equality operators _==_ and _!=_ when comparing values, which does not work as expected.
- Although a programmer should never compar two reference variables of wrapper classes using the equality operators, a programmer may use the equality operators when comparing a wrapp class object with a primitive variable or a literal constant.
- Reference variables of wrapper classes can also be compared using the **equals()** and **compareTo()** methods. These method descriptions are presented for the Integer class, but ally equally well to the other wrapper classes.

### 3.5 Wrapper class conversions 
Autoboxing and unboxing  
- Java allows statements to combine primitive and wrapper class variables by automatically converting between primitive types and wrapper classes. **Autoboxing** is the automatic conversion of primitive types to the corresponding wrapper classes. **Unboxing** is the automatic conversion of wrapper class objects to the corresponding primitive types.

Converting to primitive types  
- The Integer, Double, and Long wrapper classes provide methods for converting objects to primitive types
- **intValue()**
- **doubleValue()**
- **longValue()**
- The Character and Boolean classes support the **charValue()** and **booleanValue()** methods, respectively, which perform similar functions.

Converting to and from Strings  
- Wrapper classes feature methods that are useful for converting to and from Strings. Several of these methods are static methods, meaning they can be called by a program without creating an object. To call a static method, the name of the class and a '.' must precede the static method name, as in _Integer.toString(16);_
- **toString()**
- **Integer.toString(someInteger)**
- **Integer.parseInt(someString)**
- **Integer.valueOf(someString)**
- **Integer.toBinaryString(someInteger)**

### 3.6 Using packages 
Built-in Java packages  
- Java provides a variety of built-in classes, such as Scanner, ArrayList, File, and many others, that programmers can use to write programs. Given the large number of built-in classes, Java organizes related classes into groupings called packages.
- A **package** is a grouping of related types, classes, interfaces, and subpackage. The types, classes, and interfaces in a package are called **package members**.

Using package members in a program  
- A programmer can use a package member using one of the following methods.
- Using a package member's fully qualified name: A class' **fully qualified name** is the concatenation of the package name with the class name using a period. Ex: _java.util.Scanner_ is the fully qualified name for the Scanner class in the java.util package.
- Using an import statement to import the package member: An **import statement** imports a package member into a file to unable use of the package member directly, without having to use the package member's fully qualified name. Ex: _import java.util.Scanner;_ imports the Scanner class into a file and allows a programmer to use SCanner instead of java.util.Scanner.
- Using an import statement to import every member in a package: A programmer imports all members of a package by using the **wildcard** character * instead of a package member name. Ex: _import java.util.*;_ imports all classes in the java.util package.

### 3.7 Random numbers  
Generating a random number
- The **Random** class provides methods that return a random integer in the rang -2^31 to 2^31 - 1 or a programmer-defined range.
- The statement _import java.util.Random;_ enables use of the Random class. The statement _Random randGen = new Random();_ creates a new random number generator named randGen. The method call randGen.nextInt() can then be used to get a random integer ranging from -2^31 to 2^31 -1.
- An argument can be passed to the next to the nextInt() method to return an integer between 0 (inclusive) and the specified value (exclusive). Ex. **nextInt(10)_ return 10 possible values: 0, 1, 2 ..., 8, 9.

Specific ranges  
- The programmer should first determine the number of values in the range, generate a random integer with that number of possible values, and then add x to adjust the range to start with x.

Pseudo-random  
- The integers generated by a Random object are known as pseudo-random. "Pseudo" means "not actually, but having the appearance of". Internally, the nextInt() method has an equation to compute the next "random" integer from the previous one, (invisibly) keeping track of the previous one. For the first call to nextInt(), no previous random integer exists, so the method uses an integer known as the **seed**.
- A programmar can specify the seed when the Random obkect is created, as in _Random randGen = new Random(5);_ or using the setSeed() method, as in _randGen.setSeed(5);_.

### Module 3 - Using Classes and Objects - Object Oriented Programming Lecture Notes
What is Object-Oriented Programming?
- Java is one of many **object-oriented programming (OOP)** languages.
- **Objects** are used to represent real-worl entities.
- Allows us to map our program to the real situations that our programs represent.
- Can make it much easier to solve problems.

Terms, terms, terms
- We will be using several new terms when we start using OOP concepts.
- object
- attribute
- method
- class
- encapsulation

Object
- Objects in the real-world share two characteristics: **state** and **behavior**.
- Objects in programs often map to real world objects. They too have state and behavior.

Attributes  
- Represent an object's **state**. The values that make up the object.
- Can be _primitive data types_ or other objects.
- Note: may also be referred to as **fields, instance variables, properties**.

Methods  
- Provide a way to execute an object's **behaviors**.
- A group of programming statements that is given a name.
- Note: may also be referred to as **functions, operations, actions**.

Class  
- Defines the **attributes and methods** of a type or class of objects.
- A **blueprint** from which objects are created.
- Classes define new, compound data types.

Encapsulation  
- The technique of controlling and protecting the data of an object.
- We can provide controlled access through **public** methods of an object.
- If we don't want something to be exposed, we make it **private**.

### Module 3 - Using Classes and Objects - Using Classes and Objects Lecture Notes
Steps to create and use an object
- **Import** the class from the Java API.
- **Declare** that we want to create an instance of the class - an object.
- **Instantiate** our object using the constructor of the class.
- **Invoke** or **call** the methods of our object to perform desired operations.

1. Importing classes
- All classes in the java.lang package are automatically included in our programs.
- When we want to use a class from a different package in the Java API, we need to **import** it at the top of our program.
- We use something like
- import java.awt.Point;
- import java.awt.*;

2. Declaring an object instance
- We access our objects using **declared** variables - just as we did for Strings and primitive types. (In fact, a String is a class(.
- _String className;_    _Point origin;_
- The name of the class is the **type** of the variable.
- Note: Class names use TitleCase, not camelCase.

3. Instantiating an object
- To **instantiate** (or create) an object, we use a special method provided by the class called the _constructor_.
- The **constructor** defines which attributes the object needs from the user in order to create it.
- We give the attributes to the constructor through **parameters**.
- The name of the constructor method is always the exact same name as the class itself.

Using a Constructor
- For example, to create an instance of the java.awt.Point class, we must give it the x and y values of the point we want to represent.
- The constructor is defined as:
- Point (int x, int y)
- To use the constructor to create a new object, we use the _new_ operator.
- Point origin = new Point(10, 20);

Reference Variables
- Constructors return a **reference** to the object that was created in the computer's memory.
- The variable that stores the object's reference point is known as a reference variable.
- Sometimes we say the variable "points to" the object.
- Point origin = new Point (10, 20);

Aliases
- Two variables can reference the same object in memory. They are known as **aliases**.
- Point origin = new Point(10, 20);
- Point center = origin;
- If we make any changes to the object, it changes for both.

Recap: Reference vs Primitive Variables
- Reference variables store a **reference to** an object in memory.
- Point origin = new Point(10, 20);
- Point center = origin;

- Primitive type variables store the actual **value of** the data.
- int myNumber = 10;
- int yourNumber = myNumber;

4. Invoking Methods
- After we instantiate our object, we have an instance.
- We can call the methods of the class on our instance using the **dot operator**.
- Parenthesis after the method name are required. This is where we pass parameters to our methods -- like passing values to functions in math: f(X).
- variableName.methodName(optionalParams);

Understanding method documentation
- For example, to invoke methods from the java.awt.Point class, we first want to look for available methods in the Point documentation
- The methods are defined in two columns. For example,
- double - getX()
- void - setLocation(int x, int y)

- To get the X coordinate of our originPoint we created, we can use the getX() method.
- Point origin = newPoint(10, 20);
- double x = origin.getX();
- System.out.println("Origin X: " + x);

Putting it all together.  

### Module 3 - Using Classes and Objects - Strings
String Representation and Indices
- Each character of a String has an index.
- We can access specific characters or sub-sequences of characters using the indices.
- The first character is always at indix 0.

Selected Methods  
- int - length() Returns the legnth of this string.
- char - charAt(int index) Returns the char value at the specified index.
- int - indexOf(char ch)  Returns the index within this string of the first occurence of the specified character.
- String - substring(int beginIndex, int endIndex) Returns a string that is a substring of this string.
- String - substring(int beginIndex) Returns a string that is a substring of this string.

String representation and Indices
  - int length = phrase.length();
  - char lastChar = phrase.charAt(length - 1);
  - int space = phrase.indexOf(' ');
  - String wordTwo = phrase.substring(space + 1);
  - string wordOne = ??;
 
Selected Methods
  - Helpful methods for modifying existing Strings. Note, they all return a new String.
  - String - replace(char oldChar, char newChar) Returns a string resulting from replacing all occurrences of oldChar in this string with newChar.
  - String - toLowerCase() Converts all of teh characters in this String to lower case using the rules of the default locale.
  - String - toUpperCase() Converts all of the characters in this String to upper case using the rules of the default locale.
  - String - trim() Returns a string whose value is this string, with any leading and trailing whitespace removed.
 
Strings are Immutable  
- Once a String is created, it cannot be changed. When we modify Strings, the original String stays the same and a new String is returned.
- String name = "Mickey Mouse";
- String loadName = name.toUpperCase();
- // What are the values of name and loudName?
- String phrase = "Hello World";
- phrase = phrase.toLowerCase();
- // What is the value of phrase?

Selected Methods  
- int - compareTo(String anotherString) Compares two strings lexicographically.
- int - compareToIgnoreCase(String str) Compares two strings lexicographically, ignoring case differences.
- boolean - equals(Object anObject) Compares this string to the specified object.
- boolean - equalsIgnoreCase(String anotherString) Compares this String to another String, ignoring case considerations.

### Module 3 - Using Classes and Objects - Random  
Why Random Numbers?
- Random numbers are used often in software.
- Shuffling
- Rolling Dice
- Simulations
- Security
- Games
- ect.

Pseudorandom Numbers  
- The Random class represents a **pseudo-random number generator**.
- Picks a random number out of a range of numbers.
- Since a program can't actually pick a random number, it executes a series of complex calculations based on an initial **seed value** to produce a statistically random number.

Constructor and Selected Methods  
- Random() Creates a new random number generator.
- Random(long seed) Creates a new random number generator using a single long seed.
- int - nextInt() Returns the next pseudorandom, uniformly distributed int value from this random number gnerator's sequence.
- int - nextInt(int bound) Returns a pseudorandom, uniformly distributed int value between 0 (inclusive) and the specified value (Exclusive), drawn from this random number generator's sequence.

Example
- import java.util.Random; // import class
- Random generator = new Random(); // instantiate object
- int anyNum = generator.nextInt(); // get random number
- int flip = generator.nextInt(2); // get random number in range [0-1]

### Module 3 - Using Classes and Objects - Math Lecture Notes  
The Math Class
- Provides basic mathematical functions
- static int - abs(int a) Returns the absolute value of an int value.
- static double - cas(double a) Returns the trignometric cosine of an angle.
- static double - sin(double a) Returns the trignometric sine of an angle.
- static double - tan(double a) Returns the trignometric tangent of an angle.
- static double - pow(double a, double b) Returns the value of the first argument raised to the power of the second argument.
- static double - sqrt(double a) Returns the correctly rounded positive square root of a double value.

Static Methods  
- All methods of the Math class are **static methods**, also called class methods.
- This means we can invoke them through the name of the class without having to create an instance of the ibject first.
- double result = Math.pow(x, 2);
- double root = Math.sqrt(result);

### Module 3 - Using Classes and Objects - Decimal Formatting Classes Lecture Notes
Examples

### Module 3 - Using Classes and Objects - Enumerated Types
Enumerated Types  
- An **enumerated (enum) type** is a special type that provides a predefined, fixed set of constances.
- consider using enums when a variable can only be one of a small set of values
- Examples:
- Days of the week (Monday, Tuesday, Wednesday,...)
- Directions (North, South, East, West)
- Status (Playing, Paused, Stopping, Waiting)

Enum
- An **enum** is a simplified class that pre-defines all the possible instances of the class.
- Consider a program that uses a String variable to represent the suit of a card.
- String suit = "Heats";
- This can work, but what if the user decides to set the suit to something invalid?
- String suit = "Triangle";
- Because any string is valid, there is nothing preventing this from happening. Enums can help us solve this problem.

Card Suit Enum 
- We can define an enum type for the set of possible suits,
- public enum Suit {Clubs, Diamonds, Hearts, Spades};
- Now, just like a class, we can declare a variable of type Suit.
- Suit cardSuit;
- Because it is of type Suit, we must assign it one of the pre-defined values.
- cardSuit = Suit.Hearts;
- We call enum values **type-safe** because they can only contain a value of the enum type.

### Module 3 - Using Classes and Objects - Wrapper Classes
Automatic Assignments  
- Not all types will be automatically assigned.
- For the data types we have discussed, here are valid automatic assignments.
- Wrapper Classes allow converting from String objects to primitive data types.

Casting - Limitations
- Not all types can be cast as different types.
- Wrapper Classes also allow converting from primitive data types to String objects.
- However these typically do not need to be called because java often handgles this automatically as part of the concatenation operation.

## Module 4 Part 1 Reading
### 4.1 If-Else branches(general)
Branch Concept  

Branch basics (If)
- In a program, a **branch** is a sequence of statements only executed under a certain condition.
- An if branch is taken only IF an expression is true.

If branch exmaple: Absolute value  

If-else branches
- An **if-else** branch has two branches: The first branch is executed IF an expression is true, ELSE the other branch is executed.

If-else example: Max  

If-elseif-else branches
- Commonly a programmer wishes to take one of multiple (three of more) branches. An if-else can be extended to an if-elseif-else structure.
- Note: The else part is optional. If omitted, then if none of the previous expressions are true, no branch executes.

### 4.2 Detecting equal values with branches
Detecting if two items are equal using an if statement
- A program commonly needs to determine if two items are equal.
- An **if** statement executes a group of statements if an expression is true. Braces surround the if branch's statements. **Braces** {}, sometimes redundantly called curly braces, represent a grouping, such as a grouping of statements.
- The **equality operatory (==)** evaluates to true if the left and right sides are equal.
- Good practice is to indent a branch's statements, using a consistent number of spaces.

Equality and inequality operators  
- Whereas the equality operator checks whether two values are equal, the **inequality operator (!=)** evaluates to true if the left and right sides are not equal, or different.
- An expression involving the equality or inequality operators evaluates to a Boolean value. A **Boolean** is a type that has just two values: true or false.

If-else statement
- An **if-else** statement executes one group of statements when an expression is true, and another group of statements when the expression is false.

Multi-branch if-else statements  
- Commonly, a program may need to detect several specific values of a variable. An If-else statement can be extended to have three (or more) brances. Each branch's expression is checked in sequence. As soon as one branch's expression is found to be true, that branche's statements execute (and no subsequent branch is considered). If no expression is true, the else branch executes.

Comparing characters, strings, and floating-point types
- The relational and equality operators work for integer, character, and floating-point built-in types.
- Comparing characters compares their Unicode numerical coding.
- Floating-point types should not be compared using the equality operators, due to the imprecise representation of floating-point numbers.
- The operators should not be used with strings; unexpected results will occur.

### 3.3 Detecting ranges with branches (general)
Detecting ranges using if-elseif-else
- A common programming cast is to detect if a value lies within a certain range and then perform an action depending on where the value lies.
- An if-elseif-else structure can detect number ranges with each branch performing a differect action for each range. Each expression only needs to indicate the upper range part; if execution reaches an expression, the lower range part is implicit from the previous expressions being false.

Using multi-branch if-else to detect ranges
- The sequential nature of multi-branch if-else statements is useful to detect ranges of numbers. In the following example, the second branch expression is only reached if the first expression is false. So the second branch is taken if userAge < 16 is false (so 16 or greater) AND userAge < 25, meaning userAge is between 16 - 24 (inclusive).

### 4.4 Detecting ranges with branches  
Relational operators  
- A **relational operator** checks how one operand's value relates to another, like being greater than.
- Some operators, like >=, involve two characters. A programmer cannot arbitrarily combine the >, =, and < symbolbs; only the shown two-character sequences represent valid operators.

### 4.5 Detecting ranges using logical operators  
Logical AND, OR, and NOT (general)  
- A **logical operator** treats operands as being true or false, and evaluates to true or false. Logical operators include AND, OR, and NOT. Programming languages typically use various symbols for those operators, but below the words AND, OR, and NOT are used for introductory purposes.

- a AND b: **Logical AND**: true when both of its operands are true.
- a OR b: **Logical OR**: true when at least one of its two operands are true.
- NOT a: **Logical NOT**: true when its one operand is false, and vice-versa.

Detecting ranges with logical operators (general)
- A common use of logical operators is to detect if a value is within a range.

Logical operators  
- Special symbols are used to represent the AND, OR, and NOT logical operators. Logical operators are commonly used in expression of if-else statements.

- a && b: **Logical AND** (&&): true when both its operands are true
- a || b: **Logical OR** (||): true when at least one of its operands are true
- !a: **Logical NOT** (!): true when its one operand is false, and vice-versa.

Detecting ranges implicity vs. explicity  
- A programmer often uses logical operators to detect a range by explicity specifying the high-end and low-end of the range. However, if a program should detect increasing ranges without gaps, a multi-branch if-else statement can be used without logical operators; the low-end of the rang is implicity known upon reaching an expression. Likewise, a decreasing range without gaps has implicitly-known high-ends.

### 4.6 Detecting ranges with gaps  
Basic ranges with gaps  
- Oftentimes, ranges contain gaps. An if-else statement can be used to detect such ranges with gaps.

Ranges with gaps using logical operators  
- Programmers often use logical operators to explicitly detect ranges with an upper and lower bound, including ranges with gaps that may have intermediate bounds. Further, the ranges can be combined into a single branch using the logical OR operator.

### 4.7 Detecting multiple features with branches  
Multiple distinct if statements 
- A programmer can use multiple if statements in sequence to detect multiple features with independent actions. Multiple sequential if statements look similar to a multi-branch if-else statement but has a very different meaning. Each if-statement is independent, and thus more than one branch can execute, in constrast to the multi-branch if-else arrangement.

Nested if-else statements  
- A branch's statements can include any valid statements, including another if-else statement, which are known as **nested if-else** statements. Nested if statements are commonly used to make decisions that are based on multiple features.

### 4.8 Common branching errors
Common error: Missing braces
- When a branch has a single statement, the braces are optional, but good practice always uses the braces. Always using braces even when a branch only has one statement prevents the common error of mistakenly thinking a statement is part of a branch.

Common error: Using the incorrect operators  
- A common error is to use = rather than == in an if-else expression.

### 4.11 Switch statements
Switch statement
- A **switch** statement can more clearly represent multi-branch behavior involving a variable being compared to constant values. The program executes the first **case** whose constant expression matches the value of the switch expression, executes that case's statements, and then jumps to the end. If no case matches, then the **default case** statements are executed.

Switch statement general form
- The switch statement's expression should be an integer, char, or string. The expression should not be a Boolean or a floating-point type. Each case must have a constant expression like 2 or 'q'; a case expression cannot be a variable.
- The order of cases doesn't matter assuming break statements exist at the end of each case. The earlier program could have been written with case 3 first, then cas 2, then case 0, then case 1, for example.
- Good practice is to always have a default case for a switch statement.

Omitting the break statement
- Omitting the **break** statement for a case will cause the statements within the next case to be executed. Such "falling through" to the next case can be useful when multiple cases, such as cases 0, 1, and 2, should execute the same statements.

### 4.12 Boolean data type
Boolean data type  
- **Boolean** refers to a quantity that has two possible values, true or false. Java has the built-in data  type **boolean** for representing Boolean quantities.
- A Boolean variable may be set using true or false keywords. A Boolean variable may also be set to the result of a logical expression.

Uses of Boolean data types
- A programmer can use a Boolean variable to simplify a complex expression. An expression that combines logical and relational operators can be simplified by assigning boolean variables with the result of the expression using relational operators. The if-else expression can then consist of only logical operations using those variables.

### 4.13 String comparisons  
String comparison: Equality  
- Two strings are commonly compared for equality. Equal strings have the same number of characters, and each corresponding character is identical.
- A programmer can compare two strings using the notation _str1.equals(str2)_. The **equals** method returns true if the two strings are equal. A common error is to use == to compare two strings, which behaves differently than expected.

String comparison: Relational
- Strings are sometimes compared relationally (less than, greater than), as when sorting words alphabetically. A comparison begins at index 0 and compares each character until the evauluation results in flase, or the end of a string is reached.
- A programmer compares strings relationally using the notation str1.compareTo(str2). **compareTo()** returns value as follows:
- Table 4.13.1

- A common error is to forget that case matteres in a string comparison. A programmer can compare strings while ignoring case using str.equalsIgnoreCase(str2) and str1.compareToIgnoreCase(st2).

### 4.14 String access operations  
String character indices  
- A string is a sequence of characters in memory. Each string character has a position number called an **index**, starting with 0 (not 1).

Accessing string characters
-**charAt()**: The notation someString.charAt(x) determines the character at index x of a string.  

Working with the end of a string  
- Determing the last character in a string is often useful. If a string's length is known, the last character is at index length -1. The method _s1.length()_ returns s1's length.
- A common task is to append(add to the end) a string to an existing string.
- The **+** operator can return a new string that appends a string to another string.
- Similarly, s1.concat(S2) returns a new string that appends s2 to s1.

Common errors
- A common error is ot access an invalid string index, especially exactly one larger than the largest index.

### 4.15 Character operations 
- The Character class provides several methods for working with characteres.
- Table 4.15.1

### 4.16 More string operators  
Finding in a string / Getting a substring  
- The String data type comes with several useful features. THe features are made possible due to String's implementation as a class, which for purposes here can be though of as several useful methods. Some useful methods are shown below.
- Table 4.161.

Combining / Replacing  
- The String class has more methods for modifying strings.
- Table 4.16.2

### 4.17 Conditional expressions
- If-else statements with the form shown below are so common that the language supports the shorthand notation shown.
- A **conditional expression** has the form _condition ? exprWhenTrue : exprWhenFalse_.
- All three operands are expressions. If the condition evaulates to true, then exprWhenTrue is evaluated. If the condition evaluates to false, then exprWhenFalse is evaluated. The conditional expression evaluates to whichever fo thsoe two expressions was evaluated.
- A conditional expression has three operands and thus the "?" and ":" together are sometimes referred to as a **ternary operator**.
- Good practice is to restrict usage of conditional expressions to an assignment statement.

### 4.18 Floating-point comparison  
- Floating-point numbers should not be compared using ==.
- Floating-point numbers should be compared for "close enough" rather than exact equality. The different threshold indicating that floating point numbers are equal is often called the **epsilon**.

### 4.23 While Loops 
While loop: Basics  
- A **while loop** is a program construct that repeatedly executes a list of sub-statements (known as the **loop body**) while the loop's expression evaluates to true. Each execution of the loop body is called an **iteration**. Once entering the loop body, execuation continues to the body's end, even if the expression would become false midway through.
- while (expression) { //Loop expression
-   //Loop body: Executes if expression evaluated to tru
-   //After body, execution jumps back to the "while"
- }
- //Statements that execute after the expression evaluates to false

Basic while loop example  

Getting input before a loop  
- Another common pattern gets that initial value from user input as well, thus getting input in two places: before the loop, and at the loop body's end.

Loop expressions  
- Various kinds of expression are found in while loop expressions. For example, sometimes a loop is executed as long as a value is greater than another value, or less than another value. Sometimes a loop is executed as long as a value is NOT equal to another value.

Common errors  
- A common error is to use the opposite loop expression than desired, like using x == 0 rather than x != 0. Programmers should remember that the expression describes when the loop should iterate, not when the loop should terminate.
- A **infinite loop** is a loop that never stops iterating. A common error is to accedentally create an infinite loop, often by forgetting to update a variable in the body, or be creating a loop expression whose evaluation to false isn't always reachable.
- Another common error is to use the assignment operator = rather than the equality operator == in a loop expression.

### 4.24 More while example
Example: GCD  

Example: Conversation  

Example: Getting input until a sentinel is seen
- Loops are commonly used to process an input list of values. A **sentinel value** is a special value indicating the end of a list, such as a list of positive integers ending with 0, as in 10 1 6 3 0.

### 4.25 For loops
Basics 
- A loop commonly must iterate a specific number of times, such as 10 times. Though achievable with a while loop, that situation is so common that a special kind of loop exists. A **for loop** is a loop with three parts at the top: a loop variable initialization, a loop expression, and a loop variable update. A for loop describes iterating a specific number of times more naturally than a while loop.
- The statement _i = i + 1_ is so common that the language supports the shorthand **++i**, with ++ known as the **increment operator**. (Likewise, **--** is the **decrement operator**, --i meaning i = i -1).
- Note: Actually two increment operators exist: ++i(**pre-increment**0 and i++(**post-increment**).

Example: Savings with interest  

Example: Computing the average of a list of input values  

Choosing amoung for and while loops  
- Generally, a programmer uses a for loop when the number of iterations is known (like loop 5 times, or loop numItems times), and a while loop otherwise.

### 4.26 More for loop examples  
Example: Finding the max  

Beyond iterating N times 
- The three parts of a for loop may be adjusted to do more than just iterate N times. For example, a for loop can output various sequences.

Example: Outputting a table of temperatures  

Loop style issues 
- Starting with 0: Programmers in C, C++, Java, and other langauges have generally standardized on looping N times by starting with i = 0 and checking for i < N, rather than by simply using i = 1 and i <= N. One reason is due to other constructs (arrays / vectors), often used with loops, start with 0.
- The ++ operators: The ++ operator can appear as ++i(**prefix form**) or as i++(**postfix form**). ++i increments i first and then evaluates the result, while i++ evaluates the result first and then increments i.
- In-loop declaration of i: Variables can be declared throughout code, so many programmers use: _for (int i = 0, i < N, ++i)_.

Common errors / good practice  
- A common error is to also have ++i; statement in the loop body, causing the loop variable to be updated twice per iteration.

### 4.27 Loops and strings
Iterating through a string with a for loop  
- A programmer commonly iterates through a string, examining each character.

Iterating until done with a while loop 

### 4.28 Nested loops  
- A **nested loop** is a loop that appears in the body of another loop. The nested loops are commonly referred to as the **inner loop** and **outer loop**.
- Nested loops have various uses. One use is to generate all combinations of some items.

### 4.20 Break and continue  
- A **break statement** in a loop causes an immediate exit of the loop.
- A **continue statement** in a loop causes an immediate jump to the loop condition check. 

## Module 4 - Conditionals and Loops - Lecture Videos
### Module 4 - Conditionals and Loops - Boolean Expressions Lecture Notes
Conitionals
- Conditionals give us the power to choose which statements in a program will be executed under specific conditions.
- If the sun is out, then it is day.
- If it is Tuesday and it is not summer, spring, or winter break, then I am in class.
- If the radius is greater than 100, then change the color to red.
- If the password equals the expected password, then grant access. Else, deny.

Relational Operators  
- Decisions are typically based on **equality** and/or **comparisons**.
- We can use the equality and comparison operators to compare data.
- Expressions using the operators return a **boolean**(true or false).
- (3 == 3) -> **true**
- (3 >= 4) -> **false**

- Operator - meaning
- == - equal to
- != - not equal to
- < - less than
- <= - less than or equal to
- > - greater than
- >= - greater than or equal to

Logical Operators  
- We can build compound decisions expressions using the **logical operators**.
- Logical AND (&&) and OR (||) operators have _lower precedence_ than the relational operators (aka. they are evaulated after).
- Logical NOT(!) has a higher precedence than only of the other logical and relational operators.
- Expressions using the operators take **boolean** operands and return a **boolean** (true or false).
- (true && false) -> **false**
- (!false) -> **true**

- Operator: Meaning
- ! : logical NOT
- && : logical AND
- || : logical OR

Logical Operators: Truth Tables

Example
- SmartHome.java

### Module 4 - Conditionals and Loops - Basic if Statement Lecture Notes  
Syntax  

if( condition )  
{  
  // statements    
}  
// other code    

Knowledge Check  
Write an if-statement
- Write an if statement that checks is the legnth of a String, name, is less than or equal to 50 characters.
- Guided experimentation

Alternate Syntax  
if ( condition )  
  // statement  
// other code    

### Module 4 - Conditionals and Loops - The if-else Statement Lecture Notes  
Syntax if-else  

if( condition )  
{  
  // statement  
}  
else  
{  
  // statement  
}  
// other code    

### Module 4 - Conditionals and Loops - The if-else-ef-else Statement Lecture Notes
Syntax if-else-if  

if ( condition1 )  
{  
  // statements  
}  
else if ( condition 2 )  
{  
  // statements    
}  
// other code    

Syntax if-else   

if (condition1)   
{  
  // statements  
}  
else if (condition2)  
{  
  // statements    
}  
else  
{  
  // statements    
}  
// other code    

Example  
- AgePhrases.java

### Module 4 - Conditionals and Loops - Nested if Statements Lecture Notes  
Nested Statements  
- The statements executed inside of if and else blocks can be additional if-else statements.
- This allows us to further define decisions in our code.
- If the username exists, then check if the password equals the expected password, else deny.

Syntax nested if  

if (condition1)   
{  
  if (condition2)  
  {  
    // statements  
  }  
  // statements    
}  
// statements    

### Module 4 - Conditionals and Loops - The Ternary Operator Lecture Notes  
Using the Ternary Operator  
- Allows you to **assign a value to a variable based on a boolean expression** in a single line of code.
- An alternative to the if-else syntax.
- Also called the "Conditional Operator".

General Syntax  

result = testCondition ? value 1 : value2;  

Example
- Dimes.java

### Module 4 - Conditionals and Loops - MinOfThree Example Lecture Notes  

### Module 4 - Conditionals and Loops - Comparing Floating Point Numbers Lecture Notes

### Module 4 - Conditonals and Loops - Comparing Characters Lecture Notes  

### Module 4 - Conditionals and Loops - Comparing Objects Lecture Notes  

### Module 4 - Conditionals and Loops - Comparing Strings Lecture Notes  

### Module 4 - Conditionals and Loops - Switch Statements Lecture Notes  
Syntax switch  
- The **expression** must result in an integer type, char, enum, or String.
- It cannot be a boolean value or floating point.

switch ( expression )  
{  
case value1:  
  // statements  
  break;  
case value 2:  
  // statements  
  break;  
default:  
  // statements  
}  

### Module 4 - Conditionals and Loops - While Loops Lecture Notes  
Key Elements of a Loop 
- **Initial conditions** (where do we start?)
- **Statements** (what are we going to do each time?)
- **Looping condition** (how long will we keep going?)

Syntax while  

while (condition)  
{  
  // statements  
}  
// other code  

Example
- BasicWhileLoops.java

### Module 4 - Conditionals and Loops - Infinite Loops Lecture Notes  

### Module 4 - Conditionals and Loops - For Loops Lecture Notes  
Key Elements of a Loop 
- **Initial conditions** (where do we start?)
- **Statements** (what are we going to do each time?)
- **Terminating conditions** (how long will we keep this going?)

Syntax for  

for (initialization; condition; increment)  
{  
  // statements  
}  
// other code  

While Loop vs For Loop
- While num is less than or equal to 5, print the value of num
- For num from 1 to 5 (inclusive), print the value of num

Example
-  BasicForLoops.java

### Module 4 - Conditionals and Loops - Strings and Loops Lecture Notes  

### Module 4 - Conditionals and Loops - Nested for Loops Lecture Notes  
Syntax nested loop
- The body of a loop can contain another loop.
- For each iteration of the outer loop, the inner loop iterates completely.

for (initialization; condition; increment)  
{  
  // statements  
  for (initialization; condition; increment)  
  {
    // statements  
  }  
}  

## Module 5 Reading Notes  
### 5.1 User-defined method basics 
- Methods (general)
- A program may perform the same operation repeatedly, causing a large and confusing program due to redundancy. Program redundancy can be reduced by creating a grouping of predefined statements for repeatedly used operations, known as a **method**.

Basics of methods
- A **method definition** consists of the new method's name and a block of statement.
- A **method call** is an invocation of a method's name, causing the method's statements to execute.
- The method's name can be any valid identifier. A **block** is a list of statements surrounded by braces.
- Methods must be defined within a class. A **method** is a named list of statements. **Access modifers** public static

Returning a value from a method  
- A method may return one value using a **return statement**.
- Other return types are allowed, such as char, double, etc. A method can only return one item, not two or more. A return type of **void** indicates that a method does not return any value.

Parameters  
- A programmer can influence a method's behavior via an input.
- A **parameter** is method input specifided in a method definition.
- An **argument** is a value provided to a method's parameter during a method call.
- A parameter is like a variable declaration.
- An argument may be an expression.

Multiple or no parameters  
- A method definition may have multiple parameters, separated by commas. Parameters are assigned argument values by position.
- A method definition with no parameters must still have the parentheses.

Calling methods from methods  
- A method's statements may call other methods.

### 5.2 Print Methods  
Printing from a method  
- A common operation for a method is to print text. A method that only prints typically does not return a value. the **void** keyword indicates a method does not return a value. A method with a void return type is often called a **void method**. Once a void method finishes execution, control reutnrs to the caller and no value is returned.

Calling a print method multiple times  
- One benefit of a print method is that complex output statements can be written in code once. Then the print method can be called multiple times to produce the output instead of rewriting complex statements for every necessary instance.

Example: Menu system  

### 5.3 Reasons for defining methods  
Improving program readability  
- Decomposing a program into methods can greatly aid program readability, helping yield an initially correct program, and easing future maintenance.

Modular and incremental program development  
- Programmers commonly use methods to write programs modularly and incrementally.
- **Modular development** is the process of deviding a program into separate modules that can be developed and tested separately and then integrated into a single program.
- **Incremental development** is a process in which a programmer writes, compiles, and tests a small amount of code, then writes, compiles, and tests a small amount more (an incremental amount), and so on.
- A **method stub** is a method definition whose statements have not yet been written.

Avoid writing redundant code  
- A method can be defined once, then called from multiple places in a program, thus avoiding redundant code.
- A general guidleline (especially for begineer programmers) is that a method's definition usually shouldn't have more than about 30 lines of code, although this guideline is not a strict rule.

### 5.4 Writing mathematical methods  
Mathematical methods  
- A method is commonly defined to compute a mathematical calculation involving several numerical parameteres and returning a numerical result.

Calling methods in expressions  
- A method call evaluates to the returned value. Thus, a method call often appears within an expression.
- A method call with a void return type cannot be used within an expression, instead used in a statement.

Modular methods for mathematical expressions  
- Modularity allows more complex methods to incorporate similar functions. Complex mathematical methods often call other mathematical methods.

### 5.5 Methods with branches  
Example: Shipping cost calculator

Example: Auction website fee calculator  

### 5.8 How methods work  
- Each method call creates a new set of local variables, forming part of what is known as a **stack frame**. A return causes these local variables to be discarded.

### 5.9 Methods: Common errors
- A common error is to copy-and-paste code among methods but then not complete all necessary modifications to the pasted code.
- Another common error is to return the wrong variable.
- Failing to return a value for a method is another common error.

### 5.10 Scope of variable/method definitions  
- The name of a defined variable or method item is only visible to part of a program, known as the item's **scope**. A varibale declared in a method has scope limited to inside that method.
- A variable declared within a class but outside any method is called a class member variable or **field**, in contrast to a local varibale defined inside a method.
- Furthermore, if a method updates a field, the method has effects that go beyond its parameters and return value, sometimes known as **side effects**, which unless done carefully can make program maintenance hard.

### 5.11 Method name overloading  
- Sometimes as program has two methods with the same name but differing in the number or types of parameters, known as **method overloading** or just **method overloading**.

### 5.12 Parameter error checcking
Verifying parameter values  
-A good practice is to check that a parameter's value is within an exprected range.  

### 5.13 Using Scanner in methods  
Passing Scanner to methods  
- A program should only use one Scanner per input stream.
- If a method needs to read user input, a good practice is to create a single Scanner object in main() and pass that Scanner object to the method.

### 5.14 Using references in methods  
Storage of primitive data types and arrays  
- Arrays can be used in methods just like int and double values. However, an array is stored in memory differently than variables of primitive data types, like int or double. An int and double variable is stored directly in the stack frame. An array is stored indirectly in the help, and only the reference to the array is stored in the stack frame.
- Passing an int variable as an argument to a method results in the parameter having a seperate copy of the int variable's value.

Passing array references  
-  

Modifying an array in a method  
- When an array is passed to a method, the array's reference is copied to the method's stack frame. Two array elements can be swapped in a method.

Common error: Modifying an array reference in a method  
- A common error is trying to modify an array reference in a method. When an array reference is passed to a method, the reference itself is passed by value. A method cannot change the argument's array reference, since separate copies of the array reference are stored in two different stack frames. Changing the array reference in the method does not change the argument.

### 5.15 Java documentation for methods  
- An important part of a program is its **documentation**, which is a written description of a program and its various parts, intended to be read by programmers who must maintain or interface with the program.
- **Javadoc** is a tool that parses specially formatted multi-line comments to generate program documentation in HTML format. The program documentation is also known as and **API** (application programming interface). Those special **doc comments** begin with /** and end with */.
- The overall description describes the items purpose and extends to the first @, which denotes the beginning of the tags section. A Javadoc comment tags section consists of **block tags**, each of the form @keyword plus text, each block on its own line.
- Good practice is to include a doc comment for every method, having at least a overall description, a @param block tag for each parameter, and a @return block tag if not void.
- Common block tags in doc comments:
- @author : Lists the item's author.
- @version: Indicates the item's version number (typically for a program).
- @param : Describes a method parameter's type, purpose, etc.
- @return : Describes a method's return type, purpose, etc. Optional if return type is void.
- @see : Refers to relevant information like a website, another method, etc.

### 5.19 Streams using Strings  
Input string stream  
- A programmer can read data from a string instead of from the keyboard (standard input) by associating a Scanner object with a string. A Scanner object initialized from a String is often referred to as an **input string stream**.
- The statement _Scanner inSS = new Scanner(userInfo);_ creates a new Scanner object with a copy of the String userInfo. Then, the scanner can extract data from the Scanner inSS stream using methods like next(), nextInt(), nextDouble(), etc.

Line-by-line input processing 
- A common use of string streams is to process user input line-by-line.

Output string stream  
- An **output string stream** is a stream that can write to a String instead of to standard output. An output string stream allows a programmer to build and format a String before outputting to a file or the screen.
- An output string stream is created using both the StringWritter and PrintWriter classes, which are available by including: _import java.io.StrinWriter;_ and _import java.ioPrintWriter;_. The StringWriter class provides a character stream to output characters. The PrintWriter class augments character streams, such as StringWriter, with print() and println() methods to output various data types, in a manner similar to System.out.

### 5.22 ArrayList  
ArrayList introduction  
- Sometimes a programmer wishes to maintain a list of items, like a grocery list, or a course roster. An **ArrayList** is an ordered list of reference type items that comes with java. Each item in an ArrayList is known as an **element**. The statement _import java.util.ArrayList;_ enables use of an ArrayList.
- The declaration _ArrayList<Integer> vals = new ArrayList<Integer>()_ creates reference variable vals that refers to a new ArrayList object consisting of Integer object. ArrayList does not support primitive types like int, but rather reference types like Integer.
- A common error is to declare an ArrayList of a primtive type like int.

Common ArrayList methods  
- **add()** : add(element) Creates space for and add the element at the end of the lsit
- **get()** : get(index) Returns the element at the specified list location known as the **index**
- **set()** : set(index, element) Replaces the element at the specified position in this list with the specified element
- **size()** : size() Returns the number of list elements

Accessing ArrayList elements 
- The ArrayList's get() method returns the element at the specifided list location, and can be used to lookup the Nth item in a list. the program access the Nth most popular operating system using _operatingSystems.get(nthOs - 1);_. Note that the index is nthOS - 1 rather than just nthOS because an ArrayList's indices start at 0.
- An ArrayList's index must be an integer type.

Iterating through ArrayLists  

### 5.3 ArrayList ADT
