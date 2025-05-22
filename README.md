# Awesome protobuf [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of useful resources for protobuf


## Contents

- [Documentation](#doc)
- [Linters](#linters)
- [Tools](#tools)
  * [CLI](#tools-cli)
  * [Plugins](#tools-plugins)
- [IDE/Text Editors](#ide)
- [Language specific](#lang)
  * [C++](#lang-cpp)
  * [C#](#lang-csharp)
  * [Go](#lang-go)
  * [Java](#lang-java)
  * [Android](#lang-android)
  * [Swift](#lang-swift)
  * [Python](#lang-python)
  * [JS](#lang-js)
  * [Rust](#lang-rust)
  * [Lua](#lang-lua)
  * [Haskell](#lang-haskell)


<a name="doc"></a>
## Documentation
- [Website](https://developers.google.com/protocol-buffers) - Official documentation.
- [Github Repo](https://github.com/protocolbuffers/protobuf) - Protocol Buffers - Google's data interchange format.
- [Style Guide](https://developers.google.com/protocol-buffers/docs/style) - Style guide for `.proto` files.

<a name="linters"></a>
## Linters
- [protolint](https://github.com/yoheimuta/protolint) - A pluggable linter and fixer to enforce Protocol Buffer style and conventions.

<a name="tools"></a>
## Tools

<a name="tools-cli"></a>
### CLI
- [buf](https://github.com/bufbuild/buf) - A new way of working with Protocol Buffers.

<a name="tools-plugins"></a>
### Plugins
- [protoc-gen-validate](https://github.com/bufbuild/protoc-gen-validate) - protoc plugin to generate polyglot message validators

<a name="ide"></a>
## IDE/Text Editors
- [vscode-proto3](https://github.com/zxh0/vscode-proto3) - Vscode extension for proto3.
- [IntelliJ plugin](https://plugins.jetbrains.com/plugin/14004-protocol-buffers)
- [Protobuf Snippets](https://github.com/Clement-Jean/protobuf-snippets) - Emacs YASnippet snippets for Protocol Buffers

<a name="lang"></a>
## Language specific

<a name="lang-cpp"></a>
### C++
- [Protobuf](https://github.com/protocolbuffers/protobuf) - Main repository.

<a name="lang-csharp"></a>
### C#
- [protobuf-net](https://github.com/protobuf-net/protobuf-net) - Protocol Buffers library for idiomatic .NET.

<a name="lang-go"></a>
### Go
- [Protobuf](https://github.com/golang/protobuf) - Go support for Google's protocol buffers.

<a name="lang-java"></a>
### Java
- [Protobuf](https://github.com/protocolbuffers/protobuf) - Main repository.
- [Wire](https://github.com/square/wire) - gRPC and protocol buffers for Android, Kotlin, and Java.

<a name="lang-android"></a>
### Android
- [Jetpack Datastore](https://developer.android.com/topic/libraries/architecture/datastore#proto-datastore) - Data storage solution that allows you to store key-value pairs or typed objects with protocol buffers.

<a name="lang-swift"></a>
### Swift
- [swift-protobuf](https://github.com/apple/swift-protobuf) - Plugin and runtime library for using protobuf with Swift.

<a name="lang-python"></a>
### Python
- [Protobuf](https://github.com/protocolbuffers/protobuf) - Main repository.
- [proto-plus-python](https://github.com/googleapis/proto-plus-python) - Beautiful, idiomatic protocol buffers in Python.

<a name="lang-js"></a>
### JS
Researched by [@nikelborm](https://github.com/nikelborm/) a list of available solutions related to generation of JS/TS (at 21 may 2025). Testing results provided by [bufbuild/protobuf-conformance](https://github.com/bufbuild/protobuf-conformance). 

| NPM                                                                                          | Last published \_ ago | Tests required | Tests optional | TS  | GitHub                                                                                        | Stars | Repo age     | Comment                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| -------------------------------------------------------------------------------------------- | --------------------- | -------------- | -------------- | --- | --------------------------------------------------------------------------------------------- | ----- | ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [@bufbuild/protobuf](https://www.npmjs.com/package/@bufbuild/protobuf)                       | 8 days                | 100%           | 100%           | +   | [bufbuild/protobuf-es](https://github.com/bufbuild/protobuf-es)                               | 1.3k  | 3 years old  | This package provides the runtime library for the [@bufbuild/protoc-gen-es](https://www.npmjs.com/package/@bufbuild/protoc-gen-es) code generator plugin.                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [@bufbuild/protoc-gen-es](https://www.npmjs.com/package/@bufbuild/protoc-gen-es)             | 8 days                | 100%           | 100%           | +   | [bufbuild/protobuf-es](https://github.com/bufbuild/protobuf-es)                               | 1.3k  | 3 years old  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| [@bufbuild/protoplugin](https://www.npmjs.com/package/@bufbuild/protoplugin)                 | 8 days                | 100%           | 100%           | +   | [bufbuild/protobuf-es](https://github.com/bufbuild/protobuf-es)                               | 1.3k  | 3 years old  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| [@protobuf-ts/plugin](https://www.npmjs.com/package/@protobuf-ts/plugin)                     | 19 days               | 99.9%          | 99.9%          | +   | [timostamm/protobuf-ts](https://github.com/timostamm/protobuf-ts)                             | 1.2k  | 5 years old  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| [ts-proto](https://www.npmjs.com/package/ts-proto)                                           | 2 months              | 65.1%          | 5.86%          | +   | [stephenh/ts-proto](https://github.com/stephenh/ts-proto)                                     | 2.4k  | 6 years old  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| [@protobuf-ts/plugin-framework](https://www.npmjs.com/package/@protobuf-ts/plugin-framework) | 19 days               | 99.9%          | 99.9%          | +   | [timostamm/protobuf-ts](https://github.com/timostamm/protobuf-ts)                             | 1.2k  | 5 years old  | [Deprecated](https://github.com/timostamm/protobuf-ts/pull/717) protoc plugin tooling, the author recommends [@bufbuild/protoplugin](https://www.npmjs.com/package/@bufbuild/protoplugin). Also author explained that it relies on an old version of Typescript.                                                                                                                                                                                                                                                                                                                                               |
| [protobufjs](https://www.npmjs.com/package/protobufjs)                                       | 9 months              | 13.6%          | 12.5%          | +   | [protobufjs/protobuf.js](https://github.com/protobufjs/protobuf.js)                           | 10.2k | 9 years old  | Has poor tests results. Didn't have releases for a long time also. Author of [ts-proto](https://www.npmjs.com/package/ts-proto) believes it's aging & stagnant, and migrated from it to [@bufbuild/protobuf](https://www.npmjs.com/package/@bufbuild/protobuf). Even though it can generate typescript, the whole repo is written in pure javascript.                                                                                                                                                                                                                                                          |
| [protoc-gen-js](https://www.npmjs.com/package/protoc-gen-js)                                 | 4 months              |                |                | -   | [yinzara/protoc-gen-js](https://github.com/yinzara/protoc-gen-js)                             | 6     | 6 years old  | It's packaged [protocolbuffers/protobuf-javascript](https://github.com/protocolbuffers/protobuf-javascript) protoc plugin binary. It's purely a wrapper.                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| [protoc-gen-ts](https://www.npmjs.com/package/protoc-gen-ts)                                 | 2 years               | 20.8%          | 27.6%          | +   | [thesayyn/protoc-gen-ts](https://github.com/thesayyn/protoc-gen-ts)                           | 379   | 6 years old  | Haven't been publishing for a long time, doesn't pass conformance tests according to [this](https://github.com/bufbuild/protobuf-conformance/tree/main/impl/protoc-gen-ts). Also [maintainer's quite busy](https://github.com/thesayyn/protoc-gen-ts/issues/255#issuecomment-2733953351) and this project is not a priority for them right now. The version inside NPM is written in TS, however the maintainer was going to rewrite it to rust, because TS version is slow to compile and for [a few other reasons](https://github.com/thesayyn/protoc-gen-ts/issues/255). This rust version is not finished. |
| [google-protobuf](https://www.npmjs.com/package/google-protobuf)                             | 10 months             | 69.4%          | 53.2%          | -   | [protocolbuffers/protobuf-javascript](https://github.com/protocolbuffers/protobuf-javascript) | 419   | 10 years old | Does not support ESM. Doesn't support Typescript generation. Written purely in javascript                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [ts-protoc-gen](https://www.npmjs.com/package/ts-protoc-gen)                                 | 4 years               |                |                | -   | [improbable-eng/ts-protoc-gen](https://github.com/improbable-eng/ts-protoc-gen)               | 1.4k  | 8 years old  | Basically unmaintained and didn't have releases for a very long time. Plus it generates only `.d.ts` declarations instead of usual typescript. Bad ES6 support.                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| [@connectrpc/connect-node](https://www.npmjs.com/package/@connectrpc/connect-node)           | 3 months              |                |                | +   | [connectrpc/connect-es](https://github.com/connectrpc/connect-es)                             | 1.5k  | 3 years old  | It generates RPC clients and uses [@bufbuild/protoc-gen-es](https://www.npmjs.com/package/@bufbuild/protoc-gen-es) for that.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [@connectrpc/connect](https://www.npmjs.com/package/@connectrpc/connect)                     | 3 months              |                |                | +   | [connectrpc/connect-es](https://github.com/connectrpc/connect-es)                             | 1.5k  | 3 years old  | It generates RPC clients and uses [@bufbuild/protoc-gen-es](https://www.npmjs.com/package/@bufbuild/protoc-gen-es) for that.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [protoscript](https://www.npmjs.com/package/protoscript)                                     | 3 months              | 46.2%          | 17.9%          | +   | [TateThurston/protoscript](https://github.com/TateThurston/protoscript)                       | 71    | 3 years old  | Very young library (`v0.0.23`). Fails a significant amount of tests. Not very much activity present from the author lately.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |


<a name="lang-rust"></a>
### Rust
- [rust-protobuf](https://github.com/stepancheg/rust-protobuf) - Rust implementation of Google protocol buffers.

<a name="lang-lua"></a>
### Lua
- [lua-protobuf](https://github.com/starwing/lua-protobuf) - A Lua module to work with Google protobuf.

<a name="lang-haskell"></a>
### Haskell
- [Protobuf](https://github.com/google/proto-lens) - API for protocol buffers using modern Haskell language and library patterns.
