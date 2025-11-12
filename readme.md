# Pikchr WASM

> Pikchr (pronounced "picture") is a PIC-like markup language for diagrams in technical documentation.  https://pikchr.org/

This project is Pikchr compiled to WebAssembly to run in the browser and elsewhere. 

#### File structure

* `Makefile` to use Emscripten (https://emscripten.org) to compile it to WASM
* `pikchr.c` built by `pikchr` library
* `pikchr.js` the WASM module
* `pikchr.mjs` same as above but as ES6 module
* `index.html` see https://eliot-akira.github.io/pikchr-wasm/

#### References

- https://github.com/drhsqlite/pikchr
- https://github.com/fabiospampinato/pikchr-wasm
- https://github.com/felixr/pikchr-wasm
