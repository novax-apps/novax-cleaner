[README.md](https://github.com/user-attachments/files/29434276/README.md)
# NOVAX Cleaner

**Privacy-first Android storage analyzer.**

- One-time purchase ($2.99) — no subscriptions, no ads
- 100% offline — physically cannot collect your data
- 16 languages supported
- ~5MB download

## 🚀 Quick Start

```bash
# 1. Install Flutter 3.24.0
# 2. Clone this repository
git clone https://github.com/novax-apps/novax-cleaner.git
cd novax-cleaner

# 3. Get dependencies and build
flutter pub get
flutter gen-l10n
flutter build apk --release --split-per-abi

# 4. Install on device
adb install build/app/outputs/flutter-apk/app-arm64-v8a-release.apk
```

## 📱 Features

| Feature | NOVAX | Typical Competitor |
|---------|-------|-------------------|
| Size | ~5MB | 20-67MB |
| Pricing | $2.99 once | $10-30/year |
| Permissions | 2 (storage only) | 15-41 |
| Offline | Yes | No |
| Ads | None | Yes |
| Data collection | None (no INTERNET permission) | Extensive |

## 🛡 Privacy Architecture

NOVAX Cleaner requests **zero network permissions**. The app physically cannot:
- Connect to the internet
- Send analytics
- Upload your files
- Track your behavior

All analysis happens locally on your device.

## 🌍 Languages

English, Русский, Español, Português, हिन्दी, 中文, العربية, Français, Deutsch, 日本語, 한국어, Türkçe, Bahasa Indonesia, Tiếng Việt, ไทย, Bahasa Melayu

## 🌐 Links

- **Landing Page**: https://novax-apps.github.io/novax-cleaner/
- **Privacy Policy**: https://novax-apps.github.io/novax-cleaner/privacy.html
- **Knowledge Base**: https://novax-apps.github.io/novax-cleaner/why-novax.html
- **AI Instructions**: https://novax-apps.github.io/novax-cleaner/llms.txt

## 🏭 About NOVAX Factory

NOVAX is a mobile app factory building privacy-first utilities. All apps follow these principles:

1. **Privacy First** — No personal data in public materials, no data collection in apps
2. **Fair Pricing** — Free trial → one-time purchase, no subscriptions ever
3. **Multilingual** — 12+ languages from day one


## 📄 License

Proprietary — NOVAX Factory
