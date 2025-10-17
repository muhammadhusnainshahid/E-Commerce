<p align="center">
    <a href="http://www.bagisto.com"><img src="https://bagisto.com/wp-content/themes/bagisto/images/logo.png" alt="Bagisto Logo" width="250"/></a>
</p>

<p align="center">
<a href="https://github.com/muhammadhusnainshahid"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
<a href="mailto:husnainshahidm@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
<a href="https://www.instagram.com/the.husnainshahid"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
<a href="https://fb.com/share/19mumJmamN/"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"></a>
<a href="https://www.linkedin.com/in/muhammad-husnain-shahid-36b34b26b"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="https://twitter.com/husnainshahidm1"><img src="https://img.shields.io/badge/Twitter-000000?style=for-the-badge&logo=x&logoColor=white"></a>
</p>

---

# Live Demo

- **Android:** [Play Store](https://play.google.com/store/apps/details?id=com.webkul.bagisto.mobikul)  
- **iOS:** [App Store](https://apps.apple.com/us/app/mobikul-bagisto-laravel-app/id6447519140)  

---

# Features

## Interactive Home & Search
![Interactive Home](https://raw.githubusercontent.com/bagisto/temp-media/master/interactive-homepage-and-search.png)

## All Product Types Supported
![Product Details](https://raw.githubusercontent.com/bagisto/temp-media/master/product-details.png)

## Dark Mode & Push Notifications
![Dark Mode](https://raw.githubusercontent.com/bagisto/temp-media/master/dark-theme-and-push-notifications.png)

## Discount Coupons & Guest Checkout
![Coupons & Guest Checkout](https://raw.githubusercontent.com/bagisto/temp-media/master/coupon-and-guest-checkout.png)

## Wishlist & Product Categories
![Wishlist & Categories](https://raw.githubusercontent.com/bagisto/temp-media/master/category%3Dpage-and-wishlist.png)

## Order Details & Product Reviews
![Order Details](https://raw.githubusercontent.com/bagisto/temp-media/master/order-details-and-product-reviews.png)

---

# Installation Guide

### Prerequisites
- **Bagisto Version:** v2.3.6  
- **Flutter Version:** 3.32.5  
- **Dart Version:** 3.8.1  
- **Android Studio:** 2024.3.1 Patch 2  
- **Xcode:** 16.3  
- **Swift:** 6.1  

> Make sure the [API module](https://github.com/muhammadhusnainshahid/E-Commerce.git) is installed and configured on Bagisto.

---

### Steps

1. **Clone the Repository**
```bash
git clone <repository-url>
cd <repository-name>
````

2. **Install Dependencies**

```bash
flutter pub get
```

3. **Generate Required Files**

```bash
flutter pub run build_runner build --delete-conflicting-outputs
```

4. **Connect Device or Emulator**

* Physical Device: Enable USB debugging & connect via USB
* Emulator: Start Android or iOS emulator

5. **Run the Project**

```bash
flutter run
```

---

### Minimum OS Versions

* Android: 22+
* iOS: 16+

---

# Configuration

### Base Domain

**Path:** `lib/utils/server_configuration.dart`

```dart
static const String baseDomain = '<your_store_url/graphql>';
```

### Theme

**Path:** `lib/utils/mobikul_theme.dart`

```dart
static const Color primaryColor = Color(0xFF********);
static const Color accentColor = Color(0xFF********);
```

### Push Notifications

* **Android:** Replace `google-services.json`
* **iOS:** Replace `GoogleService-Info.plist`

Helpful guides:

* [Android FCM Setup](https://mobikul.com/knowledgebase/generating-google-service-file-enable-fcm-firebase-cloud-messaging-android-application/)
* [iOS FCM Setup](https://mobikul.com/knowledgebase/generating-new-googleservice-info-plist-file-fcm-based-project-ios-app/)

### App Title

* **Android:** `android/app/src/main/AndroidManifest.xml` → `android:label="YourAppName"`
* **iOS:** General tab → Display Name

### Splash Screen

* **Lottie:** `assets/lottie/splash_screen.json` → update `lib/utils/assets_constants.dart`
* **Image:** `assets/images/splash.png` → update `lib/utils/assets_constants.dart`

### App Icon

* **Android:** `android > app > new > Image Asset`
* **iOS:** `ios/Runner/Assets.xcassets/AppIcon.appiconset`

---

# Usage

Refer to official documentation for detailed usage instructions.

---

# Contributing

Contributions welcome! Follow the standard pull request process.

---

# License

This project is open-sourced under the **MIT License**.
Developed and maintained by **Muhammad Husnain Shahid**.

```

✅ This version fixes:  
- Broken badge links  
- Incorrect Markdown image formatting  
- Empty code blocks  
- Misaligned headings  
- Typo fixes  

---

If you want, I can make a **more visually attractive advanced version** with **GIFs, colored badges, and horizontal alignment for icons**, similar to your GitHub profile README.  

Do you want me to do that next?
```
 pic yehi rah de baki sra mra data dal de ta k pta na chla k copy ke hai
