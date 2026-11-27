# Exercise 7 - Imports

Create a file `greet.kj` in the same directory as your program:

```koji
export function greet(name: string): string {
    return `Hello, ${name}!`
}

export function farewell(name: string): string {
    return `Goodbye, ${name}!`
}
```

Now, in your main program:

- Import both functions from `greet.kj`.
- Print `greet('Koji')` and `farewell('Koji')`.

Expected output:

```
Hello, Koji!
Goodbye, Koji!
```

Then, try:

- Importing the whole module (`import greet`) and calling `greet.greet('Koji')`.
- Removing the import. Observe the compiler error.