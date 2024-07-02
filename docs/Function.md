# **Function**

* It is a way of encapsulate program functionality.
* It optionally accept data.
* It optionally return data.
* It utilized for code organisaton.
* It also makess code easier to read and understand.

```rust
fn add(a: i32, b: i32) -> i32{
    a + b
}
```

1. `fn` -  funtion
2. `add` - funtion name
3. `(a: i32, b: i32)` - parameter
4. `-> i32` - return type
5. `{ a + b }` - Function body

Using a fucntion is called **Calling Function** and it can be used anywhere. For example:

```rust
let x = add(1, 2) //retrun 3
let y = add(3, 2) //retrun 5
let z = add(x, y) //retrun 8 because x = 3, y = 5
```
