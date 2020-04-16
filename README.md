# Java Programs

## 1. Adult/Minor

Write a Java program which asks user to input his/her age and prints if s/he is a minor or adult.

## 2. Adult/Minor with validation

Write a Java program which asks user to input his/her age and prints if s/he is a minor or adult.

Note: It should print proper error message if user enters age which is not between 0 and 99.

## 3. Table Program

Write a Java Program which asks user to input a number and prints its table as below:

```
Enter a number: 2

2
4
6
..
..
20
```

## 4. Table Program (Formatted) 

Write a Java Program which asks user to input a number and prints its table as below:

```
Enter a number: 2

2 x 1 = 2
2 x 2 = 4
2 x 3 = 6
...
...
2 x 10 = 20
```

## 5. Table Program (Dynamic)

Write a Java Program which asks user to input a number and a count, and prints its table as below:

```
Enter a number: 2
Enter count: 20

2 x 1 = 2
2 x 2 = 4
2 x 3 = 6
...
...
2 x 20 = 40
```

## 6. Create Pattern

WAP (Write a Program) to print below patter using loop:

```
*
* *
* * *
* * * *
* * * * *
```

## 7. Create Pattern

WAP (Write a Program) to print below patter using loop:

```
* * * * *
* * * *
* * *
* *
*
```

## 8. Array Input (Dynamic)

WAP which asks user to enter size of array then numbers depending on the size of array, and prints sum.

```
Enter size of array: 5

Enter number 1: 5
Enter number 2: 4
Enter number 3: 3
Enter number 1: 2
Enter number 5: 1

Sum: 15

```

## 9. Count Characters

WAP to count characters (including space) in a sentence entered by the user.

```
Enter sentence: This is my world!

Characters count: 17
```

## 10. Count Characters (Exclude Spaces in Between)

WAP to count characters (excluding space) in a sentence entered by the user.

```
Enter sentence: This is my world!

Characters count: 14
```

## 11. Count Words

WAP to count words in a sentence entered by the user.

```
Enter sentence: This is my world!

Words count: 4
```

## 12. FD Interest Calculation

WAP to calculate returns for an FD (Fixed Deposit). User inputs amount and the duration in years for the FD. Interest rate should by dynamically used based on the duration as below:

From 1 year to 3 years: 5.5%  
From 4 years to 5 years: 6.5%  
From 6 years to 8 years: 8.0%  
More than 8 years: 9%

```
Enter amount: 10000
Enter duration: 6

Applicable interest rate: 8.0%
Total interest in 6 years: 800
Final amount: 10800
```

## 13. Income Tax Calculation

WAP to calculate income tax based on the tax slabs as give below:

```
| From Amount | To Amount | Tax Rate (%) |
| ----------: | --------: | -----------: |
|           0 |  2,50,000 |            0 |
|    2,50,001 |  5,00,000 |            5 |
|    5,00,001 | 10,00,000 |           10 |
|   10,00,001 | 12,00,000 |           20 |
|   12,00,001 |     above |           30 |
|             |           |              |
```

Example calculations: 

1. If user enters amount upto 2,50,000 then total tax should be 0.
2. If user enters amount 3,00,000 then tax rate from amount 0 to 2,50,000 should be calculated at the rate of 0% and then rest amount (50,000) should be calculated at the rate of 5%. So total should be as: 0% of 2,50,000 + 5% of 50,000 = 2,500
3. If user enters amount 15,00,000 then tax should be calculated as below:

```
| From Amount | To Amount | Tax Rate (%) | Tax Amount |
| ----------: | --------: | -----------: | ---------: |
|           0 |  2,50,000 |            0 |          0 |
|    2,50,001 |  5,00,000 |            5 |      2,500 |
|    5,00,001 | 10,00,000 |           10 |     50,000 |
|   10,00,001 | 12,00,000 |           20 |     40,000 |
|   12,00,001 | 15,00,000 |           30 |     90,000 |

Total: 1,82,500
```

Example run:

```
Enter amount: 1500000

Your total tax is: 182500
```
