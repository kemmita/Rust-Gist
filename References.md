```rust
fn main() {
    let msg:String = String::from("Garage");
    let other_msg:String = String::from("Garage");
    let small:i8 = 122;
    // Here we pass the address from the st
    do_it(msg, &other_msg, &small);
}

fn do_it(s : String, t:&String, x:&i8) {
    // s is passed in and after it is used it will be removed from the heap so it will no longer be visible in the parent function
    println!("{}", s);

    // with t we do not create a new copy of the var in heap, we take a pointer to the address where the value is living in the heap
    // The value will always be de-referenced automatically, we could also manually do (*t)
    println!("{}", t);

    // If your function needs to take ownership of the data, pass by value. If your function only needs to read the data, pass a reference.
    // If your function needs to change the data, pass a mutable reference.
    println!("{}", x)
}
```
