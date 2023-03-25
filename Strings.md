```rust
    // allocated on the stack
    let msg:&str = "table";
    println!("{}", msg);

    // allocated on the heap as this string can be changed and thus the size is dynamic and on the heap so it will be slower
    let msg_another:String = String::from("Garage");
    println!("{}", msg_another);
```
