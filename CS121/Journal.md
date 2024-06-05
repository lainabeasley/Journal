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

## 2.3 Identifiers
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

## 2.4 Arithmetic expressions (general)
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

##2.7 Floating-point numbers (double)
