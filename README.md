教程地址
https://tokio.rs/tokio/tutorial

关了以前的服务
sudo lsof -i :6379
kill -9 <pid>

启动服务
RUST_LOG=debug cargo run --bin mini-redis-server


cargo run --example hello_world
cargo run --example sub
cargo run --example pub


cargo run --bin mini-redis-cli set foo bar
cargo run --bin mini-redis-cli get foo