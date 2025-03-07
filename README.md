# 🛑 ValueError: invalid literal for int() with base 10: 'abc'

## ❓ Why This Happens
Python throws this error because `"abc"` is not a number and cannot be converted to an integer.

## 🔍 Problem Example
```python
print(int("abc") + int("123"))  # ❌ Causes an error
```

## ✅ Correct Code
Only convert valid numbers:
```python
print(int("123") + int("456"))  # ✅ Works correctly
```

