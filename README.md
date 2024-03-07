

## Overview
This repository contains Python code for converting numeric values to their string representations. The project is structured into two main files: the implementation of the conversion function and the test suite to verify the correctness of the function.

## Files

### 1. `number_to_string.py`
This file contains a single function `number_to_string` which takes an integer or floating-point number as input and returns its string representation.

#### Usage:
```python
def number_to_string(num):
    return str(num)
```

### 2. `test_number_to_string.py`
This file includes a series of test cases to ensure the `number_to_string` function works as expected across various scenarios, including positive numbers, negative numbers, and expressions resulting in numbers.

#### Dependencies:
- `codewars_test`: A testing framework used to write and run the test cases. Make sure to install this package before running the tests.

#### Test Cases:
- Converts integers to strings, e.g., `67` to `'67'`
- Converts expressions that result in numbers to strings, e.g., `1+2` to `'3'`
- Handles negative numbers, e.g., `-1` remains `'-1'` when converted

#### Running Tests:
To run the tests, ensure you have the `codewars_test` package installed and execute the `test_number_to_string.py` file. The test framework will report the results for each test case.

## Installation
1. Clone this repository to your local machine.
2. Ensure you have Python installed.
3. Install the `codewars_test` package if you plan to run the tests:
   ```sh
   pip install codewars_test
   ```

## Usage
To use the `number_to_string` function in your project, import it from the `number_to_string.py` file and pass a number as an argument:

```python
from number_to_string import number_to_string

string_number = number_to_string(123)
print(string_number)  # Output: '123'
```

## Running Tests
To run the test suite, execute the `test_number_to_string.py` file after ensuring all dependencies are satisfied. Use the following command:

```sh
python test_number_to_string.py
```

The output will indicate whether all test cases pass or if any errors are encountered.

## Contribution
Contributions to this project are welcome. Please ensure to write tests for new features and run existing tests before submitting a pull request.
