# Module 1

## Name : Jenita Jayaseeli I
## Reg no : 212225060105

# 1. Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```
a = int(input())
if a%2==0:
    print("EVEN")
else:
    print("ODD")
```

## Output
![Screenshot 2025-04-29 101001](https://github.com/user-attachments/assets/a81270cd-cdd1-4c20-acd1-d8bae48047d7)


## Result

Thus, the python program was executed successfully


# 2. Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
```
a = (1 == True)
b = (0 == False)
c = True + 5
d = False + 9

# Printing the results
print(f"a is {a}")
print(f"b is {b}")
print(f"c: {c}")
print(f"d: {d}")
```

## Output
![Screenshot 2025-04-29 101901](https://github.com/user-attachments/assets/84efbfc3-41d1-4bd1-9b17-cdcaa49802dd)

## Result
The expected output is achieved 

# 3. Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'V'` and `'c'` using character literals.

## 🧠 Algorithm
1. Print the character `'V'`.
2. Print the character `'c'`.

## 🧾 Program
```
print('V')
print('c')
```

## Output

![Screenshot 2025-04-29 102156](https://github.com/user-attachments/assets/c9a55b2f-1291-48ac-9142-294c86134d0f)

## Result
The expected output is achieved

# 4. 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```
a=int(input())
b=int(input())
x=complex(a,b)
print(x)
print(x.real)
print(x.imag)
```

## Output
![Screenshot 2025-04-29 102634](https://github.com/user-attachments/assets/a3258f93-f8b0-4604-b941-280637e793d4)


## Result
The expected output is achieved 

# 5. Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
a = int(input())
b = input()
print(a,b)
```

## Output
![Screenshot 2025-04-29 103142](https://github.com/user-attachments/assets/7ea57ebb-3ba7-40f7-a2b7-863473c43c5c)


## Result
The expected output is acheived
