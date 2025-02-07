# Overview

- Each platform (mobile, desktop, web) has its own workspace member.
- The router feature provides a views/ directory for platform-specific views.
- The ui crate provides UI components that are shared between platforms.
- The server create provides shared server functions.

## How to run

```
cargo install cargo-binstall
cargo binstall dioxus-cli
dx serve --package web
```
