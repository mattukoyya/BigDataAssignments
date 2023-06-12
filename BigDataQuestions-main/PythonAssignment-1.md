## Assignment Part-1

Q1. Why do we call Python as a general purpose and high-level programming language?
Ans: Python is easy to learn and it is used to solve different problems and high level means it is easy for humans to understand as it is not in the format of 0 and 1.

Q2. Why is Python called a dynamically typed language?
Ans: when we declare a variable it automatically assigns the datatype.No need to write the datatype in python because it decides the datatype during the runtime.

Q3. List some pros and cons of Python programming language?
Ans: pros:
python is easy to learn
it can handle data analytics libraries
simple variable assignment and declaration
cons:
slow speed
heavy memory usage

Q4. In what all domains can we use Python?
Ans:Bigdata,datascience,machinelearning,artificial intellogence

Q5. What are variable and how can we declare them?
Ans: variable is a name given to a specific memory location
variable_name=value

Q6. How can we take an input from the user in Python?
Ans:input()

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans:string

Q8. What is type casting?
Ans:if we convert from one datatype to another datatype for e.g.,from string to int

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans:yes we can take using split function like input().split()

Q10. What are keywords?
Ans:keywords are reserved words and they have specific purpose.

Q11. Can we use keywords as a variable? Support your answer with reason.
Ans:no.it will throw an error as they are reserved words.

Q12. What is indentation? What's the use of indentaion in Python?
Ans: indentation is spaces at the beginning of the code line.it is used to indicate a block of code.

Q13. How can we throw some output in Python?
Ans:print("Throw some output")
Q14. What are operators in Python?
Ans:Numerical operators,comparision operators,logical operators,assignment operators

Q15. What is difference between / and // operators?
Ans:/ is used for float division and // is used for integer division.

Q16. Write a code that gives following as an output.
Ans:print("ineuron"\*4)

```
iNeuroniNeuroniNeuroniNeuron
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans:
num=int(input())
if(num%2==0):
print("Even")
else:
print("Odd")

Q18. What are boolean operator?
Ans:true or false

Q19. What will the output of the following?

```
1 or 0 output:1

0 and 0 output:0

True and False and True output:false

1 or 0 or 0 output:1
```

Q20. What are conditional statements in Python?
Ans:if-else statements

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans:they are used for decision making if condition fails it will go to elif if it fails then it will go to else.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans:
age=int(input())
if(age>=18):
print("I can vote")
else:
print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.

```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Ans:temp=0
for i in numbers:
if(i%2==0):
temp=temp+i
print(temp)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans:
x,y,z=input().split()
if(x>y and x>z):
print(x,"is the highest")
elif(y>z):
print(y,"is the highest")
else:
print(z,"is the highest")

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop

```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Ans:
for i in numbers:
if(i%5==0 && i<=150):
continue
else:
break
