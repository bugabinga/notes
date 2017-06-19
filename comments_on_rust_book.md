This will mutate to a blog post over time, explaining my experience reading the Rust book Second Edition.

# mutability

- explain "deep" mutability


# numeric conversions (chapter 3.2)

- Will automatic numeric conversions happen?
    No, and this is easy to test.
- How to do numeric conversions?
    No idea, not enough information at this stage
- Which numeric type will be inferred? Smallest possible?
    No idea, how to test the type of a variable during runtime?
- Do numbers overflow?
    During my tests it seemed to only overflow for literal value. Runtime overflow results in panics. Why?

# array element access

- why do some bounds checks not happen during compile time?
    ```rust
    fn main() {
    let a = [1, 2, 3, 4, 5];
    let index = 10;

    let element = a[index];

    println!("The value of element is: {}", element);
    }
    ```
    In this example from the book, the compiler could have known this has to fail.

# expressions (chapter 3.5)

- explain how while, loop and for differ as expressions to if-expression

# ownership (chapter 4.1)

- Why has nobody ever called text types in PLs simply "Text" :)?
- Are there tools that can generate "stack"-"heap"-boxes as in  Figure 4-3 ?
- The difference between passing ownership of a value to a function and passing a mutable, borrowed value is not immediately clear, because these seem to do "the same thing".

# slices (chapter 4.3)

- Why not simply return a &mut String?
- What about &mut slices?
