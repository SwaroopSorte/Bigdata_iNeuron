## Assignment Part-1

Q1. Why do we call Python as a general purpose and high-level programming language?
    Python is easy to use: It is simple with an easily readable syntax and that makes it well-loved by both seasoned developers and experimental students. The simplicity of Python betokens that developers can fixate on genuinely solving the Machine Learning quandary rather than spend all their time (and energy) understanding just the technical nuances of the language.
    Python runs on any platform: Not only is Python profoundly utilizer-amicable, but it also runs everywhere. It runs on Windows, Unix, Linux, MacOS, and 21 different platforms including z/0s, Solaris, and VMS.
    Extensive support libraries: It provides large standard libraries that include the areas like string operations, Internet, web accommodation implements, operating system interfaces, and protocols. Most of the highly used programming tasks are already scripted into it that constrains the length of the codes to be inscribed in Python.
    ==========================================================
Q2. Why is Python called a dynamically typed language?
    Python is a dynamically typed language. What is dynamic? We don't have to declare the type of a variable or manage the memory while assigning a value to a variable in Python. Other languages like C, C++, Java, etc.., there is a strict declaration of variables before assigning values to them. We have to declare the kind of variable before assigning a value to it in the languages C, C++, Java, etc..,

    Python don't have any problem even if we don't declare the type of variable. It states the kind of variable in the runtime of the program. Python also take cares of the memory management which is crucial in programming. So, Python is a dynamically typed language.
    ==========================================================

Q3. List some pros and cons of Python programming language?
    Pros of Python:
    python is easy to learn and read
    python enhances productivity
    python has a vast collection of libraries
    python is free, open source and has a vibrant community
    python is a portable programming language
    python is an interpreted language

    Cons of Python:
    Python has speed limitation
    python is not so strong with mobile computing
    python can have runtime errors
    python consumes a lot of memory space
    python is not easy to test
    summing up.
    ==========================================================

Q4. In what all domains can we use Python?
    1.Machine learning
    2.Desktop GUI
    3.Data Analytics and Data Visualization
    4.Web Development
    5.Game Developement
    6.Embedded System
    7.Mobile App development

    ==========================================================
Q5. What are variable and how can we declare them?
    Python has no command for declaring a variable. A variable is created the moment you first assign a value to it.
    ==========================================================
Q6. How can we take an input from the user in Python?
    there are two methods 
        input(prompt)
        raw_input(prompt)
    ==========================================================
Q7. What is the default datatype of the value that has been taken as an input using input() function?
    <type'str'>
     ==========================================================
Q8. What is type casting?
    Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users
     ==========================================================
Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
    Yes, It is possible using 2 methods.
    1)using split() method
    2)Using list comprehension

     ==========================================================
Q10. What are keywords?
    Every programming language has special reserved words, or keywords, that have specific meanings and restrictions around how they should be used.
    In Python 3.8 there are thirty five keywords.
     ==========================================================
Q11. Can we use keywords as a variable? Support your answer with reason.
    No,We cannot use a keyword as a variable name, function name, or any other identifier. They are used to define the syntax and structure of the Python language.
     ==========================================================
Q12. What is indentation? What's the use of indentaion in Python?
    Indentation refers to the spaces at the beginning of a code line.

    Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important.

    Python uses indentation to indicate a block of code.
     ==========================================================
Q13. How can we throw some output in Python?

     ==========================================================
Q14. What are operators in Python?
    Operators are used to perform operations on variables and values.
    Types of Operators
        Arithmetic
        Assignment
        Comparison
        Logical
        Identity
        Membership
        Bitwise
     ==========================================================
Q15. What is difference between / and // operators?
    /  = Division
    // = Floor Divison
     ==========================================================
Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
    print(iNeuroniNeuroniNeuroniNeuron)
    OR
    for x in range(3):
        print(iNeuron)
     ==========================================================
Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
    num = int(input())
    if(num%2==0):
    print("Even")
    else:
    print("Odd")
     ==========================================================
Q18. What are boolean operator?
    The Python Boolean type is one of Python’s built-in data types. It’s used to represent the truth value of an expression. For example, the expression 1 <= 2 is True, while the expression 0 == 1 is False. Understanding how Python Boolean values behave is important to programming well in Python.
     ==========================================================
Q19. What will the output of the following?
```
1 or 0                   = 1

0 and 0                  = 0

True and False and True  = False

1 or 0 or 0              = 1
```
     ==========================================================
Q20. What are conditional statements in Python?
    In a Python program, the if statement is how you perform this sort of decision-making. It allows for conditional execution of a statement or group of statements based on the value of an expression.

     ==========================================================
Q21. What is use of 'if', 'elif' and 'else' keywords?
    if(<expr>):
        <statement>
    elif:
        <statement>
    else:
        <statement>
    elif:
        <statement>
    This is different from the if statement forms listed above because it is not a control structure that directs the flow of program execution. It acts more like an operator that defines an expression. In the above example, <conditional_expr> is evaluated first. If it is true, the expression evaluates to <expr1>. If it is false, the expression evaluates to <expr2>.
     ==========================================================
Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
    age = int(input())
    if age>=18:
        print("I can vote")
    else:
        print("I can't vote")
     ==========================================================
Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
    list2 = [12, 75, 150, 180, 145, 525, 50]
    sum=0
    for i in range(0,len(list2)):
        if(list2[i]%2==0):
        sum=sum+list2[i]
    print(sum)
    
     ==========================================================
Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
    A = list()
    n= int(input("Enter the number of element:"))
    for i in range(int(n)):
        ele=int(input(""))
        A.append(ele)
    min_ele = min(A)
    max_ele = max(A)
    print(min_ele)
    print(max_ele)
     ==========================================================
Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
    list1= [12,75,150,180,145,525,50]
    for i in range(0,len(list1)):
        if(list1[i]%5==0):
            if(list1[i]>150):
            print(list1[i]+1)
            if(list1[i]>500):
            break
        
     ==========================================================
