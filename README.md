**About The Project:**
This is a basic level project in which I created a basic BMI calculator using both python and c++ language
**User Input:**
The program repeatedly prompts the user to enter their height and weight using the getValidInput function, which ensures the inputs are positive numeric values.
If the user enters invalid data (non-numeric or non-positive values), the program displays an error message and prompts for input again.

**BMI Calculation:**
Once valid inputs are obtained, the calculateBMI function calculates the BMI using the formula: 
BMI = weight / (height)^2
The program prints the calculated BMI and determines the user's weight category based on standard BMI ranges:
**Underweight:** BMI < 18.5
**Normal weight:** 18.5 ≤ BMI < 25
**Overweight:** 25 ≤ BMI < 30
**Obese:** BMI ≥ 30
The corresponding weight category is then printed.**
**************************************************************************************************************************************************************************************
**TEST CASES**
**Test Case 1:**
Height: 1.75 meters
Weight: 70 kg
**Output:**
Your BMI is 22.86
You are normal weight

**Test Case 2:**
Height: 1.60 meters
Weight: 50 kg
**Output:**
Your BMI is 19.53
You are normal weight

**Test Case 3:**
Height: 1.80 meters
Weight: 85 kg
**Output:**
Your BMI is 26.23
You are overweight

**Test Case 4:**
Height: 1.70 meters
Weight: 50 kg
**Output:**
Your BMI is 17.30
You are underweight
