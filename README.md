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
**Mục tiêu dự án:** OnlyTrade giúp người dùng “giải phóng” các món đồ không còn sử dụng bằng cách chuyển chúng thành điểm nội bộ, từ đó có thể dùng điểm để lấy các món đồ khác trên sàn mà không cần dùng tiền mặt.

**Vấn đề mà dự án giải quyết:** Ứng dụng hướng tới giải quyết thực trạng lãng phí đồ dùng cá nhân còn tốt nhưng bị bỏ xó – một vấn đề lớn trong xã hội hiện đại, nhất là tại các nước đang phát triển.

---

## Table of contents
- [OnlyTrade - Nền tảng trao đổi đồ dùng qua hệ thống point nội bộ](#onlytrade---nền-tảng-trao-đổi-đồ-dùng-qua-hệ-thống-point-nội-bộ)
- [Introduction](#introduction)
  - [Mục tiêu dự án](#mục-tiêu-dự-án)
  - [Vấn đề mà dự án giải quyết](#vấn-đề-mà-dự-án-giải-quyết)
- [Installation](#installation)
- [Usage](#usage)
- [Repository Structure](#repository-structure)
- [Contributing](#contributing)
- [Changelog](#changelog)
- [License](#license)
- [Contact](#contact)

---

## Installation:
**B1:** Cài đặt app từ các nguồn.  
- Google Play (Android)  
- App Store (iOS)  
- Website / file cài đặt nội bộ (nếu có)

**B2:** Đăng ký hoặc truy cập bằng các tài khoản:
- Facebook  
- Google  
- Số điện thoại (OTP)

**B3:** Sẽ có một bản hướng dẫn sử dụng giao diện cho người dùng (onboarding) để làm quen nhanh với các chức năng chính.

---

## Usage:
Người dùng ứng dụng sau khi đã đăng nhập thì sẽ được up món đồ của mình muốn trao đổi lên app theo hướng dẫn và yêu cầu của app, món đồ đó sẽ được đi qua một hệ thống định giá của app (hệ thống đó phải đảm bảo 100% tính minh bạch và công bằng, có thể có sự bảo hộ của các bộ máy lớn như nhà nước), sau khi món đồ của người dùng đã đi qua hệ thống định giá đó thì người dùng sẽ được trả một số lượng point nội bộ tương ứng với giá trị của món đồ đó, sau đó người dùng có thể dùng point vừa được trả để mua trực tiếp các món đồ có trên sàn miễn là họ có đủ số lượng point cần thiết để trao đổi và quy trình đó cứ tiếp diễn tiếp diễn như cách một nền kinh tế bằng tiền thật vận hành.

---

## Repository Structure:
```txt
OnlyTrade/
├─ docs/                     # Tài liệu dự án (đặc tả, flow, wireframe...)
├─ src/                      # Source code chính
│  ├─ screens/               # Màn hình chính của ứng dụng
│  ├─ components/            # Các component UI tái sử dụng
│  ├─ services/              # Xử lý API, auth, storage
│  ├─ modules/               # Các module: Trade, Point, Valuation...
│  ├─ utils/                 # Hàm hỗ trợ
│  └─ assets/                # Hình ảnh, icons, fonts
├─ tests/                    # Unit/Integration tests
├─ README.md                 # File hướng dẫn dự án
└─ LICENSE                   # Bản quyền
