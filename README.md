# Pocketsweep — On-Device Edge ML Photo & Media Cleaner

**App Store:** [Download Pocketsweep for iOS & iPadOS](https://apps.apple.com/ng/app/pocketsweep-photo-cleaner/id6768923226)

Pocketsweep is a privacy-first, on-device media organizer and duplicate cleaner for iPhone and iPad. Every perceptual hash, duplicate cluster, burst frame score, and metadata tag is computed locally on the device using Apple Vision and local Foundation Models with zero cloud uploads.

## Core Architecture

- **On-Device Perceptual & Vision Pipeline:** Uses Apple Vision feature-print extraction and frame-quality scoring to detect exact and near-duplicate photos, burst sequences, screenshots, and large video files directly on the device.
- **Local Foundation Models:** Runs on-device metadata classification without external API calls or cloud processing overhead.
- **Native SwiftUI Layout Engine:** Scales across iPhone and iPad viewports with gesture-driven triage workflows and real-time storage reclamation metrics.
- **Global Localization (i18n):** Localized across 16 languages and regional App Store storefronts.
- **StoreKit 2 Integration:** Supports native subscription and lifetime unlock entitlements with local receipt verification.

## Tech Stack

- **Language & UI:** Swift, SwiftUI
- **Machine Learning & Media:** Apple Vision, CoreML, Local Foundation Models, PhotoKit
- **Commerce & State:** StoreKit 2, Local Persistence
