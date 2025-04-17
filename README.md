Shopping App - Android  A modern e-commerce app built with:  Jetpack Compose for UI  Firebase Auth for login  Razorpay for payments  Hilt for dependency injection  Features: ✔ Splash screen ✔ Edge-to-edge design ✔ Notification permissions ✔ MVVM architecture  Perfect for learning modern Android development with Kotlin!
📱 Shopping App | Android (Jetpack Compose + Hilt + Firebase + Razorpay)

A modern Android shopping app with:

🛒 Product Browsing – Jetpack Compose UI

🔥 Firebase Auth – Secure user authentication

💳 Razorpay Integration – Seamless payments

🧩 Hilt DI – Clean dependency injection

🔔 Notification Permissions – Android 13+ support

Built with best practices in MVVM, edge-to-edge UI, and modular design.

GitHub Repository Summary (Detailed)
✨ Key Features
UI: Jetpack Compose with dynamic theming, splash screen, and edge-to-edge design.

Authentication: Firebase Auth for secure login/signup.

Payments: Razorpay SDK integration with customizable options.

DI: Hilt for dependency injection (e.g., FirebaseAuth, Checkout).

Permissions: Handles post-notification permissions (Android 13+).

🛠 Tech Stack
Languages: Kotlin

Libraries:

Jetpack Compose

Hilt (DI)

Firebase Auth

Razorpay SDK

Navigation Component

Architecture: MVVM (implied via ViewModel usage)

🚀 Setup
Add google-services.json for Firebase.

Replace TEST_ID with your Razorpay API key (use BuildConfig for security).

Enable edge-to-edge in MainActivity.

📂 Project Structure
Copy
app/
├── src/
│   ├── main/
│   │   ├── MainActivity.kt   // Entry point, Compose UI, payment flow
│   │   ├── BaseApplication.kt // Hilt setup
│   │   ├── di/               // Hilt modules
│   │   ├── navigation/       // NavGraph
│   │   └── features/         // Auth, Products, Checkout
🔍 Why This Project?
Modular: Easy to extend with new features (e.g., product catalog).

Production-Ready: Follows best practices (DI, edge-to-edge, permission handling).

Learning Tool: Covers modern Android development (Compose, Hilt, payments).

📸 Screenshot (Hypothetical)
Splash Screen

GitHub Tags
#android #jetpack-compose #kotlin #firebase #razorpay #hilt #mvvm

How to Use
Clone the repo:

bash
Copy
git clone https://github.com/yourusername/shopping-app.git
Open in Android Studio and sync Gradle.

Run on emulator/device (min API 24).

This description is SEO-friendly and highlights the project’s strengths for recruiters or collaborators. Let me know if you’d like to emphasize specific areas (e.g., testing, CI/CD)! 🚀

summary
Here's a concise yet comprehensive summary of your Shopping App project:

Shopping App - Android Summary
A modern e-commerce Android app built with Jetpack Compose, featuring Firebase authentication, Razorpay payments, and Hilt dependency injection.

Core Features
✔ User Authentication – Secure login via Firebase Auth
✔ Seamless Payments – Razorpay SDK integration with customizable options
✔ Modern UI – Jetpack Compose with edge-to-edge design and splash screen
✔ Dependency Injection – Hilt for clean architecture
✔ Android 13+ Support – Notification permission handling

Technical Highlights
100% Kotlin with Jetpack Compose for declarative UI

MVVM Architecture (ViewModels + Data Layer)

Firebase Integration for backend services

Razorpay API for payment processing

Hilt DI for maintainable code structure

Development Practices
🔹 Modular design for scalability
🔹 Edge-to-edge UI implementation
🔹 Permission-aware for modern Android versions
🔹 Secure key management (Firebase + Razorpay)

Project Structure
Copy
app/
├── di/               # Dependency Injection modules
├── features/         # Auth, Products, Checkout
├── navigation/       # Compose Navigation
└── presentation/     # UI components
Ideal for developers learning:

Modern Android development (Compose + Kotlin)

Payment gateway integrations

Firebase authentication

Dependency injection with Hilt
