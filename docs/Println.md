# **Println**

* Macros expand into additional variables code.
* `println` is a macro.
* `println` "prints" (display) information that is result just like `console.log` to the terminal.
* Useful for debugging.

`println!` - indicate a macro instead of a function.

`{:?}` the `:?` token is for debugging purposes. Macros use an excalamation to call/invoke generate additional rust code. Data can be printed using `println!`.

For examples:

```rust
let life = 42;
println!("Hello"); // prints Hello
```

```rust
println!("{:?}", life); // 
```

```rust
println!("life}"); // prints
```
