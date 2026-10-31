# Duo Clash — Official Privacy Policy Website

Official privacy policy website for **Duo Clash**, an Android mobile casual multiplayer and arcade game developed and published by **MUF Studios**.

- **Live Website**: [https://mohammed-umarfarooq.github.io/duo-clash-privacy-policy/](https://mohammed-umarfarooq.github.io/duo-clash-privacy-policy/)
- **Application Package**: `com.duoclash.game`
- **Developer / Studio**: MUF Studios
- **Support Contact**: `mufstudios.support@gmail.com`
- **Target Distribution**: Google Play Store & Samsung Galaxy Store

---

## Technical Overview & Privacy Architecture

Duo Clash is engineered with a strict **privacy-by-design** approach:

1. **No User Accounts / Zero Direct Personal Data**:
   - The game does not operate user accounts, cloud logins, or remote player databases.
   - All minigames are playable offline locally on a single device.
   - User nicknames, settings, and level progression are stored strictly in local device storage (`user://save_data.json`).
   - Android cloud backup is disabled (`android:allowBackup="false"`).

2. **Advertising (Google AdMob)**:
   - Integrates the Google Mobile Ads SDK for Android.
   - Production Ad Units: Rewarded video ads, interstitial ads, and banner ads.
   - Uses the Android Advertising ID (`com.google.android.gms.permission.AD_ID`) for ad attribution, frequency capping, and fraud prevention.

3. **Diagnostics & Telemetry (Google Firebase Analytics)**:
   - Firebase Project ID: `duo-clash-2e980`
   - Mobile SDK App ID: `1:759570360753:android:e3c2569e7c281651137590`
   - Collects pseudonymous in-game events (`app_launch`, `game_start`, `game_complete`, `level_complete`, `booster_used`, `ad_reward_earned`) and crash telemetry to maintain stability.

4. **Android Permissions**:
   - `android.permission.INTERNET`
   - `android.permission.ACCESS_NETWORK_STATE`
   - `com.google.android.gms.permission.AD_ID`
   - `android.permission.VIBRATE`
   - Zero sensitive permissions (no camera, microphone, contacts, location, or file storage access).

5. **Target Audience**:
   - General audience (13+). Not directed towards children under 13 years of age.

---

## Repository Structure

```
duo-clash-privacy-policy/
├── .github/
│   └── workflows/
│       └── pages.yml        # GitHub Actions workflow for automated Pages deployment
├── .nojekyll                # Bypass Jekyll static processing
├── favicon.svg              # Duo Clash vector branding icon
├── index.html               # Responsive, mobile-friendly Privacy Policy single page
├── styles.css               # Professional dark-mode design system & print stylesheet
└── README.md                # Documentation & repository information
```

---

## Deployment & Verification

This website is deployed to **GitHub Pages**:

- **Repository**: `https://github.com/mohammed-umarfarooq/duo-clash-privacy-policy`
- **Source**: `main` branch (`/` root) or automated GitHub Actions deployment.
- **Published URL**: [https://mohammed-umarfarooq.github.io/duo-clash-privacy-policy/](https://mohammed-umarfarooq.github.io/duo-clash-privacy-policy/)
