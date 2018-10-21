# rust_wasm

## Prepare the system:

Prerequisites:
- latest nodejs
- latest npm
- rustup

Set rust nightly as default
```
rustup default nightly
```

Install required tools:
```
cargo install wasm-pack \\
cargo install cargo-generate
```

## Create the project

Create an empty project starting from the rust-wasm-template:
```
cargo generate --git https://github.com/rustwasm/wasm-pack-template
```

## Build
```
wasm-pack build
```
The result files are in the `pkg` folder
