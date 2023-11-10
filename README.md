# Specialized Power Function with `functools.partial`

A Python script demonstrating the use of `functools.partial` to create a specialized version of a power function.

## Table of Contents

- [Description](#description)
- [Usage](#usage)
- [Output](#output)

## Description

This script showcases the use of the `functools.partial` function to create a specialized version of a power function. The original `power` function takes two arguments, `base` and `exponent`, and calculates `base ** exponent`. By using `partial`, we create a new function called `square` where the `exponent` is fixed at 2. This allows for the creation of specialized functions with pre-set arguments.

## Usage

To use this script, ensure you have Python installed on your system. Copy the code from the script and run it using a Python interpreter.

```bash
python specialize_power.py

## Output

After running the script, you should see the result of the specialized function printed to the console.

# Output: 16
