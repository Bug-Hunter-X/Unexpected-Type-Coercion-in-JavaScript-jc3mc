# JavaScript Type Coercion Bug

This repository demonstrates a common JavaScript bug caused by loose typing and implicit type coercion. The `foo` function is intended to add two numbers, but when passed a string, it performs string concatenation instead of numeric addition. This can lead to unexpected behavior and difficult-to-debug errors.

## Bug Description

JavaScript's dynamic typing system allows for implicit type conversion. This can be helpful in some situations, but it can also lead to unexpected results when performing arithmetic operations on mixed data types. In this specific example, passing a string to the `foo` function causes JavaScript to concatenate the string to the number, instead of converting the string to a number and then adding.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js`.
3. Run the code using a JavaScript runtime (Node.js, for example).
4. Observe the unexpected output.