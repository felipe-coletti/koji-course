# Exercise 6 - Errors as values

Write a program that:

- Calls `math.sqrt(16)` and `math.sqrt(-1)`.
- Uses `match` to handle both `Ok` and `Err` cases for each.
- Prints the result or the error message.

Expected output:

```
4.0
<error message>
```

In a comment at the top of your file, answer in 2–3 sentences: Why does matching on `Ok`/`Err` make it impossible to silently ignore an error?