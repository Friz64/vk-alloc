# vk-alloc

![MIT](https://img.shields.io/badge/license-MIT-blue.svg)
![Apache](https://img.shields.io/badge/license-Apache-blue.svg)

A collection of Vulkan memory allocators written in Rust.

Currently targets [ash](https://github.com/MaikKlein/ash).

## Status

Under heavy development. Not usable yet.

## Features

All features are optional by default.

* `tracing` Adds logging using [tracing](https://github.com/tokio-rs/tracing).
* `profiling` Adds support for [profiling](https://github.com/aclysma/profiling).
* `vk-buffer-device-address`: Enables the usage of "vkGetBufferDeviceAddress". Either needs the
  "VK_KHR_buffer_device_address" extension loaded or the
  "bufferDeviceAddress" device feature enabled.

## License

Licensed under MIT or Apache-2.0.
