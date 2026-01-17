# 4-glasses-and-2-eyes_SystemsDev_Project
# OnlyTrade - Nền tảng trao đổi đồ dùng qua hệ thống point nội bộ
![Status](https://img.shields.io/badge/status-active-success)
![Version](https://img.shields.io/badge/version-0.1.0-blue)
![Platform](https://img.shields.io/badge/platform-mobile-orange)
![License](https://img.shields.io/badge/license-MIT-purple)
![PRs](https://img.shields.io/badge/PRs-welcome-brightgreen)
![Stars](https://img.shields.io/github/stars/Arnold-Nguyen/4-glasses-and-2-eyes_SystemsDev_Project?style=social)

---

## Introduction:
**Project Goal:** OnlyTrade helps users "get rid of" unused items by converting them into internal points, which can then be used to redeem other items on the platform without using cash.

**Problem addressed by the project:** The application aims to address the wasteful use of perfectly good personal items that are left unused – a major problem in modern society, especially in developing countries.
---

## Table of contents
- [OnlyTrade] - [Internal Point System Exchange Platform](#onlytrade---internal-point-system-exchange-platform)
- [Introduction](#introduction)
  - [Project Objectives](#project-objectives)
  - [Problem that the project solves](#problem-that-the-project-solves)
- [Installation](#installation)
- [Usage](#usage)
- [Repository Structure](#repository-structure)
- [Contributing](#contributing)
- [Changelog](#changelog)
- [License](#license)
- [Contact](#contact)

---

## Installation:
**B1:** Install apps from sources..  
- Google Play (Android)  
- App Store (iOS)  
- Website / internal installation file (if any)

**B2:** Register or access using these accounts:
- Facebook  
- Google  
- Phone number (OTP)

**B3:** There will be an onboarding user interface guide to help users quickly familiarize themselves with the main functions.

---

## Usage:
After logging in, users upload items they wish to trade to the app according to the app's instructions and requirements. The item then goes through the app's valuation system (this system must ensure 100% transparency and fairness, and may be protected by major agencies such as the government). After the item has passed the valuation system, the user receives a corresponding number of internal points based on the item's value. The user can then use these points to directly purchase items on the platform, provided they have enough points to complete the trade. This process continues, much like a real-world economy.

---

## Repository Structure:
```txt
OnlyTrade/
├─ docs/                     # Project documentation (specifications, flows, wireframes,...)
├─ src/                      # Main code
│  ├─ screens/               # The app's home screen
│  ├─ components/            # Reusable UI components
│  ├─ services/              # Handling API, authentication, and storage.
│  ├─ modules/               # Modules: Trade, Point, Valuation...
│  ├─ utils/                 # Support functions
│  └─ assets/                # Images, icons, fonts
├─ tests/                    # Unit/Integration tests
├─ README.md                 # Project guide file
└─ LICENSE                   # Copyright
