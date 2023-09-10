# Python Tips & Tricks

#### 1. Use Guard clause
By moving the guard clause to the beginning of the function, the code now looks cleaner and more readable. You have a set of checking codes right at the beginning of the function to keep track of. Additionally, it help to reduce the indentation complexity of the code.

```python
# Without guard clause
def calc_square_root(float: number):
  """Calculate the square root of a number."""
  if number >= 0:
    return x ** 0.5
  else:
    return None

# Add guard clause
def calc_square_root(float: number):
  """Calculate the square root of a number."""
  if number < 0:
    return None

  return x ** 0.5
```

## References:
- https://medium.com/lemon-code/guard-clauses-3bc0cd96a2d3
- https://python.plainenglish.io/8-quick-refactoring-tips-to-make-your-code-cleaner-and-more-pythonic-a8110edb74fb
