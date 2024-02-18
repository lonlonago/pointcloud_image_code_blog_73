directory 

9.2.1 string common operators 

9.2.2 + operator: concatenate string 

9.2.3 * operator: string multiplication 

9.2.4 [] operator: index access 

9.2.5 [:] operator: sharding string 

9.2.6 in operator: find substring 

9.2.7% operator: format string 

9.2.8 knowledge points 

Learn Python 9.2.9 System 

##  9.2.1 string common operators 

The string type is an abstract data type. The abstract data type defines the operation method of the data type. In this section, we focus on manipulating strings through operators. 

![avatar]( c1b7ba79cf75c516ace0d3e1412963e7.png) 

The commonly used operators for the string type are shown in the following table: 

![avatar]( 9673b2628a1b617c322d82d786245d8b.jpeg) 

##  9.2.2 + operator: concatenate string 

The + operator is used to implement the concatenation function of strings, returning the concatenated string. 

Operation syntax: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574555870
 ```  
Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574555870
 ```  
##  9.2.3 * operator: string multiplication 

The "*" operator is used to repeatedly output a string and return a new string. For example, if string chips is repeated 3 times, the new string is chipschipschips. 

Operation syntax: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574555870
 ```  
Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574555870
 ```  
##  9.2.4 [] operator: index access 

The string type is a linear sequence structure that allows access to each element in the data collection through an index. 

Operation syntax: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574555870
 ```  
Index represents an index. In Python, the index value must be an integer number. Indexes in Python are divided into positive and negative indexes. Positive indexes are numbered from 0. For example, in the string "I have always loved you", the number 0 corresponds to the character'I ', the number 1 corresponds to the character'one', and so on. Negative indexes mean counting from the end and numbering from -1. For example, -1 means accessing the penultimate one, and -2 means accessing the penultimate one. Positive and negative index values must be within the valid range, otherwise an exception message to access out-of-bounds will be thrown. Students take a look at the sequential table structure shown in the figure below to deepen their understanding of indexes: 

![avatar]( d3e18c13fe5d4350b51a14de13b51669.jpeg) 

In the figure, the index value corresponding to the character'I 'is 0, the index of the character'one' is 1, the positive index of the character'you 'is 6, the negative index is -1, the positive index of the character'with' is 5, the negative index is -2, and so on. The effective range of a positive index is [0,6], and the effective range of a negative index is [-7, -1]. Students can draw inferences from one example. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574555870
 ```  
##  9.2.5 [:] operator: sharding string 

Use the sharding operator to slice the string, pass the index value before and after, the so-called slicing is to truncate the content between the front index and the back index, and the index interval follows the principle of closing left and opening right. 

Operation syntax: 

(1) The operation syntax is [front index: back index], for example [0:5], which means to intercept the value between index 0 and index 5 (excluding index 5)

(2) The value of the previous index can be left blank, [: post index], at which time the value of the previous index is equal to 0

(3) The value of the post-index can be left blank, [pre-index:], in which case the value of the post-index is equal to the length of the string

(4) The values of the index before and after can be left blank at the same time, [:], at which time the value of the index before is equal to 0, and the value of the index after is equal to the length of the string. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574555870
 ```  
##  9.2.6 in operator: find substring 

In Python, "in" is a member operator that is used in strings to find whether a substring exists in the main string. If there is a return value of Boolean type True, otherwise it returns False. "Not in" is the opposite of "in", that is, it indicates whether the substring does not exist in the main string, and the return result is a Boolean type. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574555870
 ```  
##  9.2.7% operator: format string 

In Python, strings are formatted using the "%" formatting operator, which is explained in detail in Section 9.4. 

##  9.2.8 knowledge points 

(1) String is an abstract data type

(2) String is a linear sequence structure that can be accessed by indexing characters

(3) Positive indices in the sequence structure are numbered from 0, and negative indices are numbered from -1

(4) String is a static data type and cannot be modified

##  Learn Python 9.2.9 System 

>  About the French fries teacher: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. French fries teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning, quantitative investment. 

