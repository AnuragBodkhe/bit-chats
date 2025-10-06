# bit-chats for Android

A secure, decentralized, and anonymous chat application for Android.

## 📖 Overview

bit-chats is an Android application designed for users who prioritize privacy and security in their communications. It leverages decentralized technologies to offer a censorship-resistant and anonymous messaging experience. The project is built entirely with modern Android development practices, using Kotlin and Jetpack Compose.

## ✨ Features

*   **Decentralized Messaging:** Built on the **Nostr** protocol, ensuring your conversations are not controlled by a central server.
*   **Anonymity with Tor:** Integrates **Arti**, a next-generation Rust implementation of Tor, to protect your identity and network traffic.
*   **End-to-End Encryption:** Utilizes robust, industry-standard cryptographic libraries (`Bouncy Castle`, `Google Tink`) to secure your messages.
*   **Secure Identity Management:** On-device, secure handling of user identities using `androidx.security:security-crypto`.
*   **Modern Android UI:** A clean, dynamic, and intuitive user interface built entirely with Jetpack Compose.
*   **Peer-to-Peer Capabilities:** Includes Bluetooth Low Energy (BLE) support for potential offline communication scenarios.

## 🛠️ Tech Stack & Architecture

*   **UI:** 100% [Jetpack Compose](https://developer.android.com/jetpack/compose) for declarative UI development.
*   **Architecture:** Follows the MVVM (Model-View-ViewModel) pattern, utilizing Android Architecture Components like [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel), [LiveData](https://developer.android.com/topic/libraries/architecture/livedata), and [Navigation Compose](https://developer.android.com/jetpack/compose/navigation).
*   **Asynchronicity:** [Kotlin Coroutines](https://kotlinlang.org/docs/coroutines-overview.html) and [Flow](https://kotlinlang.org/docs/flow.html) for managing background threads and asynchronous operations.
*   **Networking:** [OkHttp](https://square.github.io/okhttp/) for robust HTTP requests, with custom integrations for the Nostr protocol and Tor via Arti.
*   **Security:**
    *   [Bouncy Castle](https://www.bouncycastle.org/): For advanced cryptographic operations.
    *   [Google Tink](https://github.com/google/tink): For secure and misuse-resistant crypto APIs.
    *   [AndroidX Security](https://developer.android.com/topic/security/data): For securely storing data at rest.
*   **Dependency Injection:** [Hilt](https://developer.android.com/training/dependency-injection/hilt-android) (Recommended to add) for managing dependencies.

## 🚀 Getting Started

To build and run the project, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/AnuragBodkhe/bit-chats.git
    ```
2.  **Open in Android Studio:**
    Open the cloned directory in the latest stable version of Android Studio.
3.  **Sync Gradle:**
    Let Android Studio sync the project's Gradle dependencies.
4.  **Run the app:**
    Build and run the application on an Android emulator or a physical device.

