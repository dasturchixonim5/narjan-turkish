# Narjan Turkish — Android ilova

Learn Turkish. Think Turkish. Speak Turkish.

Bu loyiha Narjan Turkish veb-platformasini (app/src/main/assets/index.html) Android ilova sifatida o'raydi:
- Android 8.0+ (minSdk 26)
- Turkcha ovoz: Android TextToSpeech (telefonda turkcha ovoz o'rnatilgan bo'lishi kerak)
- Mikrofon: Android SpeechRecognizer (tr-TR)
- Grok AI: Sozlamalar → AI provayder → xAI API kaliti
- Progress telefon xotirasida saqlanadi; Sozlamalar → Zaxira nusxasi orqali ko'chiriladi

## APK'ni GitHub'da yig'ish (kompyutersiz)
1. github.com da yangi repozitoriy oching (masalan, `narjan-turkish`).
2. "uploading an existing file" orqali shu papkadagi barcha fayl va papkalarni yuklang (`.github` papkasi ham!).
3. Actions bo'limida "APK yig'ish" ishga tushadi (5–10 daqiqa).
4. Tugagach, ish sahifasidagi Artifacts → `NarjanTurkish-apk` ni yuklab oling, zip ichidagi `app-release.apk` ni telefonga o'rnating.

## Android Studio'da
File → Open → shu papka → Build → Build APK(s).

## Yangilash
Veb-versiya o'zgarsa, faqat `app/src/main/assets/index.html` faylini almashtiring va `versionCode` ni oshiring.
