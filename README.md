# punch-card

[![Crates.io](https://img.shields.io/crates/v/punch-card)](https://crates.io/crates/punch-card) [![MIT](https://img.shields.io/crates/l/punch-card)](./LICENSE)

A library for making punched cards like this:

```rust
use punch_card::PunchCard;

#[rustfmt::skip]
println!("{}", std::str::from_utf8(&(
    .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. .. ..,
    ..=..=..=..=..=.. .. .. ..=..=..=..=..=..=.. ..=..=.. ..=..=..=..=..=..=.. ..=..=..=..=..=.. ..=..=..=..=..,
    ..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..=..,
    .. ..=..=..=..=..=.. .. .. ..=.. ..=.. ..=.. .. .. .. .. ..=.. ..=.. ..=.. ..=..=.. .. .. .. .. .. ..=.. ..,
    ..=.. .. .. .. ..=..=..=.. .. .. .. .. .. ..=..=..=..=.. .. .. .. .. .. ..=.. .. ..=.. ..=..=.. .. .. .. ..,
    .. ..=..=.. .. .. ..=..=.. .. .. ..=..=.. ..=.. ..=..=.. .. .. ..=..=.. ..=.. ..=..=.. .. ..=.. .. .. ..=..,
    .. .. .. .. ..=..=..=..=..=..=.. .. .. ..=..=.. ..=..=..=..=.. .. .. ..=..=.. .. ..=..=.. .. ..=.. ..=.. ..,
    .. .. .. .. ..=.. ..=..=..=.. ..=.. ..=..=.. ..=..=..=..=.. ..=.. ..=..=..=.. ..=.. ..=.. ..=..=..=.. .. ..,
).punch_card::<Vec<_>>()).unwrap());
```

For more information, [read the docs](https://docs.rs/punch-card).
