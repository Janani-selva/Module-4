## Classes and Objects in Python: Calculate the Area of a circle
## AIM
To write a Python program that calculates the area of a circle based on the radius provided by the user. This
 program uses a class named cse and a method mech to perform the calculation
## ALGORITHM
1. Get user input: Take the radius of the circle as input from the user.
 2. Define the class: Create a class named cse .
 3. Define the method: Inside the class, define the method mech to calculate the area of the circle using the formula
    Area = pi *r^2
 4. Execute the program: Create an object of the class and call the method with the radius value.
## PROGRAM
```
import math
 class Saveetha:
 def __init__(self, r):
 self.area = math.pi * (r ** 2) 
def slot(self):
 print("Area of circle:", round(self.area, 2))
 r = float(input())
 res = Saveetha(r)
 res.slot()
```
## OUTPUT
![Screenshot 2025-05-25 125732](https://github.com/user-attachments/assets/b84b3791-36d6-451e-abe8-cc0d010b510d)

## RESULT
Thus,the program has been executed successfully.Thus,the program has been executed successfully.

## Dictionary Operations in Python: Merging Two Dictionaries
## AIM
To write a Python program that merges two dictionaries and combines their key-value pairs.
## ALGORITHM
 1. Define two dictionaries dict1 and dict2 with some key-value pairs.
 2. Define a function merge() that merges the two dictionaries using the ** unpacking operator.
 The merged result will combine keys from both dictionaries. If a key exists in both, the value from
 dict2 will overwrite that from dict1 .
 3. Call the merge() function and print the merged dictionary.
## PROGRAM
```
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50} def 
merge (dict1,dict2): 
res={**dict1 , **dict2} return 
res 
dict3=merge(dict1,dict2) 
print(dict3)
```
## OUTPUT
![Screenshot 2025-05-25 125742](https://github.com/user-attachments/assets/a6a6364e-d394-4d8d-9d6f-a609779f2cd3)

## RESULT
Thus,the program has been executed successfully.

## Dictionary-Python Program to Sort a Dictionary by Keys and Values
## AIM
To write a Python program that sorts a dictionary's:
  - Keys in alphabetical order
  - Values in alphabetical order
## ALGORITHM
1. Start the program.
 2. Define a dictionary with key-value pairs.
 3. Sort by Keys:
Use sorted(dictionary.items()) 
 Convert the result to a dictionary using dict()
 4. Sort by Values:
 Use sorted(dictionary.items(), key=lambda item: item[1])
 Convert the result to a dictionary using dict()
 5. Display the original and sorted dictionaries.
 6. End the program
## PROGRAM
```
def dictionairy(): 
# Declaring hash function      
key_value ={}    
# Initializing the value 
key_value[2] = 56       
key_value[1] = 2 
key_value[5] = 12 
key_value[4] = 24 
key_value[6] = 18      
key_value[3] = 323 
print ("Keys and Values sorted", 
"in alphabetical order by the value") 
print(sorted(key_value.items(), key = lambda kv:(kv[1], kv[0])))
```
## OUTPUT
![Screenshot 2025-05-25 125753](https://github.com/user-attachments/assets/abf306a9-1d56-4c54-8fe5-db5ea9baad3f)

## RESULT
Thus,the program has been executed successfully.

## Exception Handling in Python: Avoiding Index Errors
## AIM
To write a Python program that handles an IndexError when trying to access an element beyond the available
range of a list.
## ALGORITHM
 1. Define a list list1 with some integer elements.
 2. Use a try-except block:
       -  In the try block, attempt to access an index that is out of range (e.g., list1[5] ).
       -  In the except block, catch the error and print a custom message "You're out of list range" .
 3. Print the result based on whether the index access succeeds or fails.
## PROGRAM
```
 msg=[5, 10, 20]
 try:
 print(msg[5])
 except IndexError:
 print("You're out of list range")
```
## OUTPUT
![Screenshot 2025-05-25 125802](https://github.com/user-attachments/assets/654db649-98d2-4afd-89c2-1e3a86bd3020)


## RESULT
Thus,the program has been executed successfully.

## File Handling in Python: Count Lines Not Starting with 'T'
 ## Aim
 To write a Python program that counts the number of lines in a text file story.txt that do not start with the
 alphabet 'T' .

## Algorithm
 1. Open the file story.txt in read mode.
 2. Initialize a counter count to zero.
 3. Iterate through each line of the file:
 Check if the first character of the line is not 'T' .
 If the line does not start with 'T' , increment the count by 1.
4. After processing all lines, print the count value, which represents the number of lines that do not start
 with 'T' .

## Program
```
 def returnSum(myDict):
 final=0
 for i in myDict.values():
 final+=i
 return final
 #driver functions
 myDict = {'a': 100, 'b': 200, 'c': 300}
 print("Sum :",returnSum(myDict)
```
## OUTPUT
![Screenshot 2025-05-25 125811](https://github.com/user-attachments/assets/3c819119-de14-4bcd-b8bc-0fa0adeaed12)

## RESULT
Thus,the program has been executed successfully.
