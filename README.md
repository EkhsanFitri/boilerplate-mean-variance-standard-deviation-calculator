# Mean-Variance-Standard Deviation Calculator

This is the boilerplate for the Mean-Variance-Standard Deviation Calculator project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/mean-variance-standard-deviation-calculator

# Mean-Variance-Standard Deviation Calculator

This project calculates the mean, variance, standard deviation, max, min, and sum of the rows, columns, and elements in a 3x3 matrix using NumPy.

## Usage

- The main function is `calculate()` in `mean_var_std.py`.
- It accepts a list of 9 numbers and returns a dictionary with the calculated statistics.
- If the list does not contain exactly 9 numbers, it raises a `ValueError`.

### Example

```python
from mean_var_std import calculate

result = calculate([0,1,2,3,4,5,6,7,8])
print(result)
```

**Output:**
```python
{
  'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  'variance': [[6.0, 6.0, 6.0], [0.666..., 0.666..., 0.666...], 6.666...],
  'standard deviation': [[2.449..., 2.449..., 2.449...], [0.816..., 0.816..., 0.816...], 2.581...],
  'max': [[6, 7, 8], [2, 5, 8], 8],
  'min': [[0, 1, 2], [0, 3, 6], 0],
  'sum': [[9, 12, 15], [3, 12, 21], 36]
}
```

## Development

- Write your code in `mean_var_std.py`.
- Use `main.py` to test your code.
- Run your code with:
  ```sh
  python main.py
  ```

## Testing

- Unit tests are in `test_module.py`.
- Run tests with:
  ```sh
  python -m unittest test_module.py
  ```

## Submitting

- Push your code to GitHub.
- Copy your repository URL and submit it to freeCodeCamp.

---
This project is part of the freeCodeCamp Data Analysis with Python curriculum.