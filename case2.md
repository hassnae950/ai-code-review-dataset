### Task
Write a Python function to sum a list.

### AI Generated Code
def sum_list(lst):
    total = 0
    for i in range(len(lst)):
        total = lst[i]
    return total

### Issues
- total overwritten each iteration
- wrong accumulation logic

### Corrected Code
def sum_list(lst):
    total = 0
    for i in range(len(lst)):
        total += lst[i]
    return total

### Explanation
The total variable must accumulate values using +=.