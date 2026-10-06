<p align="center">
  <img src="assets/feature-1024x500.png" alt="PrismGuard VPN" width="100%">
</p>

<p align="center">
  <a href="https://github.com/PrismGuardVPN/android/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/PrismGuardVPN/android?label=latest&color=3ee6ff"></a>
  <a href="https://github.com/PrismGuardVPN/android/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/PrismGuardVPN/android/total?color=7cc8ff"></a>
  <img alt="Android 8.0+" src="https://img.shields.io/badge/Android-8.0%2B-4ade80">
</p>

# PrismGuard VPN for Android

Official APK releases of **PrismGuard VPN** — a fast, private VPN built on our own transports,
written in Rust. This repository contains release builds only; it does not contain source code.

- **Auto** picks the route that works on your network
- **Camo** — the main, fastest protocol; **Mirror** — a resilient fallback path
- **Fast DNS** (Premium) — emergency mode for whitelist-only networks
- **Free forever:** Camo + Mirror, 5 GB of downloads a month, up to 5 Mbit/s, no card needed
- **Premium:** all protocols, Shield (ads and scam sites), no speed or traffic limits (fair use),
  split tunneling, Wi-Fi + LTE together — from $5 a month
- 10 servers in 5 countries (NL, DE, UK, US, SG), no traffic logs
- English, Russian, Chinese · Android 8.0+

## Download

- **GitHub:** [Releases → latest](https://github.com/PrismGuardVPN/android/releases/latest) — download the `.apk` asset
- **Website:** [prismguard.xyz](https://prismguard.xyz)

Download PrismGuard only from this repository, prismguard.xyz or the Solana dApp Store.

## Verify the APK

Every official APK is signed with the same PrismGuard certificate. Check its fingerprint before
installing.

**Signing certificate SHA-256:**

```
36d35ccd4cb14a19a31f0590fb812c33e491e4b695a16029dc1ec6ab44562a40
```

**On the phone** — install [AppVerifier](https://github.com/soupslurpr/AppVerifier), share the
downloaded APK to it and compare the SHA-256 fingerprint with the one above.

**On a computer** — `apksigner` is part of Android SDK build-tools:

```sh
apksigner verify --print-certs PrismGuard.apk
# compare: Signer #1 certificate SHA-256 digest: 36d35ccd4cb14a19a31f0590fb812c33e491e4b695a16029dc1ec6ab44562a40
```

If the fingerprint does not match, do not install the file and write to
[@PrismGuardSupportbot](https://t.me/PrismGuardSupportbot).

## Updates with Obtainium

[Obtainium](https://github.com/ImranR98/Obtainium) installs and updates apps straight from GitHub
Releases.

1. Open Obtainium → **Add App**.
2. Paste the repository URL: `https://github.com/PrismGuardVPN/android`
3. Tap **Add**. Obtainium will notify you about new releases.

## Support

- Telegram: [@PrismGuardSupportbot](https://t.me/PrismGuardSupportbot)
- Email: support@prismguard.xyz
- News: [t.me/PrismGuardVPN](https://t.me/PrismGuardVPN)
- Website: [prismguard.xyz](https://prismguard.xyz)

## Privacy

We do not log your traffic or the sites you visit. Full policy:
[prismguard.xyz/privacy](https://prismguard.xyz/privacy/).
