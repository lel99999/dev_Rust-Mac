# dev_Rust-Mac
Rust on Mac Notes

#### Install and check version
```
$brew install rust

## check via homebrew
$brew info rust

## check via rust
$rust --version

## Alternative install, which allows you to switch between rust versions without additional downloads
$brew install rustup
$rustup-init
$rustc --version

## Create binary project via cargo (default) which can be compiled to runnable program
$cargo new testproject

testproject
|-- Cargo.toml
|__ src
   |__ main.rs

## Create library project via cargo
$cargo new --lib testlibproject

testlibproject
|-- Cargo.toml
|__ src
   |__ lib.rs

```

#### IDE
- [https://lapce.dev/](https://lapce.dev/) ** Written in Rust
- [https://github.com/lapce/lapce](https://github.com/lapce/lapce)
- [](https://github.com/helix-editor/helix)

#### Rust built browser form Mozilla
- [https://github.com/servo/servo](https://github.com/servo/servo)
