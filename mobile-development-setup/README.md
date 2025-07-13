# Mobile Development Environment Setup

## 🎯 Objective
Set up a mobile development environment using the Expo Framework for React Native to enable efficient app development and testing on physical devices.

## 📋 Prerequisites
- [Node.js LTS](https://nodejs.org/) (v18+ recommended)
- [VS Code](https://code.visualstudio.com/) (or preferred IDE)
- macOS, Linux, or Windows OS
- Physical iOS or Android device

## 📱 Why Expo Go?
| Feature | Benefit |
|---------|---------|
| Cross-platform | Test on both iOS & Android |
| Cost-effective | No need for multiple physical devices |
| Live reloading | Instant preview of changes |
| Simplified workflow | No complex emulator setup |

## 🛠️ Installation Guide

### 1. Install Expo Go
- **Android**: [Get on Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent)
- **iOS**: [Get on App Store](https://apps.apple.com/app/expo-go/id982107779)

### 2. Verify Installation
```bash
npm install -g expo-cli
expo --version
# Should return version 50.0.0 or higher`
```

### 3. Run Your First Expo Project

## 📦 Setup Steps

```bash
expo init my-first-app
cd my-first-app
expo start
```

### 4.Testing Workflow

- Scan the QR code from your terminal using the **Expo Go** app.
- Make code changes in **VS Code**.
- See changes live on your device — hot reloading in action!

---

### 5.Common Issues & Solutions

| Issue                  | Solution                                                  |
|------------------------|-----------------------------------------------------------|
| Connection problems    | Ensure device and computer are on the **same Wi-Fi**      |
| QR code not scanning   | Manually enter the **URL** shown in the terminal          |
| App crashes on launch  | **Clear Expo Go cache** and restart the app               |

---

### 📚 Resources

- [Expo Documentation](https://docs.expo.dev/)
- [React Native Docs](https://reactnative.dev/)
- [Troubleshooting Guide](https://docs.expo.dev/troubleshooting/common-issues/)

---

### 📝 Notes

- Tested on **Samsung Galaxy A52 (Android 13)** and **iPhone 13 (iOS 17.5)**
- Special configurations used:
  - Enabled `fastRefresh` for development
  - Used **React Navigation** for screen routing
  - Custom fonts loaded using `expo-font`
- Additional packages installed:
  - `react-navigation/native`
  - `@react-navigation/native-stack`
  - `expo-font`
  - `expo-status-bar`
