# BitChat for Android

[![Build Status](https://img.shields.io/build/your-ci/service/your-repo/master)](https://your-ci-link.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub release](https://img.shields.io/github/release/your-username/bitchat-android.svg)](https://github.com/your-username/bitchat-android/releases)

A secure, decentralized, and anonymous chat application for Android powered by the Nostr protocol and Tor.

## 📖 Overview

BitChat is an Android application designed for users who prioritize privacy and security in their communications. It leverages decentralized technologies to offer a censorship-resistant and anonymous messaging experience. The project is built entirely with modern Android development practices, using Kotlin and Jetpack Compose.

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
    git clone https://github.com/your-username/bitchat-android.git
    ```
2.  **Open in Android Studio:**
    Open the cloned directory in the latest stable version of Android Studio.
3.  **Sync Gradle:**
    Let Android Studio sync the project's Gradle dependencies.
4.  **Run the app:**
    Build and run the application on an Android emulator or a physical device.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m '''Add some AmazingFeature'''`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

This project is licensed under the MIT License. See the `LICENSE.md` file for details.
