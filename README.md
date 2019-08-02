
# Systems of Linear Equations - Quiz

## Introduction
The following scenarios present problems that can be solved as system of equations, while performing substitutions and eliminations as you saw in the previous lesson. 

* Solve these problems by hand, showing all the steps to work out the unknown variable values 
* Verify your answers by showing the calculated values satisfy all equations

## Objectives
You will be able to:
* Describe a system of linear equations for solving simple analytical problems
* Solve a system of equations using elimination and substitution

## Exercise 1
Jane paid 12 dollars for 4 cups of coffee and 4 cups of tea. 3 cups of coffee cost as much as 2 cups of tea. What would be the total cost of 5 cups of coffee and 5 cups of tea?

### Solution

> Let $x$ be the unit price of coffee and $y$ be the unit price of tea


```python
"""
A) 4x + 4y = 12

B) 3x - 2y = 0 

From (A):
x = 3-y

Substituting y in (B):
3(3-y) - 2y = 0

9 - 3y - 2y = 6

y = 9/5 = 1.8

From (A)
4x +4(1.8) = 12

x = (12-7.2)/4

x = 1.2

Check condition 3x = 2y
3(1.2) = 2(1.8)

3.6 = 3.6

5 cups of tea and 5 cups of coffee
5(1.2)+ 5(1.8)

= 15 dollars.
"""
```

## Exercise 2

Jim has more money than Bob. If Jim gave Bob 20 dollars, they would have the same amount. If Bob gave Jim 22 dollars, however, Jim would then have twice as much as Bob. 

How much does each one actually have?

### Solution
> Let x be the amount of money that Jim has and y be the amount that Bob has.


```python
"""
If Jim gave Bob $20, they would have the same amount.
1) x − 20 = y + 20
If Bob gave Jim $22, Jim would then have twice as much as Bob.
2) x + 22 = 2(y − 22)

From (1)
x = y + 40 (3)

Substitute x in (2)
y + 40 + 22	= 2(y − 22)

y = 106 (Bob's amount)

From (3)
x = 106 + 40

x = 146 (Jim's amount)
"""
```

## Exercise 3

Mia has 30 coins, consisting of quarters (25 cents) and dimes (10 cents), which totals to the amount 5.70 dollars.  
How many of each does she have?

### Solution

> Let x be the number of quarters and y be the number of dimes.


```python
"""
The equations are:

1) x + y = 30
2) .25x + .10y = 5.70
To eliminate y, multiply equation (1) by −10 and equation (2) by 100:

3) −10x − 10y = −300
4) 25x + 10y = 570

Add (3) and (4):
15x = 270
x = 18

Therefore,

y = 30 − 18 = 12
"""
```

## Level up - Optional 
For more pratice with linear equations, Visit following links for more complex equations and online answers verification:

* https://www.transum.org/software/SW/Starter_of_the_day/Students/Simultaneous_Equations.asp?Level=6
* https://www.transum.org/software/SW/Starter_of_the_day/Students/Simultaneous_Equations.asp?Level=7

## Summary
In this lesson, you learned how to solve linear equations by hand to find the co-efficient values. You'll now move forward to have a deeper look into vectors and matrices and how Python and Numpy can help us solve more complex equations in an analytical context. 
