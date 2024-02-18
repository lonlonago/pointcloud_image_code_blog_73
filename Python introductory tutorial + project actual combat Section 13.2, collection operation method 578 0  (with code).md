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

