# unsegen_signals

[![](https://img.shields.io/crates/v/unsegen_signals.svg)](https://crates.io/crates/unsegen_signals/)
[![](https://docs.rs/unsegen_signals/badge.svg)](https://docs.rs/unsegen_signals/)
[![](https://img.shields.io/crates/l/unsegen_signals.svg)]()

`unsegen_signals` uses [unsegen](https://crates.io/crates/unsegen)'s input module to raise signals on the usual key combinations (e.g., SIGINT on CTRL-C).

## Getting Started

`unsegen_signals` is [available on crates.io](https://crates.io/crates/unsegen_signals). You can install it by adding this line to your `Cargo.toml`:

```toml
unsegen_signals = "0.1.0"
```

## Examples

There is an example at the root of the crate [documentation](https://docs.rs/unsegen_signals) which should be sufficient to get you going.

For a fully fledged application using `unsegen_signals`, you can have a look at [ugdb](https://github.com/ftilde/ugdb), which was developed alongside `unsegen` and the primary motivation for it.

## Licensing

`unsegen_signals` is released under the MIT license.
