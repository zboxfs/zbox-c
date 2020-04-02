# zbox-c

C/C++ binding for [ZboxFS].

## Requirements

- [Rust] stable >= 1.38
- [libsodium] >= 1.0.17

## How to use

### Compile and install

```sh
./autogen.sh
./configure
make && make check && make install
```

## How to upgrade to latest version from [ZboxFS]

1. Change version number in `configure.ac` (line 5-7)
2. Change version number in dependencies section in `zbox-binding/Cargo.toml`
3. run `make` to build the library

[ZboxFS]: https://github.com/zboxfs/zbox
[Rust]: https://www.rust-lang.org
[libsodium]: https://libsodium.org
