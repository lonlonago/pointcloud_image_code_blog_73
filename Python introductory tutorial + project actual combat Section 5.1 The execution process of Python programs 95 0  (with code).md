directory 

5.1.1 execute Python programs on the command line 

5.1.2 Python files are text files 

5.1.3 Python is an interpreted language 

5.1.4 the execution of Python programs 

5.1.5 system to learn Python 

##  5.1.1 execute Python programs on the command line 

The basics of the Windows command line and Linux command line are covered in Chapter 4. After Python is successfully installed and added to environment variables, Python programs can be executed directly from the command line. 

CentOS8 has built-in python3 interpreter, no need to install. CentOS8 built-in Python interpreter, its version is 3.6.8

Executing the python3 command on the command line can enter the interactive mode of python, and executing the exit () function in the interactive mode can exit the interactive mode. 

The author's teaching environment is the Windows 10 system, and readers do not need to worry about the portability of Python programs on various platforms. Cross-platform is one of the important features of the Python language. Python programs written in the Windows system can be run directly in the Linux. Now please refer to the following steps to execute Python programs on the command line: 

(1) Enter the python3-learning directory and create hellopython.py 

Go to the python3-learning directory of the D disk and create hellopython.py file in this directory. The code in the program is very simple, only one line: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957459812
 ```  
Print is a built-in function in Python that is used to output values. 

(2) Enter the command line and switch to the python3-learning directory of the D disk 

Students who are not familiar with the basics of the Windows command line can review the learning content in Chapter 4 first. 

(3) Execute hellopython.py on the command line 

Execute python hellopython.py directly from the windows command line: 

![avatar]( 4d4fb7174877476562c3b3b432253c01.png) 

From the output of the program, the Python interpreter successfully executes the script hellopython.py and outputs the content to the screen. 

##  5.1.2 Python files are text files 

hellopython.py we wrote in the previous section, it is a text file. The so-called text file refers to a file composed of text characters. 

>  Files in a computer are mainly divided into text files and binary files. In text files, text characters are stored. In binary files, information is directly stored in binary form. Pictures, audio & video files are a kind of binary file. When you open a binary file directly with a text editor such as Notepad, you will see a bunch of garbled characters. English letters, Chinese characters, etc. are characters we often use. Humans can understand characters, but computers cannot. Computers can only recognize binary. In order for computers to recognize characters, we need to encode characters using numbers, and then convert the number encoding to the corresponding binary. 

Taking hellopython.py as an example, what we see is: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957459812
 ```  
But what the computer "sees" is: 

>  \u0070\u0072\u0069\u006e\u0074\u0028\u0022\u0068\u0065\u006c\u006c\u006f\u0020\u0070\u0079\u0074\u0068\u006f\u006e\u0022\u0029 

The\ u prefix indicates that it is encoded according to the unicode encoding, and the number after\ u indicates the hexadecimal encoding corresponding to the character. 

For example, the unicode encoding corresponding to the character p is p, and 0070 is a hexadecimal, which converts to decimal: 

![avatar]( ccabbe524be254d9beaae302c095065f.jpeg) 

The converted binary of hexadecimal 70 is: 

01110000 

Students who are not familiar with the concept of base and conversion can review the learning content in Section 3.1 first. 

Compared to decimal, hexadecimal is easier to convert to binary, and 1 hexadecimal corresponds to 4 binary digits. In the four-digit binary, when each digit is 1 from the highest digit to the lowest digit, it corresponds to 8, 4, 2, and 1 in the hexadecimal, respectively. 

Converted to the corresponding hexadecimal, you can add it directly, such as 1111. The result after direct addition is: 8 + 4 + 2 + 1 = 15, and the converted hexadecimal is F. 

Hexadecimal 7 (4 + 2 + 1), the corresponding binary is 0111, and the corresponding binary of hexadecimal 0 is 0000.

The binary corresponding to hexadecimal 70 is 01110000. 

What the computer eventually "sees" is a bunch of binary code: 

>  01110000011100100110100101101110011101000010100000100010011010000110010101101100011011000110111100100000011100000111100101110100011010000110111101101110001000100010100100001010 

In the binary content above, 1 byte is used as a group, and 1 byte contains 8 binary bits. Interested readers can convert the hexadecimal of the character to the corresponding binary by themselves. 

##  5.1.3 Python is an interpreted language 

Python is an interpreted language. When executing a Python program, Python first translates all the content in the script file into Python bytecode, and then interprets and executes the bytecode instructions linearly, from top to bottom. 

>  At this point, the bytecode is not a machine instruction. In the process of interpreting and executing the bytecode by the Python interpreter, each bytecode instruction must eventually be translated into a machine instruction, that is, a binary instruction, so that it can be run in a computer. 

##  5.1.4 the execution of Python programs 

The instructions and data in the Python program are eventually loaded into memory, from which the CPU reads and executes the Python bytecode translated machine instructions. hellopython.py the code in the file: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957459812
 ```  
The print function in the code is translated into machine instructions, while the "hello python" in the code is the data in the program. 

As a very simple example, suppose that the print function is finally translated into machine instructions A and B. The A instruction is responsible for reading data from memory, and the program data read here is: "hello python". After the A instruction is executed, the data is loaded into the registers in the CPU. 

The B instruction is responsible for writing the data "hello python" in the register to the output device. After the B instruction is executed, we finally see the output of the program on the screen: 

![avatar]( 9b2feb3de1d0c2835251ed0ccd6893f4.png) 

##  5.1.5 system to learn Python 

>  Fries Teacher Profile: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. Fries Teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning 

