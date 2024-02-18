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

