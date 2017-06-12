# Rust LLVM headers

Unfortunately Rust dist doesn't provide LLVM headers from the build. In some cases too much effors has to be made to get the headers from correct version.
They might be useful for builing custom LLVM passes or with `#![feature(rustc_private)]`.

The headers were generated for `rustc 1.19.0-dev (d7798c3d1 2017-06-02)` on `x86_64-unknown-linux-gnu` host.

In theory they are host platform independed, but this must be verified :)