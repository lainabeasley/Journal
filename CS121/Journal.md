# Coding Journal
## Name: Laina 
## Lab: Module 1
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
