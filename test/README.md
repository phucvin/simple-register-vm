cd ..

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

. "$HOME/.cargo/env"

cargo run

load $1 #500

load $2 #44

add $1 $2 $3

.registers