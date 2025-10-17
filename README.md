
<p align="center">
  <img src="https://github.com/user-attachments/assets/17880485-4893-4c6d-9112-50848b46ffd2" width="120" height="120" style="border-radius: 20px;">
  <h1 align="center">🛍️ Fashionista</h1>
  <p align="center">A Modern Flutter Fashion Shopping Experience</p>
  
  <p align="center">
    <img src="https://img.shields.io/badge/Flutter-3.0+-02569B?style=for-the-badge&logo=flutter&logoColor=white">
    <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white">
    <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white">
    <img src="https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white">
  </p>
</p>

<p align="center">
  <a href="https://github.com/muhammadhusnainshahid"><img src="https://img.shields.io/badge/Portfolio-FF6B8B?style=for-the-badge&logo=google-chrome&logoColor=white"></a>
  <a href="mailto:husnainshahid.dev@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/muhammad-husnain-shahid-36b34b26b"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://www.instagram.com/the.husnainshahid"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
</p>

---

## 🎯 Overview

**Fashionista** is a beautifully crafted Flutter application that brings the latest fashion trends to your fingertips. With an elegant UI, smooth animations, and intuitive user experience, it redefines mobile fashion shopping.

---

## ✨ Featured Screens

<div align="center">

| | | |
|:---:|:---:|:---:|
| **🏠 Modern Home Interface** | **🔍 Product Discovery** | **🛒 Smart Cart Management** |
| <img src="https://github.com/user-attachments/assets/17880485-4893-4c6d-9112-50848b46ffd2" width="180" style="border-radius: 15px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);"> | <img src="https://github.com/user-attachments/assets/24cbe17c-9e66-4758-bacc-dc9ba7cd565e" width="180" style="border-radius: 15px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);"> | <img src="https://github.com/user-attachments/assets/d6a636f7-d041-4e6b-882d-42369671ddaf" width="180" style="border-radius: 15px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);"> |

| | |
|:---:|:---:|
| **👤 User Profile** | **📱 More Screens** |
| <img src="https://github.com/user-attachments/assets/36c82212-67d5-4625-9e14-af5eb7d348cb" width="180" style="border-radius: 15px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);"> | <img src="https://github.com/user-attachments/assets/8cbc495f-da50-465f-9754-79bef4331445" width="180" style="border-radius: 15px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);"> |

</div>

---

## 🚀 Features

<div align="center">

| Feature | Description | Status |
|---------|-------------|---------|
| 🎨 **Beautiful UI** | Modern design with smooth animations | ✅ Implemented |
| 🔍 **Smart Search** | Advanced product search & filtering | ✅ Implemented |
| 🛒 **Shopping Cart** | Real-time cart management | ✅ Implemented |
| 💖 **Wishlist** | Save favorite items | ✅ Implemented |
| 🌙 **Dark Mode** | Light/Dark theme support | ✅ Implemented |
| 📱 **Responsive** | Works on all screen sizes | ✅ Implemented |

</div>

---

## 🛠️ Tech Stack

```dart
// Core Technologies
- Flutter 3.0+      🎯 Cross-platform framework
- Dart 3.0+         ⚡ Programming language
- Provider          🏗️ State management
- SharedPreferences 💾 Local storage

// UI & Design
- Material Design 3 🎨 Design system
- Custom Animations ✨ Smooth transitions
- Responsive Layout 📱 Adaptive UI

// Architecture
- Clean Architecture 🏛️ Scalable structure
- MVVM Pattern       🔄 Separation of concerns
- Repository Pattern 💽 Data abstraction
```

---

## 📦 Installation

### Prerequisites
- **Flutter SDK:** 3.0.0 or higher
- **Dart:** 3.0.0 or higher
- **IDE:** Android Studio / VS Code

### Quick Start

```bash
# 1. Clone repository
git clone https://github.com/muhammadhusnainshahid/fashionista.git

# 2. Navigate to project
cd fashionista

# 3. Install dependencies
flutter pub get

# 4. Run the app
flutter run
```

### Platform Support
| Platform | Version | Status |
|----------|---------|---------|
| **Android** | API 22+ (5.0+) | ✅ Supported |
| **iOS** | iOS 14.0+ | ✅ Supported |
| **Web** | Chrome 90+ | 🔄 Planned |

---

## 🏗️ Project Structure

```
fashionista/
├── 📁 lib/
│   ├── 📁 core/
│   │   ├── constants/      # App constants
│   │   ├── themes/         # Light/dark themes
│   │   └── utils/          # Helper functions
│   ├── 📁 data/
│   │   ├── models/         # Data models
│   │   ├── repositories/   # Data repositories
│   │   └── datasources/    # Local/remote data
│   ├── 📁 domain/
│   │   ├── entities/       # Business entities
│   │   └── usecases/       # Business logic
│   ├── 📁 presentation/
│   │   ├── providers/      # State management
│   │   ├── screens/        # App screens
│   │   ├── widgets/        # Reusable components
│   │   └── animations/     # Custom animations
│   └── main.dart          # App entry point
├── 📁 assets/
│   ├── images/            # App images
│   ├── icons/             # App icons
│   └── fonts/             # Custom fonts
└── pubspec.yaml          # Dependencies
```

---

## ⚙️ Configuration

### Basic Setup
```dart
// lib/core/constants/app_constants.dart
class AppConstants {
  static const String appName = 'Fashionista';
  static const String appVersion = '1.0.0';
  static const primaryColor = Color(0xFFE91E63);
  static const secondaryColor = Color(0xFFFF4081);
}
```

### Theme Configuration
```dart
// lib/core/themes/app_theme.dart
class AppTheme {
  static ThemeData lightTheme = ThemeData(
    primaryColor: AppConstants.primaryColor,
    fontFamily: 'Poppins',
    useMaterial3: true,
  );
}
```

---

## 🎨 UI Components

### Custom Widgets
- **ProductCard** - Beautiful product display
- **CategoryGrid** - Organized category view
- **SearchBar** - Advanced search functionality
- **CartItem** - Cart management widget
- **ProfileHeader** - User profile section

### Animations
- **FadeInAnimation** - Smooth entry animations
- **ScaleTransition** - Interactive feedback
- **SlideTransition** - Page transitions

---

## 📱 Screens & Flow

```
Start → Splash → Onboarding → Home
                             ↓
                    Category → Product Detail
                             ↓
                Cart ← Add to Cart ← Wishlist
                             ↓
                       Checkout → Profile
```

---

## 🔮 Future Enhancements

- [ ] **AI Recommendations** 🤖
- [ ] **AR Try-On** 👗
- [ ] **Social Sharing** 📤
- [ ] **Multi-language** 🌍
- [ ] **Payment Integration** 💳
- [ ] **Analytics Dashboard** 📊

---

## 🤝 Contributing

We love contributions! Here's how to help:

1. **Fork** the project
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Code Style
- Follow [Dart Style Guide](https://dart.dev/guides/language/effective-dart/style)
- Use meaningful variable names
- Add comments for complex logic
- Write tests for new features

---

## 📄 License

```xml
MIT License
Copyright (c) 2024 Muhammad Husnain Shahid

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 👨‍💻 Developer

<div align="center">

### **Muhammad Husnain Shahid**
*Flutter Developer & UI/UX Enthusiast*

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-FF6B8B?style=for-the-badge&logo=google-chrome&logoColor=white)](https://husnainshahidportfolio.vercel.app)
[![Email](https://img.shields.io/badge/📧_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:husnainshahid.dev@gmail.com)
[![GitHub](https://img.shields.io/badge/💻_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/muhammadhusnainshahid)

</div>

---

<div align="center">

### **⭐ Star this repository if you find it helpful!**

**Built with ❤️ using Flutter & Dart**

<img src="https://img.shields.io/badge/Made%20with-Flutter-02569B?style=for-the-badge&logo=flutter" />
<img src="https://img.shields.io/badge/Powered%20by-Dart-0175C2?style=for-the-badge&logo=dart" />

</div>
