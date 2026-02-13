# 💬 Die With Us

> Privacy-first anonymous chat built for low-battery moments.  
> No ads. No tracking. No data selling.

---

## 🔥 About The Project

Die With Us is a minimal, privacy-focused anonymous chat application designed to create meaningful conversations during low battery moments.

Unlike traditional chat apps, Die With Us allows access only when your battery is low (1–20%), encouraging intentional and real-time conversations.

This project was built to:

- Respect user privacy
- Prevent database abuse
- Eliminate anonymous app exploitation
- Provide active moderation
- Avoid invasive tracking and ads

---

## ✨ Core Features

### 🔋 Battery-Gated Access
- App works only between 1%–20% battery
- Secure battery validation
- Remote override control (admin controlled)

### 🛡 Privacy First
- No ads
- No trackers
- No invasive permissions
- Minimal stored user data

### 🧑‍⚖ Active Moderation
- Instant bans
- Abuse protection
- Name filtering
- Message control via admin system

### 🔐 Secure Architecture
- Firebase Authentication (Anonymous)
- Firestore (legacy versions)
- Firebase Realtime Database (v7+)
- Strict database rules
- Admin role-based permissions

### 🎨 Clean UI
- Modern Jetpack Compose interface
- Color-based user identity
- Minimal distraction design

---

## 🏗 Technical Stack

- Kotlin
- Jetpack Compose
- Firebase Authentication
- Firebase Firestore
- Firebase Realtime Database
- Android SDK 36
- MVVM Architecture

---

## 📦 Version Information

Current Public Version: **v7**

Major improvements:
- Migration to Realtime Database
- Improved version control system
- App-level remote configuration
- Dedicated `config_v7` document
- Battery override system redesign
- UI & performance improvements

---

## 🔒 Security Improvements Over Similar Apps

This app was built after identifying serious issues in similar anonymous chat platforms:

- Unrestricted database access
- Editable/deletable messages by users
- Battery spoofing vulnerabilities
- No moderation enforcement
- Public database endpoints
- Historical message leaks

Die With Us addresses these issues with:

- Strict Firestore rules
- Server-side moderation logic
- Read-only legacy message archive
- Role-based admin control
- Version-specific configuration documents
- No direct client control over moderation systems

---

## 🌍 Official Links

Website: https://diewithus.shapemysite.in  
Developer: https://iamjaved.site  
Contact: diewithus.team@gmail.com  

---

## 📲 Installation

Download the latest release from:

👉 [Releases Page](../../releases)

---

## 🧠 Philosophy

Die With Us is built on three principles:

**Free of cost.  
No ads.  
Privacy first.**

---

## ⚖ License

This project is proprietary.  
All rights reserved © Javed Hussain.
