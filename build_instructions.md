git clone https://github.com/nschllr/LibAFL.git
cd LibAFL
git checkout 0.4.0  # or your branch name
rustup install 1.75.0
rustup default 1.75.0
cd fuzzers/fuzzbench
cargo build --release
