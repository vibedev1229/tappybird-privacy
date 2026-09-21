# tappybird-privacy

Privacy policies for Tappy Bird, hosted via GitHub Pages. One page per platform, because the
platforms genuinely differ: Android uses Google Play Billing, Play Games Services and Play
Integrity, while iOS uses StoreKit, Game Center and Apple's App Tracking Transparency prompt, and
ships no Integrity equivalent.

| Platform | Live URL | Used by |
|---|---|---|
| Android | https://vibedev1229.github.io/tappybird-privacy/ | Google Play Console |
| iOS | https://vibedev1229.github.io/tappybird-privacy/ios.html | App Store Connect |

`app-ads.txt` at the repo root serves both stores.

Keep each page consistent with the matching in-app policy text: Android
`app/src/main/res/.../PrivacyPolicyActivity`, iOS `ios/TappyBird/Core/LegalContent.swift`.
