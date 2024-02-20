# Dictionaries

## Snippets 

Combine dictionary A and dictionary B *without* overwriting dictionary A's values with dictionary B's.

```python
    for key, value in isle_mapping.items():
        if key in cart:
            cart[key].extend(value)
        else:
            cart[key] = value
```


