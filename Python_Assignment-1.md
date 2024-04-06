## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Answer: Python is considered general-purpose because it can be used for a wide range of applications, including web development, data science, artificial intelligence, automation, and more. It's high-level because it abstracts away low-level details like memory management and provides a simple and easy-to-read syntax.

Q2. Why is Python called a dynamically typed language?
Answer: Python is dynamically typed because variables do not have a fixed data type. You can assign any type of value to a variable, and its type is determined at runtime.

Q3. List some pros and cons of Python programming language?
Answer: Pros: Easy to learn and use, vast standard library, strong community support, versatile, readable syntax.
        Cons: Slower execution speed compared to compiled languages like C/C++.
Q4. In what all domains can we use Python?
Answer:Python can be used in various domains, including web development, data science, machine learning, artificial intelligence, automation, scientific computing, and more.

Q5. What are variable and how can we declare them?
Answer: Variables are containers for storing data values. In Python, you can declare a variable by simply assigning a value to it. For example: x = 5

Q6. How can we take an input from the user in Python?
Answer: We can take input from user using input() function. eg- name = input("Enter your name:")

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Answer: The default datatype of the value taken as an input using the input() function is string.

Q8. What is type casting?
Answer: Type casting is the process of converting the data type of a value from one type to another. In Python, you can perform type casting using built-in functions like int(), float(), str(), etc.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Answer:No, we cannot take multiple inputs using a single input() function call. We need to call input() multiple times to take multiple inputs.

Q10. What are keywords?
Answer: Keywords are reserved words in Python that have predefined meanings and cannot be used as identifiers (such as variable names or function names).
 
Q11. Can we use keywords as a variable? Support your answer with reason.
Answer: No, we cannot use keywords as variable names because keywords have predefined meanings in Python, and using them as variable names would lead to syntax errors.
Q12. What is indentation? What's the use of indentaion in Python?
Answer: Indentation refers to the spaces or tabs at the beginning of a line of code. In Python, indentation is used to define the block of code (e.g., within loops, conditional statements, function definitions). It helps in visually representing the structure of the code and is essential for maintaining readability and understanding.

Q13. How can we throw some output in Python?
Answer: We can use print() function. eg- print("Hello, World")

Q14. What are operators in Python?
Answer: Operators in Python are special symbols or keywords that perform operations on operands. They include arithmetic operators (+, -, *, /, etc.), comparison operators (==, !=, >, <, etc.), logical operators (and, or, not), assignment operators (=, +=, -=, etc.).

Q15. What is difference between / and // operators?
Answer: The / operator performs floating-point division, whereas the // operator performs floor division, which returns the quotient without the fractional part.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Answer:print("iNeuron"*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Answer:num = int(input("Enter a number:"))
if num % 2 ==0:
    print("The number is even")
else:
    print("The number is odd")

Q18. What are boolean operator?
Answer: Boolean operators are operators that operate on boolean operands and produce boolean results. They include and, or, and not.

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
Answer: 1
	0
	False
	1

Q20. What are conditional statements in Python?
Answer: Conditional statements in Python are used to execute different blocks of code based on certain conditions. They include if, elif  and else.

Q21. What is use of 'if', 'elif' and 'else' keywords?
Answer:'if' is used to execute a block of code if a condition is true. 'elif' is used to check additional conditions if the previous conditions are false. 'else' is used to execute a block of code if none of the previous conditions are true.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Answer: age = int(input("Enter your age:"))
if age < 18:
    print("I can't vote")
else:
    print("I can vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Answer: numbers = [12, 75, 150, 180, 145, 525, 50]
total = 0
for num in numbers:
    if num % 2 == 0:
        total += num
print("Sum of even numbers:", total)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Answer: num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
num3 = int(input("Enter third number: "))
print("The greatest number is:", max(num1, num2, num3))

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Answer: numbers = [12,75,150,180,145,525,50]

        numbers_cond = []

	for num in numbers:

    		if num > 500:
        		break
    		if num > 150:
        		continue
    		if num % 5 ==0:
        		print(num)
    