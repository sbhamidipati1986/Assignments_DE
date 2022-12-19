
Q1. Why do we call Python as a general purpose and high-level programming language?
High-level languages make programming easier and uses memory and processor efficiently.

Q2. Why is Python called a dynamically typed language?
We need not declare the type of the variable, which is determined only during runtime.


Q3. List some pros and cons of Python programming language?
Pros:
Flexible and Extensible	
Extensive Libraries
Highly Scalable	
Portable
Cons:
High memory consumption
Garbage collection leads to potential memory losses

Q4. In what all domains can we use Python?
Application devlopment
ML
Natural Language Processing
Web Scrapping


Q5. What are variable and how can we declare them?

Variable is a storage unit.
Python has no command for declaring a variable.A variable is created the moment you first assign a value to it.

Q6. How can we take an input from the user in Python?
We can use input statement.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
String

Q8. What is type casting?
Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Yes, We can use the split() method.

Q10. What are keywords?
Pre defined special reserved words that have specific meanings and purposes and can’t be used for anything but those specific purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.
No.
Pre defined special reserved words that have specific meanings and purposes and can’t be used for anything but those specific purposes.

Q12. What is indentation? What's the use of indentaion in Python?
Indentation refers to the spaces at the beginning of a code line Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?
print()

Q14. What are operators in Python?
+,-,*,/,//,%,**

Q15. What is difference between / and // operators?
/ gives divisor value.
10/4=2.5
// gives floor value.
10//4=2

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
s='iNeuron'
for i in range(2):
    
    s+=s

print(s)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

x=int(input('enter the value:'))
if(x%2==0):
    print('Even')
else:
    print('odd')

Q18. What are boolean operator?
The logical operators and, or and not are also referred to as boolean operators.

Q19. What will the output of the following?
```
1 or 0
1

0 and 0
0

True and False and True
False

1 or 0 or 0
1
```

Q20. What are conditional statements in Python?
A conditional statement help to make decisions based on the conditions given in the program.

Q21. What is use of 'if', 'elif' and 'else' keywords?
IF : if condtion is satisfied it should enter the loop.
Elif: if condtion is not satisfied then we will use elif to check another condition. 
else: if any of the conditions given are not satisfied then it should enter else loop.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

x=int(input('enter the value:'))
if(x>=18):
    print("I can vote")
else:
    print("I can't vote")


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
sum=0
for i in numbers:
    if(i%2==0):
        sum+=i
print('Sum of even numbers in the list is:',sum)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
x,y,z=input('enter three value:').split()
x=int(x)
y=int(y)
z=int(z)

max(x,y,z)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

numbers = [12, 75, 150, 180, 145, 525, 50]
x=[]
for i in numbers:
    if(i>500):
        break
    elif(i%5==0 and i<=150):
        x.append(i)

Q26. What is a string? How can we declare string in Python?

Python strings are immutable data types which stores the character data.

Can be declated using ' ' or " " 

Q27. How can we access the string using its index?
Individual characters in a string can be accessed by specifying the string name followed by a number in square brackets .
Ex:
s='abc'
s[0]=a
s[1]=b
s[-1]=c

Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```
string = "Big Data iNeuron"
l=string.split(" ")
l[-1]

Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"
```
string = "Big Data iNeuron"
l=string.split(" ")
o=l[-1]
o[::-1]

Q30. Resverse the string given in the above question.
string[::-1]

Q31. How can you delete entire string at once?
del string

Q32. What is escape sequence?
An escape sequence is a sequence of characters that, when used inside a character or string, does not represent itself but is converted into another character or series of characters

Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
print("iNeuron's Big Data Course")
print('''iNeuron's Big Data Course''')

Q34. What is a list in Python?
 Lists are used to store multiple items in a single variable

Q35. How can you create a list in Python?
l=[1,2,3]
l1=list(range(1,5))

Q36. How can we access the elements in a list?
 We use the index operator[] to access elements.

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 
lst[4][2]

Q38. Take a list as an input from the user and find the length of the list.
l=input("enter a list")
list1  = l.split(",")
print(list1)
Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```
lst.insert(3,'Big')

Q40. What is a tuple? How is it different from list?
 tuple are used to store multiple items which ordered and immutable, But list is mutable which can be modified.

Q41. How can you create a tuple in Python?
Creating a tuple is as simple as putting different comma-separated values.
t=('a',1)

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
t=('a',1)
we cannot modify tuple because it is immutable.

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
we cannot modify tuple because it is immutable.
we have to create a new variable for tuple append.
t=('a',1)
t1=('b',2)
t2=t+t1
print(t2)

Q44. Take a tuple as an input and print the count of elements in it.
t2=('a', 1, 'b', 2, 'a', 1, 'b', 2)
print(t2.count('a'))

Q45. What are sets in Python?

A Set is an unordered collection data type that is iterable, mutable, and has no duplicate elements. 

Q46. How can you create a set?
Set are represented by { }

Q47. Create a set and add "iNeuron" in your set.
s={1}
s.add("iNeuron")
print(s)
Q48. Try to add multiple values using add() function.
t2=('a', 1, 'b', 2, 'a', 1, 'b', 2)
s={1}
s.update(t2)
print(s)
Q49. How is update() different from add()?
As add() function add a single element to the set, whereas update() function iterates over the given sequences and adds them to the set. 
t2=('a', 1, 'b', 2, 'a', 1, 'b', 2)
s={1}
s.add(t2)
print(s)

Output: {1, ('a', 1, 'b', 2, 'a', 1, 'b', 2)}

t2=('a', 1, 'b', 2, 'a', 1, 'b', 2)
s={1}
s.update(t2)
print(s)

{'a', 1, 'b', 2}


Q50. What is clear() in sets?
The clear() method removes all elements in a set.

Q51. What is frozen set?

Frozen set is just an immutable version of a Python set object. 

Q52. How is frozen set different from set?
While elements of a set can be modified at any time, elements of the frozen set remain the same after creation.

Q53. What is union() in sets? Explain via code.
Union of two given sets is the set which contains all the elements of both the sets. The union of two given sets A and B is a set which consists of all the elements of A and all the elements of B such that no element is repeated. 
list1=['1', '2', '3', '4']
t2=('a', 1, 'b', 2, 'a', 1, 'b', 2)
s1={1}
s1.update(t2)
s.clear()
s.update(list1)
s=s.union(s1)
print(s)

{1, 2, '2', '1', '3', 'a', 'b', '4'}

Q54. What is intersection() in sets? Explain via code.

The intersection() method returns a set that contains the similarity between two or more sets.
list1=['1', '2', '3', '4',1,'a']
t2=('a', 1, 'b', 2, 'a', 1, 'b', 2)
s1={1}
s1.update(t2)
s={1}
s.clear()
s.update(list1)
print(s,s1)
s=s.intersection(s1)
print(s)

{'a', 1}

Q55. What is dictionary ibn Python?
Dictionaries are used to store data values in key:value pairs.

Q56. How is dictionary different from all other data structures.
Because it uses key as index and mapped value.

Q57. How can we delare a dictionary in Python?
we can use dict() or {}

Q58. What will the output of the following?
```
var = {}
print(type(var))
```
Dict

Q59. How can we add an element in a dictionary?
var = {}
print(type(var))
var['k']=1
Q60. Create a dictionary and access all the values in that dictionary.
var = {}
var['k']=1
var.pop('k')
key =['a','b','c','d']
val=[1,2,3,4]
for i in range(0,len(key)):
    var[key[i]]=val[i]
print(var.values())

Q61. Create a nested dictionary and access all the element in the inner dictionary.
var = {}
var['k']=1
var.pop('k')
key =['a','b','c','d']
val=[1,2,3,4]
for i in range(0,len(key)):
    var[key[i]]=val[i]
print(var.values())
var['di']={'e':5,'f':6}
def diva(var):
    
    for i in var.values():
        if isinstance(i, dict):
            yield from get_values(i)
        else:
            yield i
x=[]
for i in diva(var):
    x.append(i)

print(x)
Q62. What is the use of get() function?
The get() method returns the value of the item with the specified key.

Q63. What is the use of items() function?
items() method is used to return the list with all dictionary keys with values.

Q64. What is the use of pop() function?
pop() method removes the key and value from dictionary.

Q65. What is the use of popitems() function?
popitem() method removes the last item in dictionary

Q66. What is the use of keys() function?
keys() method returns all the keys in dictionary


Q67. What is the use of values() function?
values() method returns all the values in dictionary

Q68. What are loops in Python?
Looping means repeating something over and over until a particular condition is satisfied.

Q69. How many type of loop are there in Python?

for loop and while loop

Q70. What is the difference between for and while loops?

The for loop is used when we already know the number of iterations, which means when we know how many times a statement has to be executed. That is why we have to specify the ending point in the for loop initialization. When we need to end the loop on a condition other than the number of times, we use a while loop

Q71. What is the use of continue statement?

The continue keyword is used to end the current iteration in a  loop and continues to the next iteration.

Q72. What is the use of break statement?

The break keyword is used to break out a loop

Q73. What is the use of pass statement?

When the pass statement is executed, nothing happens, but you avoid getting an error when empty code is not allowed. Empty code is not allowed in loops, function definitions, class definitions, or in if statements.

Q74. What is the use of range() function?
The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.
range(5)
x=range(5)
for i in x:
    print(i)
Q75. How can you loop over a dictionary?
You can loop through a dictionary by using a for loop.



### Coding problems
Q76. Write a Python program to find the factorial of a given number.
fact = lambda x: 1 if x == 0 else x * fact(x-1)

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100

si=lambda p,r,t: (p*r*t)/100

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
ci=lambda p,r,t: (p*(1+r/100)**t)/100

Q79. Write a Python program to check if a number is prime or not.
prime = lambda x:len([i for i  in range(2,int(x/2)) if(x%i==0)])
if(prime(1249)>0):
    print('Not a prime')
else:
    print('Prime')

Q80. Write a Python program to check Armstrong Number.

def arms(x):
    i=x
    l=[]
    sum=0
    while(int(i/10)>0):
        l.append(i%10)
        i=int(i/10)
    l.append(i)
    
    for i in l:
        le=len(l)
        sum+=i**le
        
    if(sum==x):
        print('Armstrong number')
    else:
        print('Not armstrong number')
        
        
        
arms(371)  

Q81. Write a Python program to find the n-th Fibonacci Number.
def fibb(x):
    
    l=[0,1]
    for i in range(2,x):
        le=len(l)
        l.append(l[le-1]+l[le-2])
    
    print(l)

fibb(10)

Q82. Write a Python program to interchange the first and last element in a list.
x=[0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
x[0]=x[-1]+x[0]
x[-1]=x[0]-x[-1]
x[0]=x[0]-x[-1]

x=[0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
t=x[-1]
x[-1]=x[0]
x[0]=t

Q83. Write a Python program to swap two elements in a list.
def inter(x,a,b):
    t=x[a]
    x[a]=x[b]
    x[b]=t
    return x
x=[0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
inter(x,2,5)    

Q84. Write a Python program to find N largest element from a list.
def nlar(x):
    t=x[0]
    for i in x:
        if(i>t):
            t=i
    return t

Q85. Write a Python program to find cumulative sum of a list.
x=[10, 20, 30, 40, 50]
def cus(x):
    
    y=[x[0]]
    for i in range(1,len(x)):
        t=x[0]
        for j in range(1,i+1):
            t=t+x[j]
            
        y.append(t)
    return(y)

cus(x)
        

Q86. Write a Python program to check if a string is palindrome or not.
pali=lambda x:'Palindrome' if(x==x[::-1]) else 'Not a Palindrome'
pali('MADAN')
pali('MADAM')

Q87. Write a Python program to remove i'th element from a string.
def rmi(x,n):
    l=[]
    for i in range(0,len(x)):
        if(i!=n):
            l.append(x[i])
    return(''.join(l))
rmi('TESTWORD',4)

Q88. Write a Python program to check if a substring is present in a given string.
x='TESTORD'
y='ORD'


if y in x:
    print("Found!")
else:
    print("Not found!")
Q89. Write a Python program to find words which are greater than given length k.
def rmi(x,n):
    l=[]
    for i in range(0,len(x)):
        if(i>n):
            l.append(x[i])
    return(''.join(l))
rmi('TESTWORD',4)
Q90. Write a Python program to extract unquire dictionary values.
dic={'a':1,'b':2,'c':3,'d':1}
set(dic.values())

Q91. Write a Python program to merge two dictionary.
dic={'a':1,'b':2,'c':3,'d':1}
dic1={'f':1,'g':2,'h':3,'d':3}
dic|dic1

Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```
i1 = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
x=[]
y=[]
ou={}
for i in i1:
    x.append(i[0])
    y.append(i[1])
for i in range(0,len(x)): 
    ou[x[i]]=y[i]

print(ou)

Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```
l = [9, 5, 6]
x=[]
for i in l:
    x.append((i,i**3))
x

Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```
def combine_t(t1,t2):
    x=[]
    for i in range(0,len(t1)):
        for j in range(0,len(t2)):
            x.append((t1[i],t2[j]))
    for i in range(0,len(t2)):
        for j in range(0,len(t1)):
            x.append((t2[i],t1[j]))   
    return(x)
combine_t(test_tuple1,test_tuple2)    

Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```
for i in range(0,len(Input)):
    for j in range(0,i):
        if(Input[i][1]<Input[j][1]):
            t=Input[i]
            Input[i]=Input[j]
            Input[j]=t
        

Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```
for i in range(1,6):
    for j in range(1,i+1):
        print('* ',end='')
    print('\t')
    

Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```
x=' '
y='*'
for i in range(1,6):
    
    s=(5-i)*x+i*y
    print(s,end='')
    print('\t')
Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```
x=' '
y='* '
for i in range(1,6):
    if(i!=6):
        s=(6-i)*x+i*y+(6-i)*x
        print(s,end='')
        print('\t')
    else:
        s=x+i*y+x
        print(s,end='')
        print('\t')
    

Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```
x=[]
for i in range(1,6):
    x.append(str(i)+' ')
    y=''.join(x)
    print(y,end='')
    print('\t')
   

Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```


for i in range(1,6):
    x=[]
    for j in range(0,i):
        x.append(chr(i+65-1)+' ')
    y=''.join(x)
    print(y,end='')
    print('\t')
