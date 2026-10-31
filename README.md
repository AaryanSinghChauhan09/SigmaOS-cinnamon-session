# SigmaOS-cinnamon-session

## Current implementation

This Rust crate is a metadata-only scaffold. Its public descriptor reports the
Cargo package name and the `scaffold` status; it does not provide operational
component behavior. Session startup, shutdown, and lifecycle management are not implemented.

## Development

```sh
cargo fmt --all -- --check
cargo check --all-targets
```

The descriptor tests check package identity and the declared `scaffold` status
only; they do not exercise session startup, shutdown, or lifecycle behavior.
