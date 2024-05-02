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
- [Crust of Rust: Lifetime Annotations](https://www.youtube.com/watch?v=rAl-9HwD858)
- [LifetimeKata](https://github.com/tfpk/lifetimekata)
- [Subtyping](https://doc.rust-lang.org/nomicon/subtyping.html)
- [rust-blog](https://github.com/pretzelhammer/rust-blog/blob/master/posts/common-rust-lifetime-misconceptions.md)

I learn it on my first pet project:
- [Serde](https://serde.rs/)
- [Crust of Rust: Decrusting the serde](https://www.youtube.com/watch?v=BI_bHCGRgMY) 

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
