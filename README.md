# Python_Testcase  
https://realpython.com/python-testing/  

The structure of a test should loosely follow this workflow:  
Create your inputs  
Execute the code being tested, capturing the output  
Compare the output with an expected result  

For this application, you’re testing sum(). There are many behaviors in sum() you could check, such as:  
Can it sum a list of whole numbers (integers)?  
Can it sum a tuple or set?  
Can it sum a list of floats?  
What happens when you provide it with a bad value, such as a single integer or a string?  
What happens when one of the values is negative?  


