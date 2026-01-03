# API Reference

## main Module

### `add(a, b)`

Add two numbers and return the result.

**Parameters:**
- `a` (int or float): First number
- `b` (int or float): Second number

**Returns:**
- (int or float): Sum of `a` and `b`

**Example:**

```python
from main import add

result = add(2, 3)
print(result)  # Output: 5
```

### `main()`

The main entry point of the application. Prints a greeting and demonstrates the `add()` function.

**Example:**

```bash
python main.py
```

Output:
```
Hello from Python starter project
2 + 3 = 5
```

## Running the Application

To run the application:

```bash
python main.py
```

Or in the virtual environment:

```bash
.venv/Scripts/python main.py  # Windows
source .venv/bin/activate && python main.py  # macOS/Linux
```
