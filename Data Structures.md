```rust
fn main() {
    // Tuples can hold a max of 12 items
    let stuff:(i32, i8, f64) = (12,3,2334.3);
    println!("{}", stuff.2);
    // Arrays can hold a max of 32 items
    let arr:[i32;3] = [12,2345,34554];
    
    // Loop over arr
    for num in arr.iter() {
        println!("{}", num)
    }
}
```
