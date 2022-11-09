# Page 259 - Quadratic Equation

Root of Quadratic Equation

## Program Description:
The roots of the quadratic equation `ax^2 +bx + c = 0`, a != 0 are given by the following formula. 
If a == 0, your program should output `Invalid entry`.

![quadratic equation](https://user-images.githubusercontent.com/32272045/200133496-7f43131c-ed7a-40c0-ae55-92c9a8518272.png)

In this formula, the term `b^2-4ac` is called the **discriminant**. 
If `b^2-4ac` = 0 , then the equation has a single (repeated) root. 
If `b^2-4ac` > 0 , the equation has two real roots. 
If `b^2-4ac` < 0 , the equation has two complex roots. 

Write a program that takes as input the value of `a` (the coefficient of 
x^2 ), `b` (the coefficient of x), and `c` (the constant term) and **outputs the type of roots of the equation**. 
Your input is going to be `a`,`b`,and `c` respectively.

Furthermore, if `b^2-4ac` >= 0 , the program should output the roots of the quadratic equation. 
(Hint: Use the function pow from the header file cmath to calculate the square root. Chapter 3 explains how the function pow is used.)

**Please make sure your code's output is exactly the same as the output below.**
```
Input: 2 5 6
Output: Complex roots
```
```
Input: 2 4 2
Output: The single root is -1
```
```
Input: 
1 1 0
Ouput:
Two real roots
- First root 0
- Second root -1
```
## How to Submit:
1. Once you are in your private `repository`
2. Open up the `main.cpp` file
3. Click on the :pencil2: icon to edit the file and then write your program.
4. Scroll down to `Commit Changes` and give your commit a title.
5. Finally, Click `Commit Changes` to submit your code.

```
Every time you make a commit, your code gets graded based on the test cases. 
You are allowed to make as many commits as you like.
```

## Things To include:
- Make sure to include the following comment above your code.
```cpp
// Full Name J00123456 Date Done
```
