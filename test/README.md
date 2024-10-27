cd ..

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

. "$HOME/.cargo/env"

time cargo run --release --bin wasmi_cli test/fib32.wasm --invoke fib 40

9.0s
