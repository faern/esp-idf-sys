# Raw Rust bindings for the [ESP IDF SDK](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/)

[![CI](https://github.com/esp-rs/esp-idf-sys/actions/workflows/ci.yml/badge.svg)](https://github.com/esp-rs/esp-idf-sys/actions/workflows/ci.yml)
[![crates.io](https://img.shields.io/crates/v/esp-idf-sys.svg)](https://crates.io/crates/esp-idf-sys)
[![Documentation](https://img.shields.io/badge/docs-esp--rs-brightgreen)](https://esp-rs.github.io/esp-idf-sys/esp_idf_sys/index.html)
[![Matrix](https://img.shields.io/matrix/esp-rs:matrix.org?label=join%20matrix&color=BEC5C9&logo=matrix)](https://matrix.to/#/#esp-rs:matrix.org)
[![Wokwi](https://img.shields.io/endpoint?url=https%3A%2F%2Fwokwi.com%2Fbadge%2Fclick-to-simulate.json)](https://wokwi.com/projects/332188235906155092)

## Highlights

* Build is `cargo` driven and **automatically downloads & configures everything by default**; no need to download the ESP IDF SDK manually, or set up a C toolchain
* Supports both native ESP IDF build (default), as well as a PlatformIO build
* Option to use in a mixed Rust/C project. Check the documentation in the [esp-idf-template](https://github.com/esp-rs/esp-idf-template) crate

**You might want to also check out the type safe Rust wrappes built on top of these raw bndings:**
* [Type safe wrappers for ESP IDF Services](https://github.com/esp-rs/esp-idf-svc)
* [Type safe wrappers for ESP IDF Drivers](https://github.com/esp-rs/esp-idf-hal)

## Build Prerequisites

Follow the [Prerequisites](https://github.com/esp-rs/esp-idf-template#prerequisites) section in the `esp-idf-template` crate.

## Customizing how the ESP IDF SDK is built

Read the [documentation here](BUILD_OPTIONS.md).

## More information

For more information, check out:
* The [Rust on ESP Book](https://esp-rs.github.io/book/)
* The [ESP Embedded Training](https://github.com/esp-rs/espressif-trainings)
* The [esp-idf-template](https://github.com/esp-rs/esp-idf-template) project
* The [esp-idf-svc](https://github.com/esp-rs/esp-idf-svc) project
* The [esp-idf-hal](https://github.com/esp-rs/esp-idf-hal) project
* The [embedded-svc](https://github.com/esp-rs/embedded-svc) project
* The [embedded-hal](https://github.com/rust-embedded/embedded-hal) project
* The [Rust for Xtensa toolchain](https://github.com/esp-rs/rust-build)
* The [Rust-with-STD demo](https://github.com/ivmarkov/rust-esp32-std-demo) project
