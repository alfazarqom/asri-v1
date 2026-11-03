# ASRI V1 — Application Requirements

> Dokumen sumber utama kebutuhan aplikasi. Keputusan yang belum dijawab tidak dianggap disetujui.
> Stack teknis: React, Vite, TypeScript.

## 1. Project Overview

| Item | Requirement |
|---|---|
| Repository | `alfazarqom/asri-v1` |
| Application type | E-Commerce Storefront |
| Business category | Electronics & Gadgets |
| Store brand | Asri Store |
| Platform strategy | Mobile-first responsive |
| Primary purpose | Online Store |
| Primary stack | React + Vite + TypeScript |
| Discovery progress | Level 1 — Application Foundation |

## 2. Confirmed Requirements

### REQ-001 — Application Type
- **Status:** Confirmed
- **Decision:** A. E-Commerce Storefront
- **Description:** Aplikasi toko online yang mencakup katalog produk, keranjang belanja, checkout, dan pesanan.
- **Source:** User confirmation, initial requirement question 1.

### REQ-002 — Business Category
- **Status:** Confirmed
- **Decision:** B. Electronics & Gadgets
- **Description:** Toko online untuk produk elektronik dan perangkat teknologi.
- **Source:** User confirmation, initial requirement question 2.

### REQ-003 — Store Brand
- **Status:** Confirmed
- **Decision:** A. Brand sudah ada
- **Brand name:** Asri Store
- **Description:** Aplikasi menggunakan brand toko yang sudah dimiliki, yaitu Asri Store.
- **Source:** User confirmation, initial requirement question 3.

### REQ-004 — Target Platform
- **Status:** Confirmed
- **Decision:** A. Mobile-first Responsive
- **Description:** Pengalaman aplikasi dioptimalkan untuk perangkat mobile dan tetap responsif pada tablet serta desktop.
- **Source:** User confirmation, initial requirement question 4.

### REQ-005 — Primary Application Purpose
- **Status:** Confirmed
- **Decision:** A. Online Store
- **Description:** Menjual produk secara online melalui katalog, keranjang belanja, dan checkout.
- **Source:** User confirmation, Level 1 question 5.

## 3. Requirement Discovery by Level

### Level 1 — Application Foundation
- **Status:** In Progress
- Confirmed: application type, business category, store brand, target platform, primary purpose.
- Pending: target users, business/store identity details, and basic application scope.

### Level 2 — Storefront Foundation
- **Status:** Pending
- Pages, navigation, catalog, product categories, search, product details, and foundational UI components.

### Level 3 — E-Commerce Features
- **Status:** Pending
- Cart, wishlist, checkout, customer information, stock and availability, orders, shipping, promotions, and discounts.

### Level 4 — Backend & Integrations
- **Status:** Pending
- Database, APIs, backend services, payment gateway, callbacks, product data management, transaction security, and external integrations.

### Level 5 — UI/UX & Design System
- **Status:** Pending
- Design tokens, typography, colors, reusable components, responsive behavior, interactions, animations, and accessibility.

### Level 6 — Technical Architecture & Implementation
- **Status:** Pending
- React/Vite/TypeScript architecture, folder structure, state management, routing, testing, build, deployment, and verification.

## 4. Pending Requirements

- Target users and customer segments
- Business identity details and brand assets
- Basic application scope
- Storefront pages and navigation
- Product catalog and product data
- Cart and wishlist behavior
- Checkout and customer information
- Payment methods and payment provider
- Shipping and delivery
- Orders and order tracking
- Promotions and discounts
- Backend, database, and integrations
- UI/UX direction and design system
- Accessibility, performance, SEO, and security
- Deployment and verification criteria

## 5. Decision Governance

1. Hanya jawaban yang dikonfirmasi pengguna yang berstatus **Confirmed**.
2. Requirement ambigu atau bertentangan harus diklarifikasi sebelum ditetapkan.
3. Jangan mengarang detail bisnis, fitur, integrasi, atau kebijakan.
4. Perubahan requirement harus dicatat dengan alasan dan status.
5. Pertanyaan discovery diajukan bertahap berdasarkan level; selesaikan fondasi level aktif sebelum berpindah level.
6. Implementasi aplikasi dimulai setelah requirement ditinjau dan disetujui pengguna.
