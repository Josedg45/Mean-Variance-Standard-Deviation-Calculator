# Mean-Variance-Standard Deviation Calculator

## Project Overview

This project implements a Python function to compute the mean, variance, standard deviation, max, min, and sum for a 3x3 matrix. The function uses Numpy for efficient numerical operations and ensures that the input meets the required conditions. The project includes unit tests to verify the correctness of the implementation.

## Features

- **Input Validation**: Ensures the input list contains exactly 9 numbers, raising a `ValueError` if the condition is not met.
- **Numpy Integration**: Utilizes Numpy for efficient matrix operations and calculations.
- **Comprehensive Statistics**: Calculates mean, variance, standard deviation, max, min, and sum along both rows, columns, and the flattened matrix.
- **Dictionary Output**: Returns results in a structured dictionary format, making it easy to interpret and use the computed statistics.

## Usage

To use the `calculate` function, run the `main.py` file. This file demonstrates how to use the function with a sample input and prints the results.

1. **Run the Main Script**:

    ```bash
    python3 main.py
    ```

## Testing

The project includes unit tests to ensure the correctness of the `calculate` function. Run the tests using a Python testing framework to verify that the function works as expected.

1. **Run the Tests**:

    ```bash
    python3 -m unittest test_module.py
    ```

## Running in Gitpod

To run this project in Gitpod, follow these steps:

1. **Open Gitpod**: Navigate to your repository on GitHub and open it in Gitpod by prepending the URL with `https://gitpod.io/#`.

    ```url
    https://gitpod.io/#https://github.com/your_username/your_repository
    ```

2. **Run the Code**: Once the environment is set up, run the main file to see the function in action.

3. **Run Tests**: Execute the tests to ensure the function's correctness.

## Conclusion

This project provides a robust function to calculate essential statistical metrics for a 3x3 matrix, ensuring input validation and leveraging the power of Numpy for efficient computation. The included tests help verify the function's correctness, making it reliable for further use and development.


