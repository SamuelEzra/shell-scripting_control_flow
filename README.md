# Linux Control Flow

This project explores control flow in Bash scripting, focusing on if statements and for loops. These constructs allow developers and system administrators to execute conditional operations and iterate over data efficiently in Linux shell scripts.

### Features
- Explanation of if statements for conditional execution
- Use of for loops for iterative tasks
- Real-world examples demonstrating control flow in Linux
- Best practices for writing efficient Bash scripts

### Control Flow Examples
#### `if` Statement Example
The `if` statement allows a script to make decisions based on conditions. Example:

```sh
#!/bin/bash

echo "Enter a number:"
read num

if [ "$num" -gt 10 ]; then
    echo "The number is greater than 10."
else
    echo "The number is 10 or less."
fi
```


Explanation:
- The script prompts the user to input a number.
- The `if` statement checks if the number is greater than 10.
- The appropriate message is displayed based on the condition.

#### `for` Loop Example
A for loop allows iteration over a list of values. Example:

```sh
#!/bin/bash

for i in {1..5}; do
    echo "Iteration $i"
done
```

Explanation:
- The loop runs five times, printing the iteration number.
- {1..5} generates a sequence of numbers from 1 to 5.

### Usage
Review the scripts in the examples/ directory and run them to understand control flow in Linux:

```sh
bash integer.sh
bash control_flow.sh
bash control_flow2.sh
```


