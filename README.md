# ISFR (Ignore secure flag Rust)

**ISFR Ignore Secure Flag** is a tool designed to bypass or ignore Android's `FLAG_SECURE` 
setting, which prevents screenshots and screen recording. It is built using **Rust** and 
works on **rooted Android 14+ devices** with **Magisk** for system modifications. This tool 
does not require **LSPosed** and is tailored for use on devices with **Magisk** installed.

## Features

- **Bypass FLAG_SECURE**: Ignore the `FLAG_SECURE` flag on apps that block screenshots and screen recording.
- **Rust-Based**: Fast and efficient implementation in the Rust programming language.
- **Magisk-Compatible**: Works on rooted Android devices via Magisk or Kernelsu.
- **Android 14+ Support**: Designed to work on Android 14 and later devices.
- **No LSPosed Required**: Unlike other solutions, this tool does not depend on LSPosed or other frameworks.
- **Lightweight**: Minimal overhead, simple integration into Magisk.

## Branches

- **`main`**: Contains the source code for the core functionality, written in Rust.
- **`module`**: Contains the code and configuration to create the Magisk module for installation on your device.

## Requirements

- **Android 14+ Device** with root access.
- **Magisk or Kernelsu** installed on the device.
- **Rust** and the **Android NDK** for building the source code.
- **Root Access**: Your device must be rooted to install the Magisk module and bypass the `FLAG_SECURE` setting.
