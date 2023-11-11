# lib
```
cd libzkp
cargo build --release
find ./ | grep libzktrie.so  | xargs -I{} cp {} ../
```

# run
```
安装solc: 0.8.19
wget https://circuit-release.s3.us-west-2.amazonaws.com/setup/params20
wget https://circuit-release.s3.us-west-2.amazonaws.com/setup/params24
wget https://circuit-release.s3.us-west-2.amazonaws.com/setup/params26
cargo build --release
targer/release/prover_batch
```
