# sigrok-sys

Rust bindings to [libsigrok](https://sigrok.org/wiki/Libsigrok).

```
cargo run --bin bindgen -- ../sigrok-sys/include/libsigrok.h -builtins > ../sigrok-sys/src/lib.rs
```

## License

GPL-3.0
