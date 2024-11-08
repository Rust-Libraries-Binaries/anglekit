## Archived Repository

**This repository was a gift from me to the Rust and open-source community. It is no longer actively maintained and has been archived. Feel free to fork and continue development on your own.**

# Anglekit

**Anglekit** is a Rust library for converting angles between degrees and radians.

## Usage

Add **anglekit** to your `Cargo.toml`:

```toml
[dependencies]
anglekit = "0.1.0"
```
## Examples
```rust
use anglekit::{degrees_to_radians, radians_to_degrees};

fn main() {
    let degrees = 90.0;
    let radians = degrees_to_radians(degrees);
    println!("{} degrees is {} radians", degrees, radians);

    let radians = std::f64::consts::PI;
    let degrees = radians_to_degrees(radians);
    println!("{} radians is {} degrees", radians, degrees);
}
```
## License

This project is licensed under the MIT License.

## Author
Ben Santora 
