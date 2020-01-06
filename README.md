# wasm-pong-rs

WASM-Pong-Rs is Pong-Game which uses Sounds and Simple Graphics. It is using WebAssembly and is written in Rust. 

## Before starting pong

You need Rust on your computer, to run this Pong game. To install Rust on a Linux, you can use the command `curl --proto '=https' --tlsvl1.2 -sSf https://sh.rustup.rs | sh`

To Install Rust a Windows OS you can follow the [link](https:rust-lang.org/tools/install).

## Compiling

The easiest way for compiling this game, is by using [wasm-pack](https://github.com/rustwasm/wasm-pack). After dowloading the wasm-pack you can use the command `wasm-pack build --target=web`

## Running

Start a HTTP Server, for example with python by using a short python-script: `python -c 'import SimpleHTTPServer; SimpleHTTPServer.test()'`

Navigate to localhost:8000 and you can play a round Pong against you or against a friend, it´s your choice! :D

## Controls

The Game is made for 2 Players. The Left Player is controling by `a` for up and `z` for down. The Right Player uses the Arrow Keys for up and down.

