```rust
fn main() {
    println!("{}", meine_func(345.0 , 1.9));
}

// Notice we do not use the return keyword, in Rust the last line is automatically returned from the function
fn meine_func(qty: f64, oz: f64) -> f64 {
    qty * oz
}
```
