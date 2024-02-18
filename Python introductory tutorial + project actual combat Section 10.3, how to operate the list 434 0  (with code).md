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

