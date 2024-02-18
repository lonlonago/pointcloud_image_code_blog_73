directory 

9.1.1 understand string. 

9.1.2 type name of string 

Numeric encoding of 9.1.3 characters 

9.1.4 common character encoding 

Default encoding 9.1.5 string 

9.1.6 string encoding and decoding 

9.1.7 escape characters 

9.1.8 traverse string 

9.1.9 knowledge points 

Learn Python 9.1.10 System 

##  9.1.1 understand string. 

To understand a string, you must not only know what it is, but also its underlying data structure. 

So, what is a string? 

In Python, all strings are enclosed in English quotation marks, and the following are strings: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574512989
 ```  
![avatar]( 0385bb53fadeba7acb2099248b2f42fb.png) 

String is a linear sequence structure. To understand this data structure, look directly at the diagram: 

![avatar]( fbc26b273c09e8a5ed61300b4e9884e2.jpeg) 

The above figure represents the string "I have always loved you". It can be seen from the figure that the relationship between characters is a straight line, the characters are arranged in sequence, and all the character spaces correspond to a continuous memory. This structure is called a linear sequence structure. Each cell in the figure represents a memory block, and the memory block stores the digital encoding of the characters. 

With this linear sequence structure, each element in the data set can be accessed through an index. In Python, indices are numbered from 0. For example, the number 0 corresponds to the character'I ', the number 1 corresponds to the character'one', and so on. 

>  Interested students can systematically learn the course of data structures. To become an excellent programmer, you must master the knowledge of data structures. The French fries teacher will launch a series of data structures in the later tutorial. 

##  9.1.2 type name of string 

In interactive mode, type to output the type name of a string: 

> > > chinese = "I love you"

> >> english = 'I Love You'

> > > english = "'I love you"'

> > > russian = "" i love you "" "

> >> type(chinese)

<class 'str'>

> >> type(english)

<class 'str'>

> >> type(japanese)

<class 'str'>

> >> type(russian)

<class 'str'> 

From the output, the type of string is named str. 

##  Numeric encoding of 9.1.3 characters 

In the third chapter, it has been introduced that computers can only process binary, and in order for computers to process characters, characters need to be encoded. The so-called encoding refers to the representation of characters by numbers. Different representations correspond to different character encodings. 

Through the built-in function ord in Python, the decimal digit code of a character can be obtained. Using the basic syntax of the ord function: 

ord(character) 

The character parameter represents a specific character, and the return value is the decimal digit encoding of the character. Enter interactive mode to verify: 

> > > ord ('love')

29233 

Through the built-in function chr in Python, you can get the corresponding character of the numeric encoding. Use the basic syntax of the chr function: 

chr(code) 

The parameter code represents the numeric encoding of the character, and the return value is the character of the numeric encoding. Enter the interactive mode to verify: 

> > > chr (29233)

"Love." 

##  9.1.4 common character encoding 

The earliest character encodings were ASCII, which used a single byte to represent a character. The range of energy-saving representations for a word was 0-255, meaning that this encoding could only represent up to 256 characters. ASCII could not represent other characters such as Chinese characters, and in order to meet the needs of other regions, multi-byte encodings appeared. 

China initially developed the GBK encoding, which used two bytes to represent commonly used Chinese characters. Other regions have also developed different encodings to represent their own character sets.

In order to standardize and unify the coding of various regions, the UNICODE code appeared. At the beginning of its formulation, the UNICODE code used two bytes to represent a character. 

(1) ASCII 

ASCII code, the full name of the American Standard Code for Information Interchange, is a scheme that uses 7 or 8 binary bits for character encoding, and can contain up to 256 characters. The basic ASCII character set has a total of 128 characters, including 96 printable characters, including commonly used letters, numbers, punctuation, etc., and 32 control characters. The following picture shows the code table of ASCII characters: 

![avatar]( 570ba18fe8266516ede57a8473a6a5cc.png) 

(2）UNICODE 

In the UNICODE encoding, a uniform and unique binary encoding is set for each character in each language, which ranges from 0x000000 to 0x10FFFF. Each character corresponds to a unique UNICODE numeric code. The UNICODE encoding is in the form of U + in front of the numeric code (hexadecimal). For example, the UNICODE for "love" is U + 7231. 

(3) UTF-8 

UTF-8 is a variable-length character encoding for UNICODE. Unlike UNICODE, which uses a fixed-length number of bytes to represent characters, UTF-8 uses a variable number of bytes, such as ASCII characters. In UTF-8, one byte is still used for encoding, and 3 bytes are used for encoding characters such as Chinese characters. 

(4) GBK 

GBK encoding is a Chinese character encoding character set, using single and double-byte variable-length encoding, English characters use single-byte encoding, which is fully compatible with ASCII codes, and Chinese parts use double-byte encoding. 

##  Default encoding 9.1.5 string 

Strings in Python are encoded in UNICODE by default, that is, strings in Python are UNICODE strings. 

##  9.1.6 string encoding and decoding 

With the encode method of the string type, you can get the type of bytecode of the string encoded in a specific encoding. 

Basic syntax using the encoding method: 

str.encode(encoding) 

The parameter encoding represents the encoding method of the character, and the return value is the type of bytes. Through the decode method of the bytecode type, the bytecode type can be converted to a UNICODE string. 

Basic syntax for using the decode function: 

bytes.decode(encoding) 

The parameter encoding represents the encoding method of the character, and the return value is of type str. 

Code example - encoding and decoding strings 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574512989
 ```  
Code explanation: 

(1) Pass the parameter'gbk 'to get the bytecode type encoded by gbk

(2) Pass the parameter'ascii 'to get the bytecode type encoded by ascii

(3) Pass the parameter'unicode-escape 'to get the bytecode type encoded in unicode

(4) Pass the parameter'utf-8 'to get the bytecode type encoded by utf-8 

When decoding with a bytes type, the encoding must be compatible, otherwise an exception message of an encoding error will be thrown. 

Verification can be done in interactive mode: 

> > > gbk _ code = chinese.encode ('gbk')

> >> gbk_code.decode('ascii')

Traceback (most recent call last):

File "<stdin>", line 1, in <module>

UnicodeDecodeError: 'ascii' codec can't decode byte 0xce in position 0: 

ordinal not in range(128) 

In interactive mode, pass gbk to get the type of bytecode that gbk encodes, but pass ascii when decoding. The ascii encoding is incompatible with the gbk encoding, so an exception is thrown. 

##  9.1.7 escape characters 

Escape characters in programming languages are special characters composed of the backslash symbol '\' + characters. Escape characters are usually used to represent characters defined in the character set, such as newlines in the ASCll character set. 

The following table is a list of commonly used escape characters: 

![avatar]( 20b79f785757f4ebf10fb8e99278f2c4.jpeg) 

You can avoid ambiguity by using escape characters, such as the escape character\ "to represent a string containing quotation marks: 

"\"" 

If there are no escape characters, the system cannot determine whether the user has defined a quoted string or a three-quote string. 

You can also use quotes to enclose other forms of quotes to represent quotes-containing strings, such as double quotes: '"' inside single quotes, and single quotes:" '"inside double quotes. 

Using escape characters, you can also implement some useful features. 

(1) Use newline characters to output multiple lines 

> > > chinese = "I\ nlove\ nyou\ n"

> >>print(chinese)

i

Love

you 

(2) Output horizontal tab 

> > > chinese = "I\ t love\ t you\ t"

> >> print(chinese)

I love you 

In certain application scenarios, it is necessary to prohibit the escape of character pairs. This function can be achieved by prefixing the string with r. 

> > > chinese = r "\ t\ t\ t"

> >> print(chinese)

I\ t love\ t you 

When a string contains a path, it is useful to prevent Python from escaping it: 

> >> file_path = "D:\nosql\data"

> >> print(file_path)

D:

osql\data 

The output is obviously problematic. Python interprets the\ n character in the string as an escape character. In this case, you can add the r prefix to the string to prevent Python from escaping the character. 

> >> file_path = r"D:\nosql\data"

> >> print(file_path)

D:\nosql\data 

##  9.1.8 traverse string 

A string is a linear sequence structure that can be iterated over all characters in a string through a for loop. 

Code example - iterate through the characters in the string one by one: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574512989
 ```  
Code explanation: 

(1) Traversal of strings is performed according to the order of characters

(2) By analyzing the output of the program, we can better understand the linear sequence structure of string. 

##  9.1.9 knowledge points 

(1) Strings are enclosed in English quotation marks in Python

(2) String is a linear sequence structure 

(3) The type name of string is str

(4) The so-called encoding refers to the use of numbers to represent characters. Different representation methods correspond to different character sets.

(5) Common character sets include ascii character set, unicode character set, utf-8 character set, and gbk character set

(6) String in Python defaults to UNICODE string 

##  Learn Python 9.1.10 System 

>  About the French fries teacher: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. French fries teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning, quantitative investment. 

