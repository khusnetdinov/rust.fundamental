# Fundamental Rust
I started this repo due to my path to learning rust lang. I'll keep the order of content according to my learning.

Start from zero point. I'll recommend going step by step.

Introduction:
- [Considering rust presentation](https://www.youtube.com/watch?v=DnT-LUQgc7s) - YouTube
- [Considering rust slides](https://jon.thesquareplanet.com/slides/considering-rust/export.pdf)

First practice:
- [https://www.rust-lang.org/learn](https://www.rust-lang.org/learn) - Rust language web page. Docs, first install instructions.
- [https://doc.rust-lang.org/book/](https://doc.rust-lang.org/book/) - Rust book.
- [https://doc.rust-lang.org/rust-by-example/](https://doc.rust-lang.org/rust-by-example/) - Rust by examples.
- [https://tourofrust.com/](https://tourofrust.com/) - Tour of rust. Interactive playground with examples with annotations.
- [https://github.com/rust-lang/rustlings](https://github.com/rust-lang/rustlings) - Rustling

I recommend before starting to write your project watch these videos:
- [Crust of Rust: Iterators](https://www.youtube.com/watch?v=yozQ9C69pNs)
- [Crust of Rust: std::collections](https://www.youtube.com/watch?v=EF3Z4jdD1EQ)

I learn it on my first pet project:
- [Serde](https://serde.rs/)
- [Crust of Rust: Decrusting the serde](https://www.youtube.com/watch?v=BI_bHCGRgMY) 

Lifetimes with subtyping and variance
- [Crust of Rust: Lifetime Annotations](https://www.youtube.com/watch?v=rAl-9HwD858)
- [LifetimeKata](https://github.com/tfpk/lifetimekata)
- [Subtyping](https://doc.rust-lang.org/nomicon/subtyping.html)
- [Lifetime variance in Rust](https://github.com/sunshowers-code/lifetime-variance)
- [Crust of Rust: Subtyping and Variance](https://www.youtube.com/watch?v=iVYWDIW71jk)
- [rust-blog](https://github.com/pretzelhammer/rust-blog/blob/master/posts/common-rust-lifetime-misconceptions.md)

Macros(Declarative macros [1], Proc macro [2], Proc attribute-like macros [3], Proc function-like macros [4]):
- [The Little Book of Rust Macros](https://danielkeep.github.io/tlborm/book/README.html)[1] - Must read
- [Crust of Rust: Declarative Macros](https://www.youtube.com/watch?v=q6paRBbLgNw)[1]
- [Proc macro workshop](https://github.com/dtolnay/proc-macro-workshop)[2, 3, 4] - lessons for going deep to macros
- [Addition info from David Tolnay about macro learning](https://github.com/dtolnay/proc-macro-workshop/issues/22)
- [Crust of Rust: Procedural Macros in Rust (part 1)](https://www.youtube.com/watch?v=geovSK3wMB8)[2, 3, 4]
- [Crust of Rust: Procedural Macros in Rust (part 2)](https://www.youtube.com/watch?v=KVWHT1TAirU)[2, 3, 4]
- [More for reading](https://github.com/dtolnay/case-studies)

Orphan rule, Coherence rules:
- [Orphan rule, newType pattern and TraitWrapper](https://www.linkedin.com/pulse/orphan-rule-newtype-pattern-traitwrapper-amit-nadiger#:~:text=The%20orphan%20rule%20in%20Rust%20states%20that%20you%20can%20only,type%20directly%20in%20your%20crate.)
- [Coherence and Orphan Rules in Rust](https://github.com/Ixrec/rust-orphan-rules)

Pointers:
- [Crust of Rust: Smart Pointers and Interior Mutability](https://www.youtube.com/watch?v=8O0Nt9qY_vo)
- [Crust of Rust: Dispatch and Fat Pointers](https://www.youtube.com/watch?v=xcygqF5LVmM)
- [What are Rust's exact auto-dereferencing rules?](https://stackoverflow.com/questions/28519997/what-are-rusts-exact-auto-dereferencing-rules/28552082#28552082)
- [Crust of Rust: The Drop Check](https://www.youtube.com/watch?v=TJOFSMpJdzg)

Hazard pointers:
- [Crust of Rust: Implementing Hazard Pointers in Rust 1](https://www.youtube.com/watch?v=fvcbyCYdR10)
- [Crust of Rust: Implementing Hazard Pointers in Rust 2](https://www.youtube.com/watch?v=_LK7qvBWNYo)
- [Crust of Rust: Implementing Hazard Pointers in Rust 3](https://www.youtube.com/watch?v=tGn0mQF0804)
- [Crust of Rust: Implementing Hazard Pointers in Rust 4](https://www.youtube.com/watch?v=3oL1xokuHBE)

Futures, Channels, Concurrency:
- [Crust of Rust: async/await](https://www.youtube.com/watch?v=ThjvMReOXYM)
- [Crust of Rust: The What and How of Futures and async/await in Rust](https://www.youtube.com/watch?v=9_3krAQtD2k)
- [Crust of Rust: The Why, What, and How of Pinning in Rust](https://www.youtube.com/watch?v=DkMwYxfSYNQ)
- [Crust of Rust: Channels](https://www.youtube.com/watch?v=b4mS5UPHh20)
- [Crust of Rust: Send, Sync, and their implementors](https://www.youtube.com/watch?v=yOezcP-XaIw)
- [Crust of Rust: Atomics and Memory Ordering](https://www.youtube.com/watch?v=rMGWeSjctlY)
- [Crust of Rust: Decrusting the tokio crate](https://www.youtube.com/watch?v=o2ob8zkeq2s)
- [Optional: Mini redis implementation with tokio as example for learning](https://github.com/tokio-rs/mini-redis)
- [Optional: Crust of Rust: A Cool Generic Concurrency Primitive in Rust](https://www.youtube.com/watch?v=eLNAMEoKAAc)

Tracing, compiling:
- [Crust of Rust: Decrusting the tracing crate](https://www.youtube.com/watch?v=21rtHinFA40)
- [Crust of Rust: Making a Rust crate compile faster](https://www.youtube.com/watch?v=pMiqRM5ooNw)
- [Crust of Rust: Build Scripts and Foreign-Function Interfaces (FFI)](https://www.youtube.com/watch?v=pePqWoTnSmQ)

Readging:
- [Rust API Guidelines](https://doc.rust-lang.org/nightly/style-guide/index.html)
- [The Rustonomicon](https://doc.rust-lang.org/stable/nomicon/)
- [Rust Style Guide](https://doc.rust-lang.org/nightly/style-guide/index.html)
- [Rust Language Cheat Sheet](https://cheats.rs/)

Posts:
- [An Introduction to Rust Memory Distribution](https://www.alibabacloud.com/blog/an-introduction-to-rust-memory-distribution_600132)
- [How to Use Rust Traits, Generics and Bounds](https://rsdlt.github.io/posts/rust-trait-super-generic-polymorphism-subtrait-supertrait-bounds/)

Check your self:
- [rust-quiz](https://dtolnay.github.io/rust-quiz/1)
