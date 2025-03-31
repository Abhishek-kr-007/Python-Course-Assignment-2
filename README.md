# Python-Course-Assignment-2

# TASK-1

# README.md

## Check Even or Odd

This Python script checks whether a given integer is even or odd. It prompts the user to enter an integer and then displays the result.

### Features

- Prompts the user for input.
- Validates the input to ensure it is an integer.
- Identifies and prints whether the number is even or odd.
- Handles invalid input gracefully with error messages.

### Code Explanation

- **Function Definition**: 
  - The function `check_even_odd()` is defined to encapsulate the logic for checking even or odd numbers.

- **Input Handling**:
  - The script uses `input()` to take user input and attempts to convert it into an integer using `int()`. 

- **Even or Odd Check**:
  - It checks if the number is divisible by 2 using the modulus operator `%`.
  - If the remainder is `0`, the number is even; otherwise, it is odd.

- **Error Handling**:
  - A `try-except` block is used to catch `ValueError`, which handles situations where the input is not a valid integer.

### Usage

1. Clone or download the repository.
2. Open a terminal or command prompt.
3. Run the script using Python:

    ```bash
    python <script_name>.py
    ```

4. Follow the prompt to enter an integer.

### Example Output

```
Enter an integer: 4
4 is an even number.
```

```
Enter an integer: 5
5 is an odd number.
```

```
Enter an integer: hello
Invalid input! Please enter an integer.
```

### Requirements

- Python 3.x

### Author

- Abhishek Kumar 

### License

This project is open-source and available under the [MIT License](LICENSE).


# TASK-2

# README.md

## Sum 1 To 50

This project contains a simple Python script that calculates the sum of all integers from 1 to 50.

### Overview

The `sum_numbers` function initializes a total variable to zero and iterates through the range of numbers from 1 to 50, adding each number to the total. Finally, it prints the total sum.

### Code Explanation

- **Function Definition**: The function `sum_numbers` is defined to carry out the addition.
- **Initialization**: A variable `total` is initialized to store the cumulative sum.
- **Loop**: A `for` loop iterates through numbers from 1 to 50 (inclusive).
- **Accumulation**: Each number is added to `total`.
- **Output**: The function prints the result in a formatted string.

### Code Snippet

```python
def sum_numbers():
    total = 0
    for num in range(1, 51):
        total += num
    print(f"The sum of numbers from 1 to 50 is: {total}")

if __name__ == "__main__":
    sum_numbers()
```

### How to Run

1. Ensure you have Python installed on your computer.
2. Copy the code into a Python file, e.g., `sum_numbers.py`.
3. Run the script using the following command in your terminal:

   ```bash
   python sum_numbers.py
   ```

### Expected Output

Upon running the script, you should see the following output:

```
The sum of numbers from 1 to 50 is: 1275
```

### Contributions

Feel free to fork this repository and submit a pull request if you wish to contribute. Any enhancements or improvements are welcome!

### License

This project is licensed under the MIT License. See the LICENSE file for details.

