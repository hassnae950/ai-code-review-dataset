### Task
Write a Python function to check if a number is even.

### AI Generated Code
def is_even(n):
    if n % 2 = 0:
        return True
    else:
        return False

### Issues
- Syntax error: "=" used instead of "=="
- Code can be simplified

### Corrected Code
def is_even(n):
    return n % 2 == 0

### Explanation
The comparison operator must be "==". The function can also be simplified into one line.