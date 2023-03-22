[![DUB Package](https://img.shields.io/dub/v/i2d-wgpu.svg)](https://code.dlang.org/packages/i2d-wgpu)

# bindbc-wgpu
Dynamic binding to [gfx-rs/wgpu-native](https://github.com/gfx-rs/wgpu-native) based on [BindBC](https://github.com/BindBC/bindbc-loader) library loader. Supports Windows, Linux and macOS.

This is a fork of bindbc-wgpu by [gecko0307](https://github.com/gecko0307/bindbc-wgpu).

> WebGPU specification is currently a working draft and not a standard yet. This binding may be not up to date with latest API revisions.

Usage:
```
dependency "bindbc-wgpu" version="~>0.15.0"
```

Since 0.8.0, major and minor version numbers of the bindbc-wgpu package is in sync with wgpu-native versioning. Patch number can be different.

## What is WebGPU?
It is a new low-level graphics and compute API for the Web that works on top of Vulkan, DirectX 12, or Metal. It exposes the generic computational facilities available in today's GPUs in a cross-platform way. 

[wgpu](https://github.com/gfx-rs/wgpu) is a native WebGPU implementation written in Rust that can be compiled to a shared library to use with any language. Its API is based on the [W3C spec](https://www.w3.org/TR/webgpu/). It serves as the core of the WebGPU integration in Firefox, Servo, and Deno.

Some useful links:
* [WebGPU specification](https://www.w3.org/TR/webgpu/)
* [WebGPU Shading Language specification](https://www.w3.org/TR/WGSL/)
* [wgpu documentation](https://docs.rs/wgpu/0.15.1/wgpu/)
