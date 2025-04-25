# The Rules of Crust

<p align=left>
  <img src="./crust.png" width=200>
</p>

1. Every function is unsafe.
1. No references, only pointers.
1. No cargo, build with rustc directly.
1. No std, but libc is allowed.
1. Only Edition 2021.
1. All user structs and enums #[derive(Clone, Copy)].
1. Everything is pub by default.

*The list of rules may change. The goal is to make programming in Rust fun.*
