# anti reindeer

```sh
git clone https://github.com/kamimrcht/anti_reindeer.git
cd anti_reindeer
```

Install Rust nightly: [rustup.rs](https://rustup.rs/) then `rustup install nightly`.

```sh
cargo +nightly build --release
cargo +nightly test
```

## Index mode

```sh
cd test_files
```

```sh
cargo +nightly run --release -- index test_files/metadata.csv test_files/query2.txt
```

## Query mode

```sh
cd test_files
```

```sh
cargo +nightly run --release -- query test_files/metadata.csv test_files/query2.txt
```

## Useful commands

Update Rust:
```sh
rustup update
```

Update CBL:
```sh
cargo update cbl
```

Format code:
```sh
cargo fmt
```

Show clippy warnings:
```sh
cargo clippy
```

Fix warnings automatically:
```sh
cargo clippy --fix
```
