```rust
// Only static and const vars can be declared outside of a function
static FILE_LENGTH:i32 = 21;
const PROCESS_TIME:i32 = 23;

fn main() {
    // All let vars are immutable
    let local_var_tiny:i8 = 127;
    
    // Declare multiple vars with tuple unpacking.
    let local_vars:(i8, i8) = (9, 3);

    // Here we can specify a var as mutable
    let mut local_var_to_change_later:i16 = 23;
    local_var_to_change_later = 234;
    println!("{}", local_var_to_change_later);
}
```
