# Rodrigo Saravia Arenas

**Mobile engineer · iOS & Android · 8 years shipping consumer apps end to end**

I build native mobile apps in Swift and Kotlin, the Node.js/MongoDB backends behind them on AWS, and the release pipeline that gets them onto the App Store and Google Play. I'm based in Arequipa, Peru, and have worked remotely with a US team since 2018.

---

## What I've worked on

### EcoBytes: iOS & Android
A consumer app I own end to end, from Swift and Kotlin clients to backend and releases. I built and released the iOS client.
- 📦 **Reusable Swift libraries** used across Shoelace Wireless apps (mainly EcoBytes), including a module that collects per-app data usage and device network metrics and reports them to the backend
- 🏆 **"Build for All" award**, Celo Camp Batch 5
- 🏆 **Best Innovation & Top 18**, Deutsche Telekom T-Challenge 2022/23 (invited to present in Bonn)
- 💳 **Wallet integration**: [`ecobytes-wallet-integration`](https://github.com/BioZrod/ecobytes-wallet-integration) is an Android library that connects to Valora/Celo wallets through intents, so users can redeem EcoBytes points for Celo tokens
- 🌐 **Opera MiniPay front end**: [`eb-minipay`](https://github.com/shoelacewireless/eb-minipay), an EcoBytes front end for the MiniPay wallet

### BoostAgent: iOS & Android
A second consumer app I own across both platforms and its backend.
- Shipped VPN functionality in both clients (Apple `NEPacketTunnelProvider`, Android `VpnService`), with live tunnel status and throughput driven by reactive Kotlin `StateFlow` state

> The EcoBytes and BoostAgent source code is company-owned and private, and the apps are no longer publicly listed. I'm happy to walk through their architecture in detail.

### OpenSchema (Magma Core Foundation)
**Leading contributor** to this open-source network-telemetry project, with [75 commits, the most of any contributor](https://github.com/magma/openschema/graphs/contributors). I built the iOS module and reworked the Android data-usage collection and storage layer.

### Smaller projects
- [`ndt7-client-android`](https://github.com/BioZrod/ndt7-client-android): Kotlin client for M-Lab's NDT7 network speed test, updated to the latest SDK
- [`PhotoSearch`](https://github.com/BioZrod/PhotoSearch): Apple TV (tvOS) demo app in Swift that pulls photos from Flickr

---

## Stack

**iOS:** Swift · UIKit · Network Extension · TestFlight / App Store Connect<br>
**Android:** Kotlin · Java · Coroutines · StateFlow · MVVM · Jetpack Navigation<br>
**Backend:** Node.js · MongoDB · AWS (EC2, Lambda, S3, SES, SNS, CloudWatch) · Firebase<br>
**Also:** Python · SQL · Linux · release engineering
