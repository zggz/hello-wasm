
### step
1. 编译
```sh
GOOS=js GOARCH=wasm go build -o main.wasm main.go
```
2. 引入 JavaScript 支持文件
```sh
 cp "$(go env GOROOT)/misc/wasm/wasm_exec.js" .
 ```