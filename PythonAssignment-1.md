## Assignment Part-1
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
