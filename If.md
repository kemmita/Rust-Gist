```rust
fn main() {
    let num:u8 = 23;
    // Traditional For Loop
    if num == 5{
        print_message("Five")
    } else if  num < 123 {
        print_message("Tree")
    } else {
        print_message("Invalid")
    }

    // Assign a value to a var from the result of the if expression
    let msg = if num == 5{
        "Five"
    } else if  num < 123 {
        "Number"
    } else {
        "Invalid"
    };
    println!("{}", msg)

}
```
