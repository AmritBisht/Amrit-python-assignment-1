                                                     
                                                     please view it as raw




## Assignment Part-1   

Q1. Why do we call Python as a general purpose and high-level programming language?

Ans: We call Python as a general purpose programming language because it is used in many popular fields 
     like machine learning, artificial intelligence, Data science etc. and it is called high level programming language
     as it is a programming language which is closely associated with human understanding, that is its syntax or way of
     writing is easily understandable




Q2. Why is Python called a dynamically typed language?

Ans: Python is called a dynamically typed language because in Python the type of a variable is determined at runtime 
     rather than at compile time. we don't have to specify the data type of a variable when we declare it and the type
     of a variable can change during the execution of the program. 




Q3. List some pros and cons of Python programming language?

Ans: Pros:-
     * Easy to Read, Learn and Write
     * Dynamically Typed
     * Free and Open-Source
     * Vast Libraries Support
     * Improved Productivity
   
     Cons:- 
     * Not Memory Efficient
     * Runtime Errors
     * Difficult to test 
     * Speed limitations



Q4. In what all domains can we use Python?

Ans: Data engineering, Data Science, Machine Learning, Deep Learning, Artificial Intelligence, Scientific Computing Scripting,
     Networking, Game Development to Web Development.



Q5. What are variable and how can we declare them?

Ans: Variables are used to store information to be referenced and manipulated in a computer program.
     We can declare it as:- 
     ----------------------
     Var = "Ineuron"
     ----------------------

Q6. How can we take an input from the user in Python?

Ans: We can take it as:-
     ----------------------
     inp = input("Give your input: ")
     print(inp)
     ---------------------- 



Q7. What is the default datatype of the value that has been taken as an input using input() function?

Ans: Default datatype is String input function first takes the input from the user and converts it into a string.

 


Q8. What is type casting?

Ans: Type Casting is the method to convert the variable data type into a certain data type in order to the operation
     required to be performed by users.



Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Ans: Yes we can take more than one input from the user using single input() by using split function 

     ---------------------
     input().split(separator, maxsplit)
     ---------------------


Q10. What are keywords?

Ans: In Python keywords are special reserved words that have specific meanings and purposes and can't be used 
     for anything but those specific purposes.


Q11. Can we use keywords as a variable? Support your answer with reason.

Ans: We cannot use a keyword as a variable name, function name, or any other identifier. They are used to define
     the syntax and structure of the Python language. All the keywords except True , False and None are in lowercase 
     and they must be written as they are.


Q12. What is indentation? What's the use of indentaion in Python?

Ans: Python indentation is a way of telling the Python interpreter that a series of statements belong to a particular 
     block of code.



Q13. How can we throw some output in Python?

Ans: We can get output in python by print() function it prints the message to the screen or any other standard output device.



Q14. What are operators in Python?

Ans: Operators are used to perform operations on variables and values. python divides the operators in the following groups:
     Arithmetic operators
     Assignment operators
     Comparison operators
     Logical operators


Q15. What is difference between / and // operators?

Ans: / is regular division and return float numeric datatype and // is floor division return int numeric datatype.



Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans: ---------------
     print(iNeuron * 5)
     ---------------


Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Ans: ------------
     num = int(input("enter numer : "))
     if num % 2 == 0 :
        print(num,"is even number")
     else :
        print(num,"is odd number") 
     ------------

   
Q18. What are boolean operator?

Ans: Boolean Operators are those that result in the Boolean values of True and False. There are two types of operators in 
     python that return boolean values that are Logical operators and Comparison operators.



Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
Ans: 1
     0
     False
     1



Q20. What are conditional statements in Python?

Ans: Conditional Statement in Python perform different computations or actions depending on whether a specific Boolean 
     constraint evaluates to true or false. python has 3 Conditional Statements :-

     * if statement
     * if-else statement
     * if-elif-else ladder


Q21. What is use of 'if', 'elif' and 'else' keywords?

Ans: 'if' condition makes a decision based on whether the condition is true or not. If the condition is true, it prints 
     out the indented expression. If the condition is false, it skips printing the indented expression.
     'else' is use when the beginning of an if-else statement operates similar to a simple if statement however, if the condition is false, 
     instead of printing nothing, the indented expression under 'else' will be printed.
     When you run into a situation where you have several conditions, you can place as many 'elif' conditions as necessary between the if 
     condition and the else condition


Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Ans: ------------------
     age = int(input("I am : "))
     if age > 18:
        print("I can vote")
     else:
        print("I can't vote")
     --------------------


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Ans: ----------------------
     numbers = [12, 75, 150, 180, 145, 525, 50]
     a = 0
     for i in numbers:
         if i % 2 == 0 :
            a += i 
     print(a)
     -----------------------

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Ans : ----------------------
      a = int(input("first num :"))
      b = int(input("second num :"))
      c = int(input("third num :"))

      if a > b :
         if a > c :
            print(a, "greatest number")
      elif a < b :
           if b < c :
              print(c, "greatest number" )  
           else : 
              print(b, "greatest number")      
       -------------------------

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans: ---------------------
     numbers = [12, 75, 150, 180, 145, 525, 50]
     a = []
     for i in numbers:
         if i > 150:
            if i > 500:
               break
            continue
         elif i % 5 == 0:
              a.append(i)        
     print(a)
    -----------------------   
