cd ..

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

. "$HOME/.cargo/env"

time cargo run --release --bin wasmi_cli test/fib32.wasm --invoke fib 40

9.0s

cd ..

git clone 

cd tinywasm https://github.com/explodingcamera/tinywasm

cd exampes/rust

./build.sh

cd ../../crates/cli

cargo run --release run ../../examples/rust/out/fibonacci.wasm -f fibonacci_recursive -a 'i32:40'

> take longer than 30s

cd ../../../../

git clone https://github.com/rhysd/wain

cd wain

vim exampes/fib.wat -> change to call fib 40

cargo run --release -- examples/fib.wat

> take longer than 30s
