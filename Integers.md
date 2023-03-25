```rust
fn main() {
    // All of the below int types also have unsigned versions
    let local_var_tiny:i8 = 127; // i8 can hold values from -128 to 127
    let local_var_small:i16 = 32767; // i16 can hold values from -32768 to 32767
    let local_var_medium:i32 = 2147483647; // i32 can hold values from -2147483648 to 2147483647
    let local_var_large:i64 = 2147483647; // i64 can hold a large number
    let local_var_giant:i128 = 2147483647; // i128 can hold a huge flipen number

    println!("{}", local_var_giant);
}

```
