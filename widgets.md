---
description: Some stuff I’ve created for the sake of it
---

# Miscellaneous Widgets

Incomplete catalog of small-scale projects I’ve developed or participated in.

## Websites

- [Ed25519 quirks](https://quirks.ed25519.info/) ([open-source](https://github.com/slowli/ed25519-quirks)),
  a website about quirks of the Ed25519 digital signature cryptosystem.
- [Just Web Token](https://justwebtoken.io/) ([open-source](https://github.com/slowli/justwebtoken.io)),
  an education website about JSON Web Tokens (JWTs) that allows parsing and verifying tokens.
- [Elasticpoll](https://elasticpoll.app/) ([open-source](https://github.com/slowli/elasticpoll.app)),
  a web application that allows organizing single-choice and multi-choice polls
  that combine privacy and universal verifiability with the help of some applied cryptography.
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
- [`pwbox`](https://docs.rs/pwbox/). Passphrase-based encryption with customizable
  cryptographic backends.
- [`jwt-compact`](https://docs.rs/jwt-compact/). JSON Web Token implementation
  focused on supporting compact claim serialization with [CBOR] and support
  of alternative cryptosystems.
- [`ocl-convolution`](https://docs.rs/ocl-convolution/). [OpenCL] implementation
  of quantized [convolution] layers for deep neural networks.
- [`elastic-elgamal`](https://docs.rs/elastic-elgamal/). [ElGamal encryption]
  and related cryptographic protocols (such as various zero-knowledge proofs)
  with a pluggable crypto backend.
- [`externref`](https://docs.rs/externref/). Low-cost reference type (aka `externref` and `anyref`)
  shims for WASM modules.
- [`term-transcript`](https://docs.rs/term-transcript/). Snapshot creation
  and testing for CLI / REPL applications.
- [`tracing-capture`](https://docs.rs/tracing-capture/) and [`tracing-tunnel`](https://docs.rs/tracing-tunnel/).
  Tools for the `tracing` framework allowing to capture tracing spans / events, and to propagate
  them across an opaque boundary (e.g., when running WASM modules using `wasmtime` or another WASM engine).

[CBOR]: https://cbor.io/
[OpenCL]: https://www.khronos.org/registry/OpenCL/
[Vulkan]: https://www.khronos.org/registry/vulkan/
[convolution]: https://en.wikipedia.org/wiki/Convolutional_neural_network
[ElGamal encryption]: https://en.wikipedia.org/wiki/ElGamal_encryption

## NPM Packages

- [`chai-bytes`](https://www.npmjs.com/package/chai-bytes). Easy assertions on byte arrays
  based on [Chai](https://chaijs.com/).
- [`julia-set`](https://www.npmjs.com/package/julia-set),
  [`julia-set-node`](https://www.npmjs.com/package/julia-set-node).
  Rendering Julia set fractals with the help of WebGL (and Puppeteer in the case of Node).
- [`bech32-buffer`](https://www.npmjs.com/package/bech32-buffer). Bech32(m) encoding
  for Bitcoin adderesses and other applications. The demo website
  [is also available](https://slowli.github.io/bech32-buffer/).
