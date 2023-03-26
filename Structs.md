```rust
// Structs are used to create custom types/classes, the only thing that can be defined here is fields of our object.
struct User {
    username: String,
    email: String,
    sign_in_count: u128,
    active: bool,
}

impl User{
    fn about(&self){
        println!("User {} has email {}", self.username, self.email)
    }
}

fn main() {
    // Create a new instance of User
    let user:User = User{
        username: String::from("cheeses"),
        email: String::from("cheeses@gmail.com"),
        sign_in_count: 0,
        active: false,
    };
    user.about();
    println!("{}", user.get_account());
    user.info()
}
```
