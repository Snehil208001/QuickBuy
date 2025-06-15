🛍️ QuickBuy - Android Shopping App





QuickBuy is a modern, feature-rich e-commerce application for Android, built entirely with Jetpack Compose. It showcases modern Android development best practices, including a clean MVVM architecture, dependency injection with Hilt, and seamless integration with Firebase services and the Razorpay payment gateway.

This repository is an excellent resource for developers looking to learn and implement production-level practices in Kotlin and Jetpack Compose.

✨ Key Features
✨ Splash Screen: A smooth and animated introduction to the app.
🔐 User Authentication: Secure user sign-up and login powered by Firebase Authentication.
🛍️ Product Browse: A clean and intuitive user experience for Browse products, categories, and flash sales.
📄 Product Details: A comprehensive view of each product with descriptions, sizing, and quantity selection.
🛒 Shopping Cart: Add, view, and manage products in the cart.
❤️ Wishlist: Save favorite items for later.
💳 Payment Integration: A complete checkout flow with the Razorpay SDK integration for test payments.
🏗️ Clean Architecture: Built on an MVVM (Model-View-ViewModel) architecture with distinct data, domain, and presentation layers for better separation of concerns.
💉 Dependency Injection: Utilizes Hilt for managing dependencies, simplifying the codebase and improving testability.
📱 Modern UI: Fully built with Jetpack Compose, featuring an edge-to-edge UI, dynamic theming, and responsive layouts.
🔔 Android 13+ Support: Includes handling for runtime permissions like notifications.
🛠 Tech Stack & Architecture
Language: Kotlin 🔵
UI Toolkit: Jetpack Compose 🟢
Architecture: MVVM (ViewModel + Repository) 🏛️
Dependency Injection: Hilt 🗡️
Asynchronous Programming: Kotlin Coroutines & Flow ⚡
Navigation: Jetpack Navigation Component 🧭
Backend Services: 🔥
Firebase Authentication
Cloud Firestore
Firebase Storage
Payment Gateway: Razorpay SDK 💳
Image Loading: Coil 🖼️
UI Components:
Accompanist Pager for image banners. 📑
Animated-Navigation-Bar for the bottom navigation. 🍫
📂 Project Structure
The project follows a clean, modular architecture that separates concerns into three main layers: data, domain, and presentation.

app/
├── src/main/java/com/example/shopping/
│
├── 📁 data/
│   ├── di/               # Dagger Hilt modules for the data layer
│   └── repo/             # Repository implementations (e.g., RepoImpl)
│
├── 📁 domain/
│   ├── di/               # Dagger Hilt modules for the domain layer
│   ├── models/           # Data models (e.g., Product, User)
│   ├── repo/             # Repository interfaces
│   └── useCase/          # Business logic for each feature
│
└── 📁 presentation/
    ├── navigation/       # Jetpack Compose navigation graph and routes
    ├── screens/          # Composable screens for each UI
    └── viewModels/       # ViewModels for each screen
⚙️ Setup and Installation
To get this project up and running on your local machine, follow these steps:

Clone the repository: 📥

Bash

git clone https://github.com/snehil208001/quickbuy.git
Open in Android Studio: 💻

Open Android Studio and select File > Open.
Navigate to the cloned repository folder and select it.
Firebase Setup: 🔥

This project requires a google-services.json file to connect to Firebase.
Go to the Firebase Console and create a new project.
Add an Android app to your Firebase project with the package name com.example.shopping.
Download the generated google-services.json file and place it in the app/ directory.
Razorpay API Key: 🔑

The project uses a test API key for Razorpay. You can find it in the app/src/main/AndroidManifest.xml file.
For production use, replace it with your own key from the Razorpay Dashboard.
Build and Run: ▶️

Sync the Gradle files.
Build and run the app on an Android emulator or a physical device.
🔗 Demo & APK
🎥 Screen Recording Demo 📽️ Watch on Google Drive

📦 Download APK 📲 Install & Try
