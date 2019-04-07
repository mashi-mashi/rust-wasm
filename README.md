## rust

```
curl https://sh.rustup.rs -sSf | sh
```

## PATH

```
source ~/.zsh_profile
```

```
rustup install nightly
```

```
rustup target add wasm32-unknown-unknown --toolchain nightly
```

## build

```
rustc +nightly --target wasm32-unknown-unknown -O src/lib.rs --crate-type=cdylib
```
