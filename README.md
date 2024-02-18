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



--------------------------------------------------------------------------------

directory 

10.3.1 list common operation method 

Adding 10.3.2 List 

Search 10.3.3 List 

Modification of 10.3.4 List 

Removal of 10.3.5 List 

10.3.6 other operations related to lists 

10.3.7 knowledge points 

Learn Python 10.3.8 System 

##  10.3.1 list common operation method 

List type is an abstract data type. Abstract data type defines the operation method of data type. In this section, we focus on the common operation method of list type. 

##  Adding 10.3.2 List 

Function description: 

>  The data object represented by the parameter object is added to the list, and the element is added to the end of the list. This method has no return value. When defining an empty list, elements cannot be added by index. Adding new elements requires the list addition method described in this section. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574549933
 ```  
Function description: 

>  The index parameter indicates the index value, and the insert method is used to insert the element at the previous position of the index. If the value of index is greater than the largest index in the list, it is equivalent to executing the append method.

The append method adds an element to the end of the list each time, and the insert method inserts the element at the specified position. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574549933
 ```  
Function description: 

>  Adds an iterable object to the end of the list with no return value. The extend method only accepts iterable objects and adds the elements of the iterable object to the list one by one. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574549933
 ```  
Any iterable object that can iterate through the elements of a data collection one by one. The iterable types learned so far are string and list. 

##  Search 10.3.3 List 

Function description: 

>  Checks whether an element exists in the lookup table. If it exists, the index of the element will be returned. If it does not exist, an exception will be thrown. Start indicates the starting position of the lookup, and stop indicates the end position of the lookup (closed interval, excluding stop). 

The default value for start is 0, and the default value for end is the length of the list. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574549933
 ```  
Function description: 

>  Finds the number of times the element value value appears in the list, and returns 0 when the element value value does not exist. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574549933
 ```  
Now write a simple code example to implement the function of the count method through a loop structure. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574549933
 ```  
##  Modification of 10.3.4 List 

In Section 10.2, it is introduced that the value of a list element can be modified by the [] operator. Students should note that the index in [] must be within a valid range, otherwise an out-of-bounds error will be thrown. 

##  Removal of 10.3.5 List 

Function description: 

>  Delete the element value corresponding to the index index. The value of index defaults to the maximum index value of the list, that is, the pop method defaults to deleting the element at the end. The maximum index value of the list is the length of the list minus one. The return value is the deleted list element. The value of index must be within the valid index range of the list, otherwise an exception will be thrown. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574549933
 ```  
Students who are not familiar with the effective scope of an index can review the content in Section 9.2. 

Function description: 

>  Execute the remove method to directly remove the elements in the list without returning a value. Note: The remove method only removes the elements that match for the first time. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574549933
 ```  
Now write a simple code example to implement the function of the remove method through the loop structure and the slicing operation of the list. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574549933
 ```  
Function description: 

>  No parameters, no return value, one-click to clear all elements in the list. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574549933
 ```  
##  10.3.6 other operations related to lists 

Function description: 

>  The len method is a built-in method that returns the number of elements in a container data type. Compound data types in Python are data objects of a container class. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574549933
 ```  
Function description: 

>  Sort the list in place, using only the < operator to compare the values of the elements. If an exception occurs during the comparison, the sorting operation fails. The default value of the parameter key is None, which is used to pass a function with one argument. The sort method passes the list element to the function, and then compares it based on the output of the function. For example, key = len, then the sort method calculates the length of the list element, and then sorts according to the length. The parameter reverse is used to specify whether it is sorted in descending or ascending order. When reverse is False, it means ascending sorting, and when it is True, it means descending sorting. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574549933
 ```  
Function description: 

>  When all the elements in the list are of type string, the elements in the list can be formed into a string with str as the separator through the join method of string. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574549933
 ```  
##  10.3.7 knowledge points 

>  (1) When defining an empty list, elements cannot be added by index. Adding new elements requires the append method.

(2) The append method adds the data object as a whole, while the extend method adds the elements of the iterable object to the list one by one. 

##  Learn Python 10.3.8 System 

>  About the French fries teacher: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. French fries teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning, quantitative investment. 



--------------------------------------------------------------------------------

directory 

Introduction to 10.5.1 Sorting Algorithm 

10.5.2 Bubble Sort Algorithm 

Learn Python 10.5.3 System 

##  Introduction to 10.5.1 Sorting Algorithm 

The so-called sorting refers to arranging the elements in the data collection in order from small to large, or in order from large to small. The former is called ascending sorting, and the latter is called descending sorting. In this course on Data Structures and Algorithms, we will learn many sorting-related algorithms, such as Bubble Sort Algorithm, Select Sort Algorithm, Quick Sort Algorithm, Heap Sort Algorithm, etc. In this tutorial, we will master the very classic Bubble Sort algorithm. 

##  10.5.2 Bubble Sort Algorithm 

The principle of the bubble sort algorithm is very simple. The adjacent elements are compared in pairs, and the positions are swapped according to the relationship between ascending or descending order. For example, in ascending sort, the large bubble is placed at the back and the small one at the front. Compare n elements in pairs, and only need to compare n-1 times to find the most value. After finding the most value, the most value is automatically bubbled to the end of the interval, and then the next comparison is performed. The following figure shows the descending [3,2,1] list in ascending order using bubble sort: 

![avatar]( 603685e807bc23bbb66511e475a30b7c.png) 

According to the above principles, we now use the Python language to implement the Bubble Sort algorithm: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574554162
 ```  
##  Learn Python 10.5.3 System 

>  About the French fries teacher: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. French fries teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning, quantitative investment. 



--------------------------------------------------------------------------------

directory 

Common operation methods of 11.3.1 tuples 

Search for 11.3.2 tuples 

11.3.3 knowledge points 

Learn Python 11.3.4 System 

##  Common operation methods of 11.3.1 tuples 

Tuple type is an abstract data type. Abstract data type defines the operation method of data type. In the content of this section, the operation method of tuple type is emphasized. 

![avatar]( 57c5fef387f7740050623904dcb29d61.png) 

Tuples are an immutable data type that cannot be modified. The methods provided in tuples are mainly to look up elements. Lists are a mutable data type that can be modified by the operator []. The differences between tuples and lists are described in detail in Section 11.4. 

>  Performing operations such as slicing, adding, etc. on the tuple returns a new tuple without modifying the tuple. 

##  Search for 11.3.2 tuples 

(1) tuple.index(value, start=0, stop=2147483647) 

Function description: 

>  Find the index of the element value in the tuple. Start indicates the start position of the search, and stop indicates the end position of the search (closed interval, excluding stop). The default value of start is 0, and the default value of stop is 2147483647. 

When an element does not exist, an exception is thrown. When executing the index method, you can first use the in operator to determine whether the element is in a tuple. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574567766
 ```  
The function of the index method is implemented through a loop structure: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574567766
 ```  
(2) tuple.count(value) 

Function description: 

>  Finds the number of values in the list. Returns 0 if the value does not exist. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574567766
 ```  
The function of the tuple type count method can also be implemented through a loop structure: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574567766
 ```  
So far, we are in the loop structure by way of traversal to find elements, in the case of large data, the efficiency of the search will be very low. In the introduction of function processing, we will explain how to improve the efficiency of data search by binary search. 

##  11.3.3 knowledge points 

>  (1) A tuple is a static data type that cannot be modified. The methods provided in a tuple are mainly to find elements.

(2) A list is a dynamic data type that can be modified by the operator [] 

##  Learn Python 11.3.4 System 

>  About the French fries teacher: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. French fries teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning, quantitative investment. 



--------------------------------------------------------------------------------

directory 

Introduction to 11.5.1 Sorting Algorithm 

11.5.2 selection sorting algorithm 

Learn Python 11.5.3 System 

##  Introduction to 11.5.1 Sorting Algorithm 

The so-called sorting refers to arranging the elements in the data collection in order from small to large, or in order from large to small. The former is called ascending sorting, and the latter is called descending sorting. In this course on Data Structures and Algorithms, we will learn many sorting-related algorithms, such as Bubble Sort Algorithm, Select Sort Algorithm, Quick Sort Algorithm, Heap Sort Algorithm, etc. In this tutorial, we will master the very classic Select Sort algorithm. 

##  11.5.2 selection sorting algorithm 

The core idea of selection sorting is to select the smallest (large) element from the data set, store it at the beginning of the interval, and then find the smallest (large) element from the remaining unsorted elements, put it at the end of the sorted interval, and repeat this process until sorting is achieved. The following figure shows the process of selecting the minimum value of 1 to the header of the interval: 

![avatar]( 4f63b42a9dc786f9e1a9700cac78fceb.png) 

>  (1) In the initial case, assume that the minimum value is 3 and the minimum index is 0.

(2) Compare element 3 with element 2, 2 is smaller than 3, and update the minimum index to index 1 of element 2.

(3) Compare the element 2 corresponding to index 1 with the 1 at the end, 1 is smaller than 2, and update the minimum index to index 2 of element 1.

(4) Minimum index 2 is not equal to the initial minimum index 0, so elements 3 and 1 are interchanged. 

According to the above principles, we now use the Python language to implement the selection sorting algorithm: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574519517
 ```  
##  Learn Python 11.5.3 System 

>  About the French fries teacher: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. French fries teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning, quantitative investment. 



--------------------------------------------------------------------------------

directory 

Common operation methods of 12.2.1 dictionary 

12.2.2 dictionary search 

12.2.3 dictionary changes 

Adding 12.2.4 Dictionary 

Deletion of 12.2.5 Dictionary 

12.2.6 knowledge points 

Learn Python 12.2.7 System 

##  Common operation methods of 12.2.1 dictionary 

Dictionary type is an abstract data type. Abstract data type defines the operation method of data type. In this section, students are taught to thoroughly master the common operation method of dictionary type. 

![avatar]( e989e50ff9866e5c7d0fb687da752118.png) 

The commonly used operation methods of dictionaries are mainly divided into four categories: dictionary search, dictionary modification, dictionary addition, and dictionary deletion. 

##  12.2.2 dictionary search 

(1) Check if the key name exists 

Search method: 

>  1. key in dict  

2. key not in dict 

Key represents the key name of the dictionary, returns True if the key name exists, otherwise returns False. Not in means whether it does not exist. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
(2) Find the key value corresponding to the key 

Search method: 

>  1. dict[key]

Key represents the key name of the dictionary. If the key name exists, the key value will be returned. If the key name does not exist, an exception will be thrown.

2. dict.get(key, default=None)

Key represents the key name of the dictionary. If the key name exists, the key value will be returned. If the key name does not exist, the value specified by the default parameter will be returned. 

Operator [] is used in lists and tuples for index access and slicing, and in dictionaries for key-value access, modifying key-value, and adding key-value pairs. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
The get method of the dictionary type will automatically determine whether the key name exists first, avoiding the error exception when the key name does not exist. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
(1) Find all key names in the dictionary 

Operation syntax: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
The keys method of the dictionary type returns a dict_keys type dict_keys an iterable object that we can iterate through in a for loop. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
dict_keys types can be converted to list or tuple types by display type conversion. For example, list (dict_keys) or tuple (dict_keys). Students should think more divergent when learning. 

(2) Find all the keys in the dictionary 

Operation syntax: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
The values method of the dictionary type returns a dict_values type, dict_values an iterable object, which can also be traversed in a for loop. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
(5) Find all key-value pairs of the dictionary 

In the keys and values methods of the dictionary type, you can only get the key name or key value separately. Presumably students will have such questions, can you get the key name and key value at one time? 

With the items method of the dictionary type, you can return the key-value pair in the dictionary. The items method of the dictionary type returns a dict_items type. dict_items is an iterable object, now write a piece of code to get both the key name and the key value in the for loop. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
##  12.2.3 dictionary changes 

In Python, the keys of a dictionary are read-only, and the corresponding keys are modified. 

(1) Modify the key value of the dictionary 

Operation syntax: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
Key represents the key name and value represents the key value. When the key name does not exist, a new key-value pair is inserted. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
##  Adding 12.2.4 Dictionary 

(1) Operator: [] 

Operation syntax: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
new_key represents the new key name and value represents the key value. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
(2) dict.setdefault(key, default=None) 

The parameter key represents the key name. If the key exists, the key corresponding to the key will be returned. Otherwise, a new key-value pair will be added. The key value of the new key is specified by the parameter default, and the return value is the key corresponding to the key name. If no key value is specified, the return value is None. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
(3)dict.update(iterable) 

Iterable represents an iterable object, and the parameters passed are mainly dictionary type, list type, tuple type, and no return value. When updating a dictionary through a dictionary object, if the key name exists, the key value of the key name in the dictionary object is updated with a new key value. If the key name does not exist, a new key-value pair is added. When updating a dictionary through a list or tuple, the list/tuple is a two-dimensional structure, see the code example for details. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
##  Deletion of 12.2.5 Dictionary 

(1) dict.pop(key) 

The pop method is used to delete the specified key. The key to be deleted must exist in the dictionary object, otherwise it will throw an error exception that the key name does not exist, and the return value is the key value corresponding to the key name. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
(2) dict.popitem() 

The popitem method is used to delete the key-value pair in the dictionary, and the key-value pair at the end of the dictionary is deleted by default. The return value of the method is a tuple, the first element of the tuple is the key name, and the second element is the key value. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
(3) dict.clear() 

Delete all keys in the dictionary with one click through the clear method of the dictionary type, no return value 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574579925
 ```  
##  12.2.6 knowledge points 

>  (1) The commonly used operation methods of dictionaries are mainly divided into four categories: dictionary search, dictionary modification, dictionary addition, and dictionary deletion.

(2) The word operator [] is used in lists and tuples for index access and slicing, and in dictionaries for key-value access, modifying key-value, and adding key-value pairs. 

##  Learn Python 12.2.7 System 

>  About the French fries teacher: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. French fries teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning, quantitative investment. 



--------------------------------------------------------------------------------

directory 

Common operations for 13.2.1 collections 

Search 13.2.2 collections 

Adding 13.2.3 Collections 

Delete 13.2.4 collection 

13.2.4 set operation 

13.2.5 knowledge points 

Learn Python 13.2.6 System 

##  Common operations for 13.2.1 collections 

Collection type is an abstract data type. Abstract data type defines the operation method of data type. In this section, students are taught to thoroughly master the common operation methods of collection type. 

![avatar]( dff9f5132e0ad23cebb438a9280ba058.png) 

The common operation methods of dictionaries are mainly divided into four categories: collection search, collection addition, collection deletion, and collection operation. Keys in collections cannot be modified because the keys in collections must be static data types 

##  Search 13.2.2 collections 

(1) Whether the lookup key exists 

Search method: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574534367
 ```  
Name indicates the key in the collection, the return value is a Boolean type, True indicates that the key name exists, False indicates that the key name does not exist. Not in indicates whether the lookup does not exist. 

Code example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574534367
 ```  
##  Adding 13.2.3 Collections 

(1) set.add(key) 

Adds the keyname key to the collection with no return value. The key must be a hashable data type, otherwise the Python interpreter will throw an exception message with the wrong type. 

Code example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574534367
 ```  
The elements in the collection must be of a hashable data type, otherwise a type error will be reported. 

Code example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574534367
 ```  
(2) set.update(iterable) 

The parameter iterable represents an iterable object. When the update method is executed, the elements of the iterable object are added to the collection one by one. Iterables learned so far: string, list, tuple, dictionary, collection 

Code example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574534367
 ```  
##  Delete 13.2.4 collection 

(1) set.pop() 

Execute the pop method to randomly delete elements from the collection. The collection must be a non-empty collection, otherwise an exception message will be thrown. The return value is the deleted element. 

Code example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574534367
 ```  
The collection must be a non-empty collection, otherwise an exception message of the wrong type will be thrown, which we can verify in interactive mode: 

>  >>> set().pop()

Traceback (most recent call last):

File "<stdin>", line 1, in <module>

KeyError: 'pop from an empty set' 

(2) set.remove(key) 

Execute the remove method to remove the specified key from the collection. If the key does not exist, an exception will be thrown and no value will be returned. 

Code example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574534367
 ```  
(1) set.clear() 

Execute the clear method to empty the elements in the collection. 

Code example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574534367
 ```  
##  13.2.4 set operation 

Through the set type in Python, mathematical intersection, union, and difference operations can be realized. 

(1) Intersection operation 

Intersection, which refers to obtaining elements common to two sets, is implemented in Python using the '&' operator. 

Code example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574534367
 ```  
(2) union operation 

Union refers to the merging of elements from two sets, using the '|' operator in Python to achieve union operation. 

Code example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574534367
 ```  
(3) Difference arithmetic 

The difference set refers to the cooperative subtraction operation of two sets. Assuming that there are sets A and B, then the difference between sets A and B represents the set of elements that belong to A but not to B. The difference operation is directly implemented by the operator '-'. 

Code example: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574534367
 ```  
##  13.2.5 knowledge points 

>  (1) Common operation methods for collections are mainly divided into four categories: collection search, collection addition, collection deletion, and collection operation.

(2) The keys in the collection cannot be modified because the keys in the collection must be static data types

Iterable objects learned so far: strings, lists, tuples, dictionaries, collections 

##  Learn Python 13.2.6 System 

>  About the French fries teacher: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. French fries teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning, quantitative investment. 



--------------------------------------------------------------------------------

directory 

13.4.1 what is binary search? 

13.4.2 algorithm implementation 

Learn Python 13.4.3 System 

##  13.4.1 what is binary search? 

We have already learned about dictionaries and collections in Python, and it is very convenient to use dictionaries and collections to achieve fast lookup. Dictionaries and collections use the index structure of hash tables to speed up lookup. How can we optimize lookup performance for sequential table structures such as lists? In this tutorial, we will learn about a very classic lookup algorithm in the course of Data Structures and Algorithms: Binary Search. 

>  Using binary lookup can greatly improve the lookup performance of sequential tables. 

The core principle of binary search: first sort the data set, and then compare it with the elements in the middle every time. If it is equal, it will be returned directly, and if it is not equal, it will find the other half of the interval according to the ascending or descending order of the data set. The search process of binary search is shown in the following figure: 

![avatar]( 13cc971efc7dd10f9dbe55af95d4455c.jpeg) 

>  (1) First compare the middle elements, 11 is larger than 7. Since the data set is in ascending order, look for the right interval next time

(2) Repeat this process until all searches are completed 

##  13.4.2 algorithm implementation 

We shall now implement this binary search algorithm: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574577247
 ```  
##  Learn Python 13.4.3 System 

>  About the French fries teacher: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. French fries teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning, quantitative investment. 



--------------------------------------------------------------------------------

directory 

2.1.1 pycharm Introduction 2.1.2 pycharm Installation 2.1.3 Configuring Python Interpreter 

##  2.1.1 PyCharm 

PyCharm is an IDE tool designed for Python development, providing many features to help programmers improve development efficiency, such as code debugging, syntax highlighting, code jumping, auto-completion, and smart prompts. 

>  IDE is the abbreviation of Integrated Development Environment, that is, integrated development environment. The so-called integrated development environment refers to a power builder that integrates code writing, compilation, and debugging functions. 

PyCharm is divided into a commercial version and a community version. The commercial version is paid for. The community version is aimed at learners in the Python community. The features it provides are not much different from the commercial version. Generally speaking, using the community version can meet the development needs of most programmers. 

##  2.1.2 PyCharm installation 

Download page of PyCharm Community Edition: Download PyCharm: Python IDE for Professional Developers by JetBrains 

The download page is shown below: 

![avatar]( befc9af8bdb085fac71b416bc59a8b79.png) 

Directly click the download button under English Commuity to download the community version of PyCharm. After downloading, directly click the icon to install. 

>  This tutorial is explained in the 2021.1 version of PyCharm Community Edition. Please download the corresponding version on the official website. 

##  2.1.3 configure the Python interpreter 

After installing Pycharm, you need to configure the IDE and add the Python interpreter to the IDE. Now please follow these steps: 

(1) Click on the PyCharm icon on the desktop 

After clicking on the PyCharm Community Edition 2021.1 icon on the desktop, the following window will appear: 

![avatar]( 3fa9949d53e8a155dea2525e891031de.png) 

Tick I confirm that I have read and accept the terms of this User Agreement, and click the Continue button. The following welcome window will appear: 

![avatar]( 50d53e91a1aa991f9e4d34200d8fb358.png) 

In this welcome interface, click Projects to create or open a Python project, and click Customize to customize the theme, fonts, and global configuration of the IDE. 

(2) Configuring the Python interpreter 

Click on the Customize menu of the welcome interface and the following panel will appear: 

![avatar]( 93074d463c72a6548b079fee730437d4.png) 

Clicking Configure... in the panel will bring up the following configuration window: 

![avatar]( 73fd6a204644b4bc2cf89612adba3101.png) 

Click on Python Interpreter in the navigation menu on the left side of the page, then click on the drop-down box Python Interpreter in the right window, and you will see a Show All... option: 

![avatar]( 8a32e979c10f4341ae6a075e301199b9.png) 

In the small window that pops up later, click the + button in the upper left corner: 

![avatar]( 14662c920b74a3ebf02c6b2e43aa4c2f.png) 

After clicking the + button, PyCharm will automatically add the Python interpreter, as shown in the following figure: 

![avatar]( 051d2924be9d6828bca3af8a40a2beb1.png) 

The Base interpreter in the blue box is used to configure the Python interpreter. If PyCharm is not automatically added, you need to manually configure the absolute path of the Python interpreter. Continue to check Make available to all projects under the Base interpreter, and then click the OK button at the bottom right. PyCharm will automatically create a virtual environment for Python. After the creation is successful, the window shown in the following image will appear: 

![avatar]( eb0dd012d76a60d61e422fed62f2589b.png) 

Finally, click the OK button in all the windows that appear. After the operation is completed, it will continue to return to the welcome interface: 

![avatar]( 8c722b7160743c1a27bad0c5d5a45338.png) 

Click New Project in the Projects panel to create a new project. The following image shows the configuration window for the new project: 

![avatar]( d73e50ec22eea684f3ecd7fead5f01b8.png) 

The reader can rename the project name in the Location column, or choose not to create the project's main.py file. After clicking the Create button at the bottom right, the project is created successfully: 

![avatar]( b88ad31c1de29bea3e30ac1c8ce360cf.png) 

(3) Test the execution of Python programs 

 Right-click in the left column of the project window and click New, Python File in turn: 

![avatar]( c448894aacc71a01fbd04cb76310d720.png) 

Enter the name of the Python script file in the window shown below: 

![avatar]( 51ba4dd71d0815d3ca542d69358ca8a0.png) 

After entering the file name, press the Enter key on the keyboard, and finally enter the following code in the file: 

![avatar]( d21fb4521dbf07b75ff66754b0e3a650.png) 

Press CTRL + SHIFT + F10 shortcut to run the Python script directly in the current window. After the program is executed, the output of the program can be seen in the bottom output window of PyCharm: 

![avatar]( 88f601fff8cbb4fe738019f1102957e9.png) 

##   Systematic learning of Python 

>  Fries Teacher Profile: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. Fries Teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning 



--------------------------------------------------------------------------------

directory 

2.2.1 VS code 

2.2.2 VS Code installation 

2.2.3 configure the Python interpreter 

##  2.2.1 VS Code 

VS Code, the full name of Visual Studio Code, is a platform-breaking IDE tool developed by Microsoft. Compared with the "clunky" PyCharm, VS Code is very lightweight and fast to start. 

>  PyCharm is "clunky" because it supports more productivity-enhancing features and is more beginner-friendly. 

Unlike PyCharm, VS Code is a completely free software and supports multiple development languages. In addition, VS Code also supports syntax highlighting, code completion, built-in GIT, and extensions through plugins. 

##  2.2.2 VS Code installation 

The download page of VS Code: Visual Studio Code - Code Editing. Redefined download page is shown as follows: 

![avatar]( c5a218c8082af308a5d820bf0cdf7741.png) 

Directly click the blue Dowload for Windows button to download the windows side. If you need to download the installation package for other environments, click the drop-down box to select the corresponding installation version. After downloading the installation package locally, click the installation package to install. During the installation process, readers can configure the installation directory of the software and whether to create a desktop icon. After the installation is completed, start VS Code and you will see the following welcome interface: 

![avatar]( cef1323febf4be44c823d1a506ee00e0.png) 

>  The author does not recommend localizing IDE tools, it is pointless. To become an excellent programmer, you need to have a certain foundation in English. For students with poor English foundation, there is no need to deliberately learn English. You can start with the English you come into contact with during the learning process, such as the English words in the IDE, the English error prompts thrown by the Python interpreter, etc., in order to continuously accumulate English vocabulary. In this way, you can significantly improve your English level through subtle influence. 

###  

2.2.3 configure the Python interpreter 

VS Code customizes and extends the development environment in the form of plugins. When running and debugging Python in the IDE, you need to install the corresponding plugins first. 

Please follow these steps to configure VS Code: 

(1) Open VS Code and click the Tetris icon in the left column of the interface: 

![avatar]( 85cd33f34e1e7cad4b71ed991b7a647b.png) 

(2) Enter Python in the plugin search box 

![avatar]( 430057b90e00280799de2ddac374637e.png) 

Among the searched plugins, install the first Python plugin and click the green install button at the bottom right to install the plugin. After the installation is successful, VS Code will display the introduction page of the Python plugin: 

![avatar]( 70d6f48e10a44861e0e4ffd8375a9b8a.png) 

(3) Test running Python scripts 

Press the CTRL + O shortcut to open the hellopython.py script file created in Section 2.1: 

![avatar]( 84e22ecdbdd485a37309df6d75e6506b.png) 

Click the green triangle button on the right to run the open Python script directly. 

![avatar]( 389138b74580dabdcfc225c457887694.png) 

Or click the bug icon in the left column of the interface: 

![avatar]( 462b373b7e3ee8ce32458443aba30edb.png) 

![avatar]( f16f674048961f25a4b5abeff0615f18.png) 

The window features two prominent blue buttons: Debug with Python to debug the current Python script, and Run with Python to run the current Python script. 

##   Systematic learning of Python 

>  Fries Teacher Profile: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. Fries Teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning 



--------------------------------------------------------------------------------

directory 

2.3.1 create Python scripts on the desktop 

2.3.2 first Python program 

2.3.3 code line by line 

##  2.3.1 create Python scripts on the desktop 

We have installed Python's power builder, PyCharm, and VS Code in the last two lessons. In this lesson, we will take PyCharm as an example to write a very simple Python program, through which we can get a preliminary understanding of Python. Before writing the program, we will create a Python script file on the windows desktop. Please follow these steps: 

(1) Create a notepad file named hellopython.txt on the desktop 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574525902
 ```  
(2) Change the suffix to py 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574525902
 ```  
After modifying the suffix, the Windows system will automatically call the PyCharm program to set the file icon. If it is not displayed correctly, students can open the folder option and check whether it is ticked to hide the extension of the known file type. If ticked, you need to remove it, and then modify the suffix of the file again. 

![avatar]( 78eb1a1206acfe95cc89e60128c15623.png) 

##  2.3.2 first Python program 

After the script is created, open the hellopython.py with PyCharm and write the following Python code: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574525902
 ```  
Press the keyboard shortcut SHIFT + F10, you can execute the program in the window, the program output is hello python. 

##  2.3.3 code line by line 

The beginning of the file is enclosed in English three quotation marks "", which is a header comment, where @author is used to indicate the author of the program, and @desc is used to indicate the description of the program. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574525902
 ```  
Print is a built-in function in Python that prints the value of an expression. The Python interpreter will output the string hello world to the monitor when the line print ("hello python") is executed. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574525902
 ```  
##  2.3.4 system to learn Python 

>  Fries Teacher Profile: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. Fries Teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning 



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

directory 

4.3.1 print the multiplication table 

4.3.2 source code 

4.3.3 system to learn Python 

##  4.3.1 print the multiplication table 

We learned the basics of the windows command line and common commands in the course of Section 4.1. In this section of the program, we will write a very simple Python program that outputs the 99 multiplication table on the command line. The output interface of the 99 multiplication table is shown in the following figure: 

![avatar]( c93f8ff328dabdf78eb5ac2ee6cecd0a.png) 

##  4.3.2 source code 

Create a Python script called multiplication_table.py on your desktop. After opening it with PyCharm, enter the following Python code: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574533910
 ```  
After writing the code, press the windows key on the keyboard, and then execute the cmd command to enter the windows command line. After entering the command line, execute cd Desktop to switch to the desktop, and finally execute python multiplication_table.py to output the 99 multiplication table on the command line. 

![avatar]( b7de58a8abb2d7d7542944273c990ec8.png) 

Students should note that we have not yet officially learned Python. Students only need to run the above programs. 

>  If the program fails to run, either your environment is configured incorrectly, or there is an error in the code during the process of copying and pasting the code. Students should be careful and correct when learning Python at the beginning. 

##  4.3.3 system to learn Python 

>  Fries Teacher Profile: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. Fries Teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning 



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

directory 

##  5.3.1 implement countdown function 

5.3.1 implement countdown function 

5.3.2 source code 

5.3.3 system to learn Python 

##  5.3.1 implement countdown function 

We learned about functions and modules in Python in Section 5.2 of the course. In this section of the program, a countdown function is implemented with functions and modules: when the countdown is over, a prompt message is output to the screen. The output interface of the program is shown in the following figure: 

![avatar]( 3473bc8fe9b0ab4ea509a1ef5b3c53fb.png) 

##  5.3.2 source code 

Create a Python script called countdown.py on your desktop. After opening it with PyCharm, enter the following Python code: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574577661
 ```  
After writing the code, if you want to execute it in PyCharm, you can press shortcut SHIFT + F10. To execute it in the command line, you can press the windows key of the keyboard, and then execute the cmd command to enter the windows command line. After entering the command line, execute cd Desktop to switch to the desktop, and finally execute python countdown.py to output the nine-nine multiplication table in the command line. 

>  Students should note that we have not officially learned Python yet. Students only need to run the above programs. If the program fails to run, either your environment configuration is wrong, or there is an error in the code during the process of copying and pasting the code. Students should be careful and correct when learning Python at the beginning. 

##  5.3.3 system to learn Python 

>  Fries Teacher Profile: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. Fries Teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning 



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

directory 

7.2.1 calculate the second largest of the four 

7.2.2 use loops to calculate minor values 

Learn Python 7.2.3 System 

##  7.2.1 calculate the second largest of the four 

If there are four integer variables, how can we calculate the next largest value among them? 

![avatar]( be6571a9996b6f5e1d897a2abc9e514e.png) 

>  It is not difficult for beginners to solve this problem, but writing code in a concise and elegant manner is no small challenge. 

Directly comparing them one by one through if, this idea is obviously wrong, and the end result is just a long and smelly piece of code. A better idea is to calculate the maximum and median values of the three variables first, and determine their size relationship: 

![avatar]( 3548f706f830a9ab75891480e3f7e129.png) 

Then compare the fourth variable with the maximum value and the median value respectively. If it is larger than the maximum value of the three, then the second largest value must be the maximum value of the three. If it is smaller than the maximum value but larger than the median value, then the second largest value must be the fourth value. Otherwise, the second largest value must be the median value of the three. Why? Because the second largest value must not be the smallest value of the three, it can only be the median value of the three. 

>  First determine the size relationship between the three variables, so that it is convenient to compare. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574535174
 ```  
##  7.2.3 use loops to calculate minor values 

The logic of computing the minimum value in a for loop is simple. If you need to calculate the next smallest value, how do you do it? 

>  Many beginners think this problem is too complex, and they need to learn to simplify the complex problem in order to better understand the essence of things. 

The problem can be simplified to that the loop is executed only twice: if the first traversal results in a value smaller than the minimum, then the minimum is updated. If the second traversal results in a value smaller than the minimum, then the next smallest value must be the last minimum. 

>  In the process of implementation, it is also necessary to pay attention to the case where the traversed value is greater than the minimum value and less than the next smallest value, as well as the special case where the minimum value and the second smallest value are just the minimum value when initialized. 

Code example:  

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574535174
 ```  
##  Learn Python 7.2.3 System 

>  Fries Teacher Profile: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. Fries Teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning 



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

directory 

What is the number of daffodils 8.4.1? 

8.4.2 output all daffodils 

Learn Python 8.4.3 System 

##  What is the number of daffodils 8.4.1? 

A daffodil number is a three-digit number greater than 0, and the sum of each digit to the power of three is equal to itself. 

>  For a simple example, 153 is a daffodil number. The third power of 1 is equal to 1, the third power of 5 is equal to 125, the third power of 3 is equal to 27, and 1 + 125 + 27 = 153, so 153 is a daffodil number. 

After understanding the basic concept of the daffodil number, how to find all the daffodil numbers? The algorithm itself is not difficult, just take out each bit of the three digits, then calculate their third powers, and finally add and sum. The difficulty lies in how to take out each bit of the three digits. For single digits, let the three digits and 10 be the remainder, and the result must be single digits. Why? Because ten and hundred digits must be divisible by 10, the remainder must be single digits. 

>  Ten and hundred digits are necessarily divisible by 10, and according to this principle, we can further find ten digits: simply remove the single digit of the three digits, and then add the remainder to 10. 

For ten digits, you can divide them by 10 first, so that you can remove the single digits. After removing the single digits, you can get ten digits by adding the remainder to 10. As for hundreds, you can directly divide 100 to get hundreds. 

##  8.4.2 output all daffodils 

In Python, the range function can generate a specified range of integer sequences, generating all three digits of the [100, 1000) interval, we can write: range (100, 1000). The following is the complete Python code implementation: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574544026
 ```  
##  Learn Python 8.4.3 System 

>  Fries Teacher Profile: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. Fries Teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning, quantitative investment. 



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

