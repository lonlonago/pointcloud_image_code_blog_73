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

