# bit-chats

A secure, decentralized, and anonymous chat application for Android.

## 🚀 Overview

**bit-chats** is an Android messaging app designed to provide privacy-first communication. It uses decentralized protocols and strong cryptographic techniques to ensure your data and identity remain secure. The app is built entirely with modern Android tooling, including Kotlin and Jetpack Compose.

## ✨ Features

- **Decentralized Messaging** — Built on the Nostr protocol to avoid reliance on central servers.  
- **Anonymity via Tor** — Integrated with Arti (Rust Tor implementation) to anonymize network traffic.  
- **End-to-End Encryption** — Leveraging Bouncy Castle and Google Tink for secure messaging.  
- **Secure Identity Management** — On-device key management with `androidx.security:security-crypto`.  
- **Modern UI** — Built using Jetpack Compose, following best practices in Android UI design.  
- **Peer-to-Peer (P2P) Support** — Includes BLE (Bluetooth Low Energy) for offline messaging scenarios.

## 🛠 Tech Stack & Architecture

| Area | Technology / Pattern |
|---|---|
| UI | Jetpack Compose |
| Architecture | MVVM (Model-View-ViewModel) with Android Architecture Components |
| Asynchronous | Kotlin Coroutines & Flow |
| Networking | OkHttp + Nostr Protocol + Tor (Arti) |
| Crypto / Security | Bouncy Castle, Google Tink, AndroidX Security |
| Dependency Injection | (Recommended) Hilt |

## 🧰 Getting Started

These instructions will help you run a local copy of the project for development and testing.

### Prerequisites

- Android Studio (latest stable version)  
- Android SDK and tools  
- A device or emulator running Android

### Steps

1. Clone this repository:  
   ```bash
   git clone https://github.com/AnuragBodkhe/bit-chats.git
