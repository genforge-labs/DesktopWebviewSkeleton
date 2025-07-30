# WhatsApp Desktop (Rust WebView Wrapper)

A simple desktop wrapper for WhatsApp Web, built with Rust using [`wry`](https://github.com/tauri-apps/wry) and [`tao`](https://github.com/tauri-apps/tao). This app allows you to run WhatsApp Web as a standalone desktop application on Linux.

---

## 📦 Project Info

- **Name**: whats-app
- **Version**: 0.1.0
- **Author**: GenForge (info@genforge.com)
- **License**: MIT
- **Description**: A simple WhatsApp WebView wrapper built with Rust.

---

## 🧩 Dependencies

- [`wry = "0.52.1"`](https://crates.io/crates/wry) – WebView wrapper for building cross-platform apps
- [`tao = "0.34.0"`](https://crates.io/crates/tao) – Window management abstraction

---

## 🛠️ Build & Run

### Prerequisites

- Rust (edition 2024)
- Linux system (for `.deb` packaging)
- `cargo-deb` installed:

```bash
cargo install cargo-deb
