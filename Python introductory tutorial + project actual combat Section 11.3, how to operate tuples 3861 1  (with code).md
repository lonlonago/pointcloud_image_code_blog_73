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

