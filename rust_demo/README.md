

- https://developer.mozilla.org/zh-CN/docs/WebAssembly/Rust_to_wasm

# 前提
- 安装rust
- cargo install wasm-pack
# 编译
1. 构建
- 在打包工具webpack、vite中使用
```sh
wasm-pack build --scope myNpmLib
```

- 或者web, 直接在html使用

```sh
wasm-pack build --target web
```
