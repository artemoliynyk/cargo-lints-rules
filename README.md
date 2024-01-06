# What and why?
Despite Rust and Clippy in particular are pretty strict, they still not strict enough.

There are a lot of nice clippy lint rules which are "allowed" by default, meaning linter won't even notify about the issues.

Which makes perfect sense in general, however there are a lot of the rules which could be used.

## Rules
This is my personal set of allowed rules I like to enable for my Rust projects (including nursery, pedantic and restrictions rules).

### What's allowed
There are a lot of stuff allowed by default in clippy https://rust-lang.github.io/rust-clippy/master/index.html#/?levels=allow
