# Calorie Counter with Form Validation

This is a simple web application that allows users to input their daily calorie intake and expenditure, and calculate their net calorie balance. The application also includes form validation to ensure that the user input is valid before performing calculations.

## Features

- User input fields for calorie intake and expenditure
- Validation for user input to ensure it is a valid number
- Calculation of net calorie balance (intake - expenditure)
- Display of the calculated net calorie balance
- Visual indication of surplus or deficit based on the net calorie balance

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

1. Clone the repository:

```
git clone https://github.com/your-username/calorie-counter.git
```

2. Open the `index.html` file in your preferred web browser.

## Usage

1. Enter your daily calorie intake in the "Calorie Intake" input field.
2. Enter your daily calorie expenditure in the "Calorie Expenditure" input field.
3. Click the "Calculate" button or press Enter.
4. The application will validate the input and calculate the net calorie balance.
5. The net calorie balance will be displayed on the page, along with a visual indication of surplus or deficit.

## Form Validation

The application uses regular expressions and other validation techniques to ensure that the user input is valid before performing calculations. The following validations are implemented:

- Input fields cannot be empty
- Input values must be numeric
- Input values cannot be negative

If any of the validations fail, an error message will be displayed, and the calculation will not be performed until valid input is provided.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
