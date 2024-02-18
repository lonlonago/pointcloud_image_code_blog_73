directory 

6.5.1 understand interaction patterns 

6.5.2 into interactive mode 

Basic Usage of 6.5.3 Interaction Patterns 

6.5.4 get help in interactive mode 

6.5.5 exit interactive mode 

Learn Python 6.5.6 System 

##  6.5.1 understand interaction patterns 

To understand interaction patterns, one must first understand what interaction is. "Interaction" is very common in daily life. For example, the interaction between people is an interaction. In the language communication between you and me, each other can receive the information transmitted by the other in the language. Interaction in a computer refers to the feedback made by the program to the user's input, such as entering the URL of Python's official website in the address bar of the browser: 

![avatar]( 36b6c4697f1de02ff340db6a8a4a42dc.png) 

The browser will render and display the page content of Python's official website: 

![avatar]( 6a85f460cfe0cbc43daf9629a78ee37e.png) 

Execute the command on the command line, and the output of the command is the feedback made by the system. 

![avatar]( d4f1e632ea01ac4115dadbd82db376c5.png) 

All of the above is an interaction. An interaction is an interaction, a human interaction, a human interaction with a computer program. 

##  6.5.2 into interactive mode 

After entering the command line of the Windows system, you can directly execute Python commands in the command line to enter the interactive mode of Python. 

![avatar]( 4a8b1b4a9954b360efb869cb7fb17ff7.png) 

From the prompt information output from the interactive mode, you can know the Python version number, label signature, running environment, and four commands to obtain more information about Python. Among these four commands, help is used to obtain help information, copyright is used to obtain copyright information, credits is used to obtain thank you information, and license is used to obtain software license information. You can directly enter the above commands in interactive mode to obtain relevant information, such as viewing Python's copyright information: 

> >> copyright

Copyright (c) 2001-2019 Python Software Foundation.

All Rights Reserved.

Copyright (c) 2000 BeOpen.com.

All Rights Reserved.

Copyright (c) 1995-2001 Corporation for National Research Initiatives.

All Rights Reserved.

Copyright (c) 1991-1995 Mathematical Center Foundation, Amsterdam.

All Rights Reserved. 

##  Basic Usage of 6.5.3 Interaction Patterns 

In Python's interactive mode, you can directly define variables, control structures, functions, etc., and perform corresponding operations. 

(1) Define variables in interactive mode 

> >> number=1 

Enter the variable name in interactive mode and hit enter to automatically output the value pointed to by the variable: 

> >> number

1 

(2) Perform arithmetic operations in interactive mode 

> >> 1+1

2

> >> x=1

> >> y=1

> >> x+y

2 

(3) Calling a function in interactive mode 

The id function was introduced in Section 6.1. Calling the id function can output the memory address of an object. 

> >> total = 66

> >> amount = total

> >> id(66)

140705939880240

> >> id(total)

140705939880240

> >> id(amount)

140705939880240 

From the output of the id function, it can be seen that both the variable total and the variable amount store the memory address with the value 66. Students who are not very familiar with memory addresses can review the content in Section 6.1. Learning is an iterative process, and they must be good at integrating the knowledge they have learned. 

The memory address is related to the machine, and in different operating environments, different memory addresses are output. 

(4) Perform conditional control in interactive mode 

> >> number = 1

> >> if number > 0:

...     print("number > 0")

...

number > 0 

Students should pay attention to code indentation when entering the code of conditional statements in interactive mode. Other operations can also be performed in interactive mode, such as writing loop structures, function definitions, module imports, etc. In actual development, interactive mode is usually used for code debugging and quick verification. Interactive mode has another important purpose - to obtain help information, which will be explained in the next section. 

##  6.5.4 get help in interactive mode 

Using Python's built-in function help, you can get help information offline in interactive mode. Basic usage of the help function: 

help(object) 

Object represents the argument passed to the help function. Parameter passing takes the following two forms: 

(1) string type parameter 

Help (string type parameter) 

In Python, strings are enclosed in English single quotes, double quotes, and three quotes. String type parameters are usually predefined keyword names, attribute names, module names, etc. in Python. Keywords are system predefined identifiers, which are interpreted in Chinese as keywords. Execute help ("keywords") in interactive mode to query all keywords in Python: 

> >> help("keywords")

Here is a list of the Python keywords.  Enter any keyword to get more help.

False               class               from                or

None                continue            global              pass

True                def                 if                  raise

and                 del                 import              return

as                  elif                in                  try

assert              else                is                  while

async               except              lambda              with

await               finally             nonlocal            yield

break               for                 not 

Query the definition and usage of the if keyword in interactive mode: 

> >> help("if")

The "if" statement

******************

The "if" statement is used for conditional execution:

   if_stmt ::= "if" expression ":" suite

               ("elif" expression ":" suite)*

               ["else" ":" suite]

It selects exactly one of the suites by evaluating the expressions one

by one until one is found to be true (see section Boolean operations

for the definition of true and false); then that suite is executed

(and no other part of the "if" statement is executed or evaluated).

If all expressions are false, the suite of the "else" clause, if

present, is executed.

Related help topics: TRUTHVALUE 

When the output of help is too long, a -- More -- prompt is displayed at the bottom of the page: 

> >> help("for")

The "for" statement

*******************

The "for" statement is used to iterate over the elements of a sequence

(such as a string, tuple or list) or other iterable object:

   for_stmt ::= "for" target_list "in" expression_list ":" suite

                ["else" ":" suite]

The expression list is evaluated once; it should yield an iterable

object.  An iterator is created for the result of the

......

-- More  -- 

Press the enter key of the keyboard to continue browsing. When the q key of the keyboard is pressed, the help mode will be exited. Execute help () directly in the interactive mode. When no parameters are passed, it will enter the help mode. After entering the help mode, directly enter the property name or object name to be checked to perform the corresponding search. Execute the quit command in the help mode to exit the help mode. 

(2) Object name 

Help (object name) 

Object name parameters can be global variables built into Python, function names, imported module names, or user-defined object names (variable names, function names, etc.). Check the usage of the built-in function print in interactive mode: 

> >> help(print)

Help on built-in function print in module builtins:

print(...)

    print(value, ..., sep=' ', end='\n', file=sys.stdout, flush=False)

    Prints the values to a stream, or to sys.stdout by default.

    Optional keyword arguments:

    file:  a file-like object (stream); defaults to the current sys.stdout.

    sep:   string inserted between values, default a space.

    end:   string appended after the last value, default a newline.

    flush: whether to forcibly flush the stream. 

##  6.5.5 exit interactive mode 

Execute the exit () or quit () function in interactive mode to exit interactive mode. 

D:\>Python

Python 3.7.6 (tags/v3.7.6:43364a7ae0, Dec 19 2019, 00:42:30) 

[MSC v.1916 64 bit (AMD64)] on win32 Type "help", "copyright", "credits" 

or "license" for more information.

> >> exit()

D:\> 

##  Learn Python 6.5.6 System 

>  Fries Teacher Profile: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. Fries Teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning 

