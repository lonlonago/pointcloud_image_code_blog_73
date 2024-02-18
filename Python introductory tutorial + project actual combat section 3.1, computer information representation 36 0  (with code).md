directory 

3.1.1 understand information representation 

3.1.2 understand binary notation 

3.1.3 information storage in computers 

3.1.4 knowledge points 

3.1.5 system to learn Python 

##  3.1.1 understand information representation 

The so-called information representation refers to expressing the meaning of information through certain things or logical concepts. Writing is an important information representation, through which the splendid culture of human civilization can be inherited. 

>  Since the invention of writing, human civilization has been calculated for less than 6,000 years. In these thousands of years of human history, humans have created a splendid human civilization through the dissemination of writing and other means. 

As the inventor and user of words, it is a very natural way for humans to represent and convey information through words. But in computers, information cannot be represented through words because machines cannot understand words. Computers are made up of logic circuits, and logic circuits usually have only two physical states: the "on" state and the "off state. These two states can be represented by the numbers 1 and 0, using 1 to represent the open state and 0 to represent the closed state. This method of representing information using the numbers 1 and 0 is called binary notation. 

![avatar]( 8d7588601a156368b9891e9f75237c50.png) 

So, why can this binary representation represent information? As a simple example, we use words to describe a piece of information as follows: 

I Love You 

Since computers can only recognize binary, in order for the computer to "understand" this text, we can use the following binary instead: 

![avatar]( e73c2bc183855f58d22bf7197b21048c.jpeg) 

Then the binary representation of "I love you" in a computer is: 

00 01 11 

##  3.1.2 understand binary notation 

(1) The concept of base is a counting method with carry. The most common counting method in life is the decimal representation. In this counting method, the base number is 10, and there are 10 basic number symbols: 

![avatar]( 909876318c2763508793c123ff41d0bb.jpeg) 

>  In the base notation method, the base N indicates that the base number in this type of notation is N, and there are N basic number symbols. Due to the simplicity and practicality of Arabic numerals, Arabic numerals are used as basic number symbols in most cases. 

The so-called "carry" refers to when the value exceeds the largest number sign in the base system, it is advanced by one to the high position. For example, the largest number sign in the decimal system is 9, and the number after carrying the high position becomes 10. The carry process can be broken down into the following three steps: 

(1) The number exceeds the maximum number symbol 9 and is carried to the upper position, changing the number from 1 digit to 2 digits 

(2) Since it is advanced to the high position, the high position is 1, and the low position has been carried. Continue to count from 0 

(3) From (1) and (2), the carried number is 10. 

Other binary counting methods are based on the same principle as decimal counting methods. For example, in the binary counting method, the base number is 3, and there are three basic digital symbols: 

![avatar]( 8c1459f24f5047d9ba12014f9627c245.jpeg) 

The largest digit sign in binary is 2, so the carried forward digit becomes 10. The carry process can be broken down into the following three steps: 

(1) The number exceeds the maximum number symbol 2 and is carried to the high position. The number changes from 1 digit to 2 digits 

(2) Since it is advanced to the high position, the high position is 1, and the low position has been carried. Continue to count from 0 

(3) From (1) and (2), the carried number is 10. 

The 10 in the decimal system is not the same size as the 10 in the ternary system, because its cardinality is different. When comparing the size of the base system, they can be converted to the decimal system for visual comparison. When converting other bases to decimal, you need to first grasp the concept of a weight. In the weight calculation of the base system, the weight of the Nth bit is to the Nth power of the base number. For example, in the ternary system, the base number is 3, then the weight of the 0th bit is 3 to the power of 0, and the weight of the first bit is 3 to the power of 1. 

>  Because the high number is carried from the low number, in the process of carrying the base number in the base for carry, this is the so-called concept of weight. 

To convert to decimal, you need to multiply the digits of the digits with the weights and then sum them. Then, the value after converting 10 in binary to decimal is: 

![avatar]( 003ecd151683c3c8dfd888019c65aad0.jpeg) 

(2) Binary and hexadecimal As can be seen from the 3.1.1 section, computers use binary to represent information. In binary counting, the base is 2, and the size after binary 10 is converted to decimal is: 

![avatar]( 9999be8f17c2ad7981287601904cd42c.jpeg) 

In computer systems, hexadecimal is also a very common representation of information. In hexadecimal, the base number is 16, and the first 10 digits are still Arabic numerals, but starting from 10, the letters A to F in the English alphabet are used instead. For example, 10 in hexadecimal is replaced by the letter A, 11 is replaced by the letter B, and so on. The first ten symbols of hexadecimal: 

![avatar]( f94599a4979d6d709b634922f3ef11a0.jpeg) 

The last six symbols of hexadecimal: 

![avatar]( 3259d926c74a468a5bf9e5a6ee70be58.jpeg) 

>  The hexadecimal is case-insensitive, and in programming languages, numeric constants starting with 0x or 0X are typically used as hexadecimals, such as 0x123F. 

Computers can only recognize binary, and when processing hexadecimal data, they need to convert it to binary for processing. For humans, the easiest to understand is decimal, but the conversion between decimal and binary is very troublesome, and the binary counting method is very verbose. For example, to represent a binary number with decimal value of 255, you need to use eight binary numbers: 

11111111 

In hexadecimal, a hexadecimal number can represent a four-digit binary number, such as a four-digit binary number 1111, which can be represented by hexadecimal F. The corresponding decimal of F is 15, and the value of the binary number 1111 is exactly 15: 

![avatar]( cc504ddb6acc9daccce794035ffad17f.jpeg) 

Therefore, when representing information, hexadecimal is often used as a compromise. 

(3) The mutual conversion between bases converts decimal integers into other bases, mainly using the method of "dividing the base and taking the remainder, and then arranging in reverse order". The specific calculation process: 

1. Divide the decimal integer by the base to get a quotient and the remainder 

2. Divide the quotient by the base and you will get another quotient and the remainder 

3. Repeat step 2 until the quotient is less than 1. 

4. Rank the remainder of the calculation in order from low to high 

Take the decimal 5 to binary as an example: 

1.2 Divides 5 to get the quotient 2 and the remainder 1. 

2.2 Divides the quotient 2 to get the quotient 1 and the remainder 0. 

3.2 Divide the quotient 1 to obtain the quotient 0 and the remainder 1. 

4. Arrange the remainder in reverse order during the calculation, then the binary is: 101 

The result of converting binary 101 to decimal is exactly: 

![avatar]( a6b23e15cfc13a531c7d0e0b09667b51.jpeg) 

>  The decimal decimal to other decimal systems uses the method of "multiplying the base to round and then arranging in sequence", that is, taking the integer part each time, and then multiplying the decimal part with the base to repeat the process. 

##  3.1.3 information storage in computers 

Modern computers are based on the von Neumann system. In the von Neumann system, computer hardware consists of five parts: arithmetic units, controllers, memory, input devices, and output devices. The von Neumann system is shown in the following figure: 

![avatar]( 04c4a77a47155556b9f42e7724b5f716.png) 

The memory is responsible for storing information, and the computer system treats the memory as a large array of bytes, numbered sequentially starting from 0 in this byte array. 

![avatar]( a7e4210407dc6d2118e647ac2ec3efb4.jpeg) 

The byte number here is the "address". 

A computer treats a byte as the smallest addressable unit of memory and a string of binary digits for information processing. In a computer, a byte contains eight binary digits, and its maximum size is: 

11111111 

Converted to decimal size: 

![avatar]( 0d80e5dd3f099b63d40f71cc207f51ed.jpeg) 

##  3.1.4 knowledge points 

>  (1) Information representation refers to expressing the meaning of information through something or a logical concept. In human civilization, words are a very important way of expressing information. (2) In computers, information is represented and stored through binary. (3) Computers are composed of logic circuits. Logic circuits usually have only two physical states: the "on" state and the "off" state. These two states can be represented by numbers 1 and 0, using 1 to represent the open state and 0 to represent the closed state. (4) In the base notation method, the base N indicates that the base number in this type of notation is N, and there are N basic number symbols. For example, in the decimal system, the base number is 10, and there are 10 basic number symbols. (5) Converting decimal integers to other digits mainly uses the method of "dividing the base number and then arranging in reverse order". When converting other digits to decimal, you need to first grasp the concept of weights. Converting other digits to decimal requires multiplying the digits and weights before summing. 

##  3.1.5 system to learn Python 

>  Fries Teacher Profile: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. Fries Teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning 

