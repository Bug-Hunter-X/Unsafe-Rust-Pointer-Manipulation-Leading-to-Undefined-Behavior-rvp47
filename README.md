# Unsafe Rust Pointer Manipulation

This repository demonstrates a potential issue when working with raw pointers and mutable references in Rust. Modifying a vector through a raw pointer after obtaining a mutable reference can lead to undefined behavior. The `bug.rs` file shows the problematic code, while `bugSolution.rs` presents a safer alternative using proper Rust mechanisms.