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
## 14. Quotient and Remainder

WAP to find quotient and remainder of the given number entered by user.

## 15. Calculate Power

WAP to calculate power of the number given by user. Ask user to enter power too.

```
Enter number: 2
Enter power: 4

2^4 = 16
```

## 16. Character Count

WAP which counts given character in the user input.

```
Enter a string: This is my world!
Enter char to count: i

Character 'i' appears 2 times.
```

## 17. Count All Characters

WAP to count all characters in a given string and print count.

```
Enter a sentence: all is well here

Characters count:

a: 1
l: 4
 : 3
i: 1
w: 1
e: 3
h: 1
r: 1
```

## 18. Count Vowels

WAP to count vowels in input string.

## 19. Palindrome

WAP to detect whether the input word is a palindrome or not

## 20. Prime Number

WAP to find if the number entered by the user is a prime number or not.

## 21. Show Unique Numbers

WAP which asks user to enter 5 numbers and displays all numbers removing the duplicate numbers

```
Enter number 1: 1
Enter number 2: 2
Enter number 3: 4
Enter number 4: 4
Enter number 5: 2

Unique numbers: 1 2 4

```

## 22. Reverse String

WAP that prints input string in reverse order.

```
Enter a string: aditi

Reverse of aditi is itida
```

## 23. Print ASCII Values

WAP to print ASCII values of all individual characters in a given string.

```
Enter a string: shashwat

ASCII value of s: 115
ASCII value of h: 104
ASCII value of a: 97
ASCII value of s: 115
ASCII value of h: 104
ASCII value of w: 119
ASCII value of a: 97
ASCII value of t: 116
```

## 24. Print ASCII Values (All Letters)

WAP to print ASCII values of all English alphabets **using for loop**

Output:
```
ASCII value of a: 97
ASCII value of b: 98
ASCII value of c: 99
ASCII value of d: 100
ASCII value of e: 101
...
...
ASCII value of v: 118
ASCII value of w: 119
ASCII value of x: 120
ASCII value of y: 121
ASCII value of z: 122
```

## 25. Count Vowels, Consonants and Other Chars

Note: Do it using ASCII values.

```
Enter a string: I love my family!

Count Vowel: 4
Count Consonants: 9
Others: 4
```

## 26. Compare String Equals (Case Sensitive)

WAP which tells if the two input strings are equal or not.

```
Enter string: Hello
Enter another string: hello

Not Equals!
```

## 27. Compare String Equals (Case Insensitive)

WAP which tells if the two input strings are equal or not.

```
Enter string: Hello
Enter another string: hello

Equals!
```

## 28. Find String in Another String

WAP which tells if a given string exists in another given string

```
Enter a string: aditi tripathi
String to find: path

Yes, it occurs!
```

## 29. Find String in Another String

WAP which tells if a given string exists in another given string

```
Enter a string: aditi tripathi
String to find: path

Yes, it occurs!
```

## 30. Char Occurrence

WAP to find occurrences of a given string into another string

```
Enter a string: shashwat
String to find: sh

Occurrences: 2
```

## 40. Replace Char

WAP to replace a character in a given string with another given character

```
Enter a string: shashwat tripathi
Char to find: a
Replace with: e

Result: sheshwet tripethi
```

## 40. Replace String within a String

WAP to replace a string in a given string with another given string

```
Enter a string: hello world!
Char to find: llo
Replace with: kko

Result: hekko world!
```

