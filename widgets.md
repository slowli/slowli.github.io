---
description: Some stuff I’ve created for the sake of it
---

# Miscellaneous Widgets

Incomplete catalog of small-scale projects I’ve developed or participated in.

## Websites

- [Ed25519 quirks](https://quirks.ed25519.info/), a site about quirks of the Ed25519
  digital signature cryptosystem.
- [Fractals](https://fractals.ostrov.ski/) (⚠ in Russian), a website for rendering
  [Julia set](https://en.wikipedia.org/wiki/Julia_set) fractals. 
- [Lectures on software engineering](https://lectures.ostrov.ski/) (⚠ in Russian)

## Rust Crates

- [`arithmetic-parser`](https://docs.rs/arithmetic-parser/),
  [`arithmetic-eval`](https://docs.rs/arithmetic-eval/),
  [`arithmetic-typing`](https://docs.rs/arithmetic-typing/).
  Customizable parser, interpreter and type system for arithmetic expressions.
- [`const-decoder`](https://docs.rs/const-decoder/). Decoding byte buffers from
  hex and base64 encodings in compile time.
- [`julia-set`](https://docs.rs/julia-set/). Rendering Julia set fractals with the help
  of [OpenCL], [Vulkan] or CPU compute.
- [`hex-buffer-serde`](https://docs.rs/hex-buffer-serde/). A small crate allowing
  to customize serialization of byte slices depending on the serializer “compactness”.
- [`secret-tree`](https://docs.rs/secret-tree). Deriving secrets from a single
  secret seed using the Blake2b hash function, in a libsodium-compatible way.
- [`pwbox`](https://docs.rs/pwbox). Passphrase-based encryption with customizable
  cryptographic backends.
- [`jwt-compact`](https://docs.rs/jwt-compact/). JSON Web Token implementation
  focused on supporting compact claim serialization with [CBOR] and support
  of alternative cryptosystems.
- [`ocl-convolution`](https://docs.rs/ocl-convolution). [OpenCL] implementation
  of quantized [convolution] layers for deep neural networks.

[CBOR]: https://cbor.io/
[OpenCL]: https://www.khronos.org/registry/OpenCL/
[Vulkan]: https://www.khronos.org/registry/vulkan/
[convolution]: https://en.wikipedia.org/wiki/Convolutional_neural_network

## NPM Packages

- [`chai-bytes`](https://www.npmjs.com/package/chai-bytes). Easy assertions on byte arrays
  based on [Chai](https://chaijs.com/).
- [`julia-set`](https://www.npmjs.com/package/julia-set),
  [`julia-set-node`](https://www.npmjs.com/package/julia-set-node).
  Rendering Julia set fractals with the help of WebGL (and Puppeteer in the case of Node).
- [`bech32-buffer`](https://www.npmjs.com/package/bech32-buffer). Bech32 encoding
  for Bitcoin adderesses and other applications.
