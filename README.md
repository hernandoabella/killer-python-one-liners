![GitHub Banners](https://github.com/user-attachments/assets/94bd957b-7001-4893-bd66-c3da2c37e7b9)

## Table of contents

### Mathematical Operations
- [Convert Celsius to Fahrenheit](#convert-celsius-to-fahrenheit)
- Convert RGB to Hex
- Simple Sum
- Calculate the Area of a Circle
- Calculate the Power of a Number
- Sum of Numbers up to a Given Number
- Sum all Numbers in a List
- Find the Maximum Value in a List
- Find the Minimum and Maximum Numbers in a List
- Calculate the Sum of Squares of a List
- Calculate the Sum of Cubes of a List
- Find the Mode of a List of Numbers
- Generate a Fibonacci Sequence
- Find the Nth Fibonacci Number (recursive)
- Find the Nth Fibonacci Number
- Calculate the Standard Deviation of a List of Numbers
- Generate multiplication table
- Calculate PI to N Decimal Places
- Calculate the Perimeter of a Rectangle
- Calculate the Exponential of a Number
- Calculate the Hypotenuse of a Right-Angled Triangle
- Calculate the Volume of a Sphere
- Calculate the Volume of a Cylinder
- Calculate the Volume of a Cube
- Calculate the Area of a Triangle given the Base and Height
- Convert Degrees to Radians
- Convert Feet to Meters
- Convert Minutes to Seconds
- Convert Seconds to HH:MM:SS Format
- Convert Seconds to Minutes and Seconds
- Convert Seconds to Hours, Minutes, and Seconds
- Convert Days to Years, Months, and Days
- Convert Decimal Number to Octal
- Convert Decimal Number to Hexadecimal
- Convert Binary Number to Decimal
- Convert DNA to RNA

### String Manipulation
- Capitalize a String
- Reverse a String
- Move Capital Letters to Front
- Get the Length of a String
- Truncate a String to a Given Length
- Spell Out a Word
- Find the Bomb
- Find Nemo
- Check if a String is Empty
- Check if a String starts with a Specific Character
- Check if a String ends with a Specific Substring
- Convert a List to a Comma-Separated String
- Remove Whitespace from a String
- Remove Duplicates from a String
- Remove Vowels from a String
- Reverse the Order of Words in a Sentence
- Count the Number of Words in a String
- Count the Letters in a String (case-insensitive)
- Count the Occurrences of a Character in a String
- Double Letter Checker
- Shhh Whisperer
- Hacker Speak Converter
- Compact Phone Number Formatter
- Vowel Dasher
- Validate Vowel Sandwich

### List Operations
- Check If a List is Empty
- Get the Last Element of a List
- Get the First N Elements of a List
- Get the Last N Elements of a List
- Check if All Elements in a List are the Same
- Check if a List Contains Only Unique Values
- Find the Index of an Element in a List
- Remove a Specific Element from a List
- Find the Difference Between Two Lists
- Find the Intersection of Two Lists
- Find the Longest Common Prefix in a List of Strings
- Shuffle a List
- Generate an Array of Consecutive Numbers
- Generate an Array of Random Numbers
- Generate an Array of Random Numbers within a Range
- Sum of Index Multiplied Elements
- Count True Values in a Boolean List
- Find the Average of Even Numbers in a List
- Find the Average of Odd Numbers in a List
- Find the Maximum Value in a List of Objects
- Check if a List is a Subset of Another List
- Check if a List is Sorted in Ascending Order
- Check if a List is Sorted in Descending Order

### Date & Time Operations
- Check if a Date is Valid
- Get the Current Date in DD/MM/YYYY Format
- Get the Current Year
- Get the Current Month (0-based index)
- Get the Month Name from a Date
- Get the Day of the Week from a Date
- Find the Day of the Year
- Find the Number of Days Between Two Dates
- Find the Difference Between Two Dates in Days
- Check if a Year is a Leap Year
- Century from Year

### Number Theory & Checks
- Check if a Number is Even or Odd
- Check if a Number is Odd
- Check if a Number is a Multiple of 5
- Check if a Number is a Power of Two
- Check if a Number is a Prime Number
- Find the Largest Prime Factor of a Number
- Find the Factors of a Number (excluding 1 and the number itself)
- Check if a Number is a Fibonacci Number
- Check if a Number is a Perfect Square
- Check if a Number is a Neon Number
- Check if a Number is a Disarium Number
- Check if a Number is a Pronic Number
- Check if a Number is a Prime Factor of Another Number
- Check if a Number is a Pronic Square
- Check if a Number is a Happy Number
- Check if a Number is a Power of Another Number
- Find the Sum of the First N Natural Numbers
- Find the Odd Occurrence

### Validation & Checks
- Validate Number Within Bounds
- Validate Zip Code
- Check if an Object is Empty
- Check if a String is a Valid Email Address
- Check if a String is a Valid Date (YYYY-MM-DD Format)
- Check if a String is a Valid Phone Number (North American Format)
- Check if a String is a Valid Social Security Number (SSN)
- Check if a String is a Valid Credit Card Number
- Check if a String is a Valid Password
- Check if a String is a Pangram

### Randomization & Probability
- Generate a Random Number within a Range
- Generate a Random Number between 1 and 10
- Generate Random Hex
- Create Random Strings
- Shuffle the Characters of a String
- Maurice's Racing Snails
- Loaded Die Detection
- Patterns & Sequences
- Pyramid Pattern
- Matchstick Count in Steps
- Recursive Right Shift Mimicker
- Collatz Sequence Analyzer
- Symmetry Checker

### Miscellaneous
- Join Path Portions
- Find the First Non-Repeated Character in a String
- Find the Minimum and Maximum Numbers in a List
- Maximum Triangle Edge Calculator
- Billable Days Bonus Calculator
- Discounted Price Calculator
- Stolen Items Loss Calculator
- Hand Washing Duration Calculator
- BBQ Skewer Analyzer
-  Diving Minigame Checker
- Roger's Shooting Score Calculator
- Chinese Zodiac Sign Identifier
- XO Checker
- One-Liner Bitwise Operations in Python
- World Landmass Proportion Calculator

---

## Mathematical Operations
### Convert Celsius to Fahrenheit
The **celsius_to_fahrenheit** function converts Celsius to Fahrenheit.

```
def celsius_to_fahrenheit(celsius): return (celsius * 9/5) + 32

print(celsius_to_fahrenheit(25)) 
# Output: 77.0°F (25°C converted to Fahrenheit)
```

<details>
  <summary><b>Walktrought:</b></summary>
  <br/>

#### Step 1: Define the Function

```
def celsius_to_fahrenheit(celsius):
    return (celsius * 9/5) + 32
```

The function **celsius_to_fahrenheit** takes one parameter, celsius, which represents the temperature in degrees Celsius.

It multiplies the Celsius value by **9/5** and adds **32** to get the equivalent Fahrenheit temperature.

#### Step 2: Understanding the Formula**

**The conversion formula between Celsius and Fahrenheit is:**

```
F = (C × 9/5) + 32
```

**Where:**

```
C is the temperature in Celsius.

F is the temperature in Fahrenheit.
```

**For example, if we input 25°C into the function:**

```
F = (25 × 9/5) + 32
F = (25 × 1.8) + 32
F = 45 + 32
F = 77
```

#### Step 3: Call the Function

```
print(celsius_to_fahrenheit(25))
```

This calls the function with 25 as the input, meaning celsius = 25.

The function returns 77.0, which is printed to the console.

#### Step 4: Expected Output

```
77.0
```

This means **25°C** is equivalent to **77°F**.

#### Final Code with a More User-Friendly Output

**If you want a more readable output:**

```
celsius = 25
fahrenheit = celsius_to_fahrenheit(celsius)
print(f"{celsius}°C is equal to {fahrenheit}°F")
```

Output:

```
25°C is equal to 77.0°F
```

Now you can convert any Celsius value to Fahrenheit using this function! 🔥
  
</details>

### Convert RGB to Hex
### Simple Sum
### Calculate the Area of a Circle
### Calculate the Power of a Number
### Sum of Numbers up to a Given Number
### Sum all Numbers in a List
### Find the Maximum Value in a List
### Find the Minimum and Maximum Numbers in a List
### Calculate the Sum of Squares of a List
### Calculate the Sum of Cubes of a List
### Find the Mode of a List of Numbers
### Generate a Fibonacci Sequence
### Find the Nth Fibonacci Number (recursive)
### Find the Nth Fibonacci Number
### Calculate the Standard Deviation of a List of Numbers
### Generate multiplication table
### Calculate PI to N Decimal Places
### Calculate the Perimeter of a Rectangle
### Calculate the Exponential of a Number
### Calculate the Hypotenuse of a Right-Angled Triangle
### Calculate the Volume of a Sphere
### Calculate the Volume of a Cylinder
### Calculate the Volume of a Cube
### Calculate the Area of a Triangle given the Base and Height
### Convert Degrees to Radians
### Convert Feet to Meters
### Convert Minutes to Seconds
### Convert Seconds to HH:MM:SS Format
### Convert Seconds to Minutes and Seconds
### Convert Seconds to Hours, Minutes, and Seconds
### Convert Days to Years, Months, and Days
### Convert Decimal Number to Octal
### Convert Decimal Number to Hexadecimal
### Convert Binary Number to Decimal
### Convert DNA to RNA

---

## Grab your copy:
| Book Cover |  Digital Book (PDF) | Physical Book |    
|----|----|----|
| [<img src="https://github.com/user-attachments/assets/36001965-6f05-426e-bfb8-39d14eb9090a" width="300px">](#) | [<img src="https://github.com/user-attachments/assets/9a6a1546-c29c-4a6c-815d-9150edeb74a7">](hernandoabella.gumroad.com/l/oqsrp) | [<img src="https://github.com/user-attachments/assets/3b79de6e-9469-49ee-aa48-9a283604a648">](https://www.amazon.com/-/es/Hernando-Abella-ebook/dp/B0D442PCLX) |

Made with ❤️ & ☕by [Hernando Abella](https://www.github.com/hernandoabella)
