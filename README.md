# Yousef Mohammed

Flutter Developer specialized in building scalable, production-ready mobile systems.
I focus on **Clean Architecture**, **business logic**, and **real-world workflows** — not just UI.

---

## 🧠 Core Expertise
- Clean Architecture (Domain / Data / Presentation)
- BLoC / Cubit
- Firebase (Auth, Firestore, Security Rules)
- REST APIs (Dio, Interceptors, JWT)
- AutoRoute
- Secure Storage + SQLite
- Role-Based Systems
- Transactional Business Logic

---

## 🚀 Projects

### 🃏 Base Cards — B2B Digital Cards Marketplace (Code Available)
A production-ready marketplace system for **shop accounts** to purchase digital voucher codes (PlayStation / etc.) from a **centralized inventory** using a wallet balance.

**What I built**
- **Single Source of Truth** inventory (`cards_inventory`) with `isSold` protection to prevent duplicates.
- **Transaction-safe purchase flow**:
  - checks inventory availability
  - marks card as sold
  - deducts shop balance
  - writes immutable purchase history
- Role-based access (Supplier / Shop) with Firestore security rules mindset.
- Real-time balance streaming and purchase updates.
- Modular Clean Architecture with feature separation (Add / Buy / Values / Categories).

**Repository:** https://github.com/yousefwa2001/base-cards

---

### 🚗 Lyonjo — Car Rental Booking App (Published)
A complete booking experience with multi-step flow and business rules, built for real users and deployed to stores.

**Key features**
- Multi-step booking flow (dates → cars → extras → summary → confirmation).
- Dynamic pricing + availability logic with filters and validations.
- API integration using **Dio**, interceptors, and **JWT authentication**.
- Localization, PDF viewing, and document upload flows.
- Clean Architecture + Bloc + AutoRoute, with reusable UI components and performance optimizations.

**Google Play:** https://play.google.com/store/apps/details?id=com.lyonjo.company 

**App Store:** https://apps.apple.com/jo/app/lyonjo/id1614812888

---

### 🧾 Employee Gate — HR Attendance & Leave System (Internal)
An internal HR workflow system focused on reliability, history tracking, and API-driven state.

**Key features**
- Attendance (check-in/out) with timestamps and history logs.
- Multi-step leave requests with validations and approval-ready structure.
- SecureStorage + API workflow using Dio.
- Clean Architecture + Bloc + AutoRoute for maintainable feature scaling.

---

## 📫 Contact
- LinkedIn: https://www.linkedin.com/in/yousef-mohammed-942542331
- Email: yousef.waelmohd@gmail.com
