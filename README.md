# BMI Calculator 

A simple Bash script that calculates your Body Mass Index (BMI) based on your weight and height, and categorizes the result.

## Features

- Prompts the user to enter their weight (in kilograms) and height (in meters).
- Calculates the BMI using the formula: 
  \[
  \text{BMI} = \frac{\text{weight (kg)}}{\text{height}^2 (\text{m}^2)}
  \]
- Provides a BMI category based on the result:
  - Underweight: BMI < 18.5
  - Normal weight: 18.5 ≤ BMI < 24.9
  - Overweight: 25 ≤ BMI < 29.9
  - Obese: BMI ≥ 30

## Requirements

- **Bash**: The script is designed to run in a Linux/macOS environment using Bash.
- **`bc` (Basic Calculator)**: The `bc` utility is used to perform floating-point arithmetic.

## Usage

1. **Clone this repository**:

   ```bash
   git clone https://github.com/gnaneshwar-p/BMI.git
   cd bmi-calculator
    ```
   output of the site : https://gnaneshwar-p.github.io/BMI/


