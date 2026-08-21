# 🧩 LIBREP2P - Complete Tech Stack

## Dependencies

### 🏃 ASYNC RUNTIME & NETWORKING

| Crate | Version | Purpose |
|-------|---------|---------|
| **tokio** | `1.40` | Async runtime, UDP/TCP, timers |
| **tokio-util** | `0.7` | Utilities for UDP framing |

### 📦 SERIALIZATION

| Crate | Version | Purpose |
|-------|---------|---------|
| **serde** | `1.0` | Serialization framework (with derive) |
| **bincode** | `1.3` | Binary serialization (efficient for UDP) |
| **serde_json** | `1.0` | JSON serialization (for debugging/human-readable) |

### 🔐 CRYPTOGRAPHY

| Crate | Version | Purpose |
|-------|---------|---------|
| **rsa** | `0.9` | RSA key generation & encryption |
| **sha2** | `0.10` | SHA-256 hashing (replaces MD5) |
| **aes-gcm** | `0.10` | AES-256-GCM (fast symmetric encryption) |
| **rand** | `0.8` | Cryptographically secure randomness |
| **hkdf** | `0.12` | HKDF for key derivation *(optional)* |
| **pem** | `3.0` | PEM encoding for keys *(optional)* |

### 🧹 SECURE MEMORY

| Crate | Version | Purpose |
|-------|---------|---------|
| **zeroize** | `1.8` | Zero memory on drop (with derive) |

### 🖥️ TERMINAL UI

| Crate | Version | Purpose |
|-------|---------|---------|
| **ratatui** | `0.28` | TUI framework (formerly tui-rs) |
| **crossterm** | `0.28` | Terminal control & input (with event-stream) |

### 🖥️ SYSTEM INFORMATION

| Crate | Version | Purpose |
|-------|---------|---------|
| **mac_address** | `1.1` | Get MAC addresses |
| **hostname** | `0.4` | Get hostname *(optional)* |
| **whoami** | `1.5` | Get username *(optional)* |

### 🎛️ COMMAND LINE PARSING

| Crate | Version | Purpose |
|-------|---------|---------|
| **clap** | `4.5` | CLI argument parser (with derive & color) |

### ❌ ERROR HANDLING

| Crate | Version | Purpose |
|-------|---------|---------|
| **thiserror** | `1.0` | Error type definitions |
| **anyhow** | `1.0` | Flexible error handling |

### 🧵 CONCURRENCY

| Crate | Version | Purpose |
|-------|---------|---------|
| **dashmap** | `5.5` | Concurrent HashMap (shared peer list) |
| **tokio-stream** | `0.1` | Stream utilities for channels |

### 📝 LOGGING

| Crate | Version | Purpose |
|-------|---------|---------|
| **tracing** | `0.1` | Structured logging |
| **tracing-subscriber** | `0.3` | Log subscriber (with env-filter) |
| **tracing-appender** | `0.2` | Log file rotation *(optional)* |

### 🔧 UTILITIES

| Crate | Version | Purpose |
|-------|---------|---------|
| **chrono** | `0.4` | Timestamps for logging |
| **base64** | `0.22` | Base64 encoding for keys |
| **hex** | `0.4` | Hex encoding |

