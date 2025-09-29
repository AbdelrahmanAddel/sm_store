# 📱 SM Store

A complete e-commerce mobile application built with Flutter, featuring a customer shopping experience and a comprehensive admin dashboard.

[![Flutter](https://img.shields.io/badge/Flutter-3.0+-02569B?logo=flutter)](https://flutter.dev)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📖 Overview

SM Store is a modern e-commerce solution that enables customers to browse products, manage favorites, and shop seamlessly while providing administrators with powerful tools to manage the entire platform.

## ✨ Key Features

### Customer Features
- 🔐 **Authentication** - Secure sign up and sign in
- 🛍️ **Product Browsing** - View and search through products
- ❤️ **Favorites** - Save products for later
- 📱 **Product Details** - Comprehensive product information
- 🎨 **Themes** - Dark and light mode support
- 🔔 **Push Notifications** - Stay updated with Firebase Cloud Messaging
- 🏷️ **Category Filtering** - Browse products by category

### Admin Features
- 👥 **User Management** - View total users and manage accounts
- 📦 **Product Management** - Add, edit, and remove products
- 🗂️ **Category Management** - Create and organize categories
- 📢 **Notifications** - Send push notifications to users

## 🛠️ Tech Stack

- **Framework:** Flutter
- **Architecture:** Clean Architecture
- **State Management:** BLoC & Cubit
- **Backend:** REST API
- **Push Notifications:** Firebase Cloud Messaging

## 📂 Project Structure

```
lib/
├── admin_home_view.dart
├── customer_home_view.dart
├── app_settings/
│   └── cubit/
│       ├── app_settings_cubit.dart
│       ├── app_settings_state.dart
│       └── app_settings_state.freezed.dart
├── authentication/
│   ├── sign_in/
│   └── sign_up/
├── categories/
│   └── presentation/
│       └── view/
│           └── category_products/
├── favorite/
│   └── presentation/
│       └── view/
├── get_all_products/
├── product_details/
│   └── presentation/
├── profile/
├── search/
└── main.dart
```

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (3.0 or higher)
- Dart SDK
- Firebase account (for push notifications)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AbdelrahmanAddel/sm_store.git
   cd sm_store
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Configure Firebase**
   - Add your `google-services.json` (Android) and `GoogleService-Info.plist` (iOS)
   - Follow [Firebase setup guide](https://firebase.google.com/docs/flutter/setup)

4. **Run the app**
   ```bash
   flutter run
   ```

## 📸 Screenshots

*Coming soon*

## 🏗️ Architecture

This project follows **Clean Architecture** principles with clear separation of concerns:

- **Presentation Layer:** BLoC/Cubit for state management
- **Domain Layer:** Business logic and use cases
- **Data Layer:** API integration and data sources

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact

**Abdelrahman Ezzeldean**

- 📧 Email: [abdelrahmanezzeldean@gmail.com](mailto:abdelrahmanezzeldean@gmail.com)
- 💼 LinkedIn: [Abdelrahman Ezzeldean](https://www.linkedin.com/in/abdelrahman-ezzeldean)
- 🐙 GitHub: [@AbdelrahmanAddel](https://github.com/AbdelrahmanAddel)

## ⭐ Show Your Support

If you found this project helpful, please give it a ⭐️!

---

<p align="center">Made with ❤️ by Abdelrahman Ezzeldean</p>
