# **Control Flow using 'if'**

The `if` statement can be used to apply logic to program and can be used to determine which line of code should excute next.

* Code are executed line by line.
* Actions are perfomed and control flow may change.
* Specific conditions can change control flow
e.g.
 `if`, `else`, `else if`

## **Example**

```rust
//if...else
let a = 99;

if a > 99{
    println("Big Number");
}
 else {
    println("Small Number");
}
```

```rust
//Nested if...else
let b = 99;
if b > 99 {
    if b > 300 {
        println!("Huge Number");
    } else {
        println!("Big Number");
    }    
} else {
    println!("Small Number");
}
```

```rust
//if..else if..else
let a = 99;
if a > 200 {
    println!("Huge Number");
} else if a > 99{
    println!("Big Number");
} else {
    println!("small number");
}
```
