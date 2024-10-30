# Anglekit

**Anglekit** is a Rust library for converting angles between degrees and radians.

## Usage

Add **anglekit** to your `Cargo.toml`:

```toml
[dependencies]
anglekit = "0.1.0"
```
## Examplesuse anglekit::{degrees_to_radians, radians_to_degrees};

```rust

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

