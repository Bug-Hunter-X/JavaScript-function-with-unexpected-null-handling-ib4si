# JavaScript Function with Unexpected Null Handling

This repository demonstrates a common JavaScript error involving null handling in a simple addition function. The original code handles explicit null values gracefully; however, it lacks robust error handling for other unexpected input types.

## Bug Description

The `foo` function adds two numbers. The function correctly handles `null` values.  However, it doesn't handle cases where the input isn't a number or `null`, leading to potential type errors or unexpected output. For example, passing strings or objects could lead to unexpected behavior.

## Solution

The solution incorporates type checking to ensure that only numbers are used in the addition.  This prevents the function from producing incorrect results or throwing errors.  Additionally, a more descriptive error message is provided if non-numeric inputs are given. 