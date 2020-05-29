## _Life_ Core Crate
[wasm-bindgen]:(https://github.com/rustwasm/wasm-bindgen)
[console_error_panic_hook]:(https://github.com/rustwasm/console_error_panic_hook)
[wee_alloc]:(https://github.com/rustwasm/wee_alloc)
#### Build Core Crate
```
$ wasm-pack build
```
#### Test in Headless Browser
```
$ wasm-pack test --headless --firefox
```
#### More Build Information
```
$ cargo --help
$ wasm-pack --help
```
#### Further Reading
- [`wasm-bindgen`][wasm-bindgen] - For communicating between WebAssembly and JavaScript.
- [`console_error_panic_hook`][console_error_panic_hook] - For logging panic messages to the developer console.
- [`wee_alloc`][wee_alloc] - An allocator optimized for small code size.
