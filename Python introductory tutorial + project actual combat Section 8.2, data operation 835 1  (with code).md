directory 

8.2.1 understand data crunching 

8.2.2 Operators and Operands 

8.2.3 Data Computing in Python 

8.2.4 integration and prioritization 

8.2.5 knowledge points 

Learn Python 8.2.6 System 

##  8.2.1 understand data crunching 

The common four operations are a kind of data operations, which can be used to add, subtract, multiply and divide more than two numbers. Comparing the size of two or more values is also a kind of data operation. In Section 8.1, data types and their classification are introduced. In data operations, the types of operations can also be classified. According to the different properties of data operations, they can be divided into arithmetic operations, relational operations, and logical operations. 

>  Whether it is arithmetic operations, relational operations, or other types of operations, it is the process of representing and processing data according to specific logical rules. For example, in Equation 1 + 1 = 2, the result of adding two things is represented by the character 2. 

![avatar]( cb817268cada4f7a0b026c5df6114907.png) 

>  The reason why 1 + 1 is equal to 2 is that we first have the experience of adding things together, and then express this process of arithmetic logic in the form of numerical symbols. 

##  8.2.2 Operators and Operands 

In short, operators are symbols that represent various types of data operations, such as addition with the symbol + and subtraction with the symbol -. Operands are numbers that participate in data operations, and operands can be divided into left and right operands according to their positional order. For example, in the arithmetic operation 1 + 2, both the number 1 and the number 2 are operands, 1 is the left operand, and 2 is the right operand. 

##  8.2.3 Data Computing in Python 

Data operations in Python mainly include assignment operations, arithmetic operations, relational operations, logical operations, member operations, and identification operations. 

(1) Assignment operation 

Assignment operation refers to the process of assigning a value to a variable, which is defined by assignment operation in Python. The assignment operator in Python is "=", and the operand to the left of the assignment operator must be a variable. 

Code example - define a boolean variable: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957453832
 ```  
Code explanation: 

>  When defining a boolean variable, it is usually prefixed with is to indicate whether or not. For example, the variable is_happy, which means whether or not it is happy. are you happy? 

The author reiterates that a variable in Python is a container that stores a memory address, and the process of assigning a value is essentially assigning the memory address of the value to the variable. 

(2) Arithmetic operations 

Arithmetic operations are addition, subtraction, multiplication and division. Arithmetic operators in Python: 

![avatar]( 295a7d01b2514cf70774bd7eca59e387.jpeg) 

Code Example - Calculates the bits of a number: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957453832
 ```  
Code explanation: 

>  (1) Divide the number by the base number of each digit to obtain the number of the current digit, for example, the base number of thousand digits is 1000, the base number of hundred digits is 100, the base number of ten digits is 10, and so on. Divide 2020 by 1000, and the result is 2, which is obviously the number of thousand digits.

(2) Perform a remainder operation between a number and the base of the digit to obtain the number of the next digit. For example, 2121 and 1000 perform a remainder operation, and the remainder is 121. If the remainder is less than the base of the digit, then the number of that digit is 0. For example, 2020 and 1000 perform a remainder operation, and the remainder is 20, and 20 is less than 100, then the number on the hundred digit is 0. Arithmetic operations and assignment operations can be combined. 

Code example - Compound operations for arithmetic operations: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957453832
 ```  
Code explanation: 

>  (1) defines a number variable that points to the value 2.

(2) number **= 2 is equivalent to number = number ** 2. First, the value pointed to by number is exponentiated with 2, and then the memory address of the calculated result is assigned to the variable number. 2 is a power of 2, and the result is 4.

(3) Other arithmetic operations can also be combined with assignment operations, and so on. 

(3) Relational operations 

Relational operations, as the name suggests, compare the size of a value. The result of a relational operation is of type Boolean. Arithmetic operators in Python: 

![avatar]( cd49b11a482ecf53959512052ff0beb1.jpeg) 

Code Example - Calculates the bits of a number: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957453832
 ```  
Code explanation: 

(1) Compared with the code examples in arithmetic operations, there are more conditional judgments to determine whether the remainder is greater than or equal to the base number of digits

(2) If the remainder is greater than or equal to the base, then perform an integer division operation with the base to obtain the number on the digit. If the remainder is less than the base, then the number of the current digit is 0 

(4) Logical operations 

Logical operation is to evaluate the true and false of the logical value of an expression. Logical operators in Python: 

![avatar]( 95b1a50d38671265a872f7ccacda428e.jpeg) 

In a logical AND operation, the result is true only if the values of the operands are true. In a logical OR operation, as long as one of the operands' values is true, the result is true. Not represents a logical NOT operation, that is, the opposite of a condition. Either true or false is true, and the output is True or False, representing true or false respectively. 

Short circuit logic of logical operations 

Short-circuit logic, that is, when performing logical operations, once the short-circuit logic condition is met, the logical operation behind the expression will be stopped immediately. The short-circuit logic condition here, that is, as long as one of the operands in the logic and operation is false, a short circuit will be triggered, and the output will be false. As long as one of the operands is true in the logic or operation, a short circuit will be triggered, and the output will be true. 

Code example - empty promise: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957453832
 ```  
Code explanation: 

(1) In the logical AND operation, as long as the value of one of the operands is false, a short circuit is triggered, and the last operand participating in the operation is returned

(2) In the expressions "and 201314 and False, the first operand is". "is an empty string with a false value, so a short circuit is triggered and the returned value is". 

Code example - interleaved lies: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957453832
 ```  
Code explanation: 

>  (1) In a logical OR operation, as long as the value of the operand is true, a short circuit is triggered, and the return value is the true operand.

(2) In the expression "or False or 201314 or 748, the first operand is". "is an empty string, the value is false, so the judgment will continue. The value of False is false, continue to judge. The value of 201314 is true, stop the operation immediately, and return 201314. 0 values of integer and floating-point types, empty string, False of boolean type, None type, these are all false values. 

(5) Member operations 

Member operations, as the name implies, determine whether an element is a member of a data set. 

Member operators in Python: 

![avatar]( 3cb53b147e627b894c278ad828c18399.jpeg) 

The in operator is explained again when introducing composite data types. 

(6) Identification operation 

The identification operation is to determine whether the identification values are equal, and the identification operation can be classified as a relational operation. 

Identification operators in Python: 

![avatar]( 1fe6da33c7c8bd06d501740cc04671b3.jpeg) 

The so-called identity value in CPython refers to the memory address (we use Python, usually CPython, CPython is an interpreter of the Python language), that is, to determine whether the operands have the same memory address, through the built-in function id to obtain the memory address of the operand. In Python, small integers and English short strings are cached in memory, so they have the same identity value. Python defaults to small integers between -5 and 256. English short strings are also cached, with a limited length of 20, and no spaces can appear between characters, otherwise they will not be cached in memory. 

Code example - I am not me: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957453832
 ```  
The output in interactive mode is: 

the man is not me 

The output in PyCharm is: 

the man is me 

When running a program in an IDE such as PyCharm, the Python interpreter will compile all the code in the file into intermediate bytecode at once, thus providing an opportunity for optimization. During the one-time compilation process, the Python interpreter stores the global constants in a fixed memory for other objects to refer to, so when running in PyCharm, the id value is equal. In interactive mode, every time the enter key is pressed, a compilation is triggered. 

Code example - I am of course me: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957453832
 ```  
The program output is: 

the man is me 

Code explanation: 

(1) Relational operations compare whether the values are equal, the characters "I" and "I", their values are equal, so the code below the if statement colon is executed 

##  8.2.4 integration and prioritization 

Associativity refers to the order of operations. The associativity of data operations mainly includes left associativity and right associativity. Left associativity refers to operations performed from left to right, and right associativity is operations performed from right to left. In Python, assignment operations are right associativity, and other operations are left associativity. 

Code Example - Continuous Assignment of Variables 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957453832
 ```  
Code explanation: 

(1) The associativity of the assignment operation is from right to left, so the first calculation is z = 2, which defines the variable z and points to the value 2.

(2) Then the value pointed to by the variable z is reassigned to the variable y, the value pointed to by y is also 2, and the value pointed to by the variable x is also 2. 

Priority refers to which operation is performed first when there are multiple operators in a data operation. In the four operations, multiplication and division operations are performed first, followed by addition and subtraction operations. 

Code example - simple four operations 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957453832
 ```  
Code explanation: 

(1) Multiplication has the highest priority, preferentially calculates 2 * 3, the result is 6, and then calculates the value of 1 + 6-4

(2) Addition and subtraction have the same precedence, so the result of computing 1 + 6 first is the same as computing 6-4 first, and the final value is 3. 

You can sort the various operations in Python by priority: 

Arithmetic Operations > Relational Operations > Identification Operations > Member Operations > Logical Operations > Assignment Operations 

When performing data operations, the priority of the operation can be enforced by the () symbol, that is, the priority enclosed by () is the highest. 

Code examples -all are lies: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957453832
 ```  
Code explanation: 

>  (1) First evaluate the value of the expression in ().

So the expression in the if statement is equivalent to True and False or False

(3) and has the same precedence as or. Calculate according to left associativity, first calculate True and False, the value is False. Finally, the expression False or False is evaluated, and the value is False. 

##  8.2.5 knowledge points 

>  (1) Operators are symbols that represent various types of data operations, and operands are numbers that participate in data operations

(2) Data operations in Python mainly include assignment operations, arithmetic operations, relational operations, logical operations, member operations, and identification operations

(3) In Python, variables are defined by assignment operations, and the operand to the left of the assignment operator must be a variable

Variables in Python are containers that store memory addresses

(5) Arithmetic operations and assignment operations can be combined into composite operations, and identification operations and logical non-operations can be combined into composite operations

(6) In the logical AND operation, as long as one of the operands is false, the operation is stopped and the last operand participating in the operation is output. In the logical OR operation, as long as one of the operands is true, the calculation is stopped and the last operand participating in the operation is output

(7) In Python, assignment operations are right associative, and other operations are left associative

(8) When performing data operations, the priority enclosed by () is the highest 

##  Learn Python 8.2.6 System 

>  Fries Teacher Profile: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. Fries Teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning 

