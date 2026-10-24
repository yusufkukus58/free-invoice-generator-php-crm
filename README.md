<div align="center">

# ⚡ BillCraft — Free Responsive A4 Invoice, Quote & Contract Studio

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-billcraft--pro.pages.dev-indigo.svg)](https://billcraft-pro.pages.dev)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)
[![Codester](https://img.shields.io/badge/Codester-Buy%20Source%20()-emerald.svg)](https://www.codester.com/items/73465/billcraft-pro-php-invoicing-and-client-crm)
[![Enterprise Edition](https://img.shields.io/badge/Whop-Enterprise%20Pro%20SaaS%20($29)-amber.svg)](https://whop.com/billcraft-pro/billcraft-pro-lifetime-access)

**An ultra-fast, zero-dependency, self-hosted web workspace for Freelancers, Web Agencies, and Small Businesses to create commercial Invoices, Price Quotes, and legal Service Contracts with wet-ink digital signatures.**

[🌐 Explore Live Demo](https://billcraft-pro.pages.dev) · [🚀 Get Enterprise Pro ($29)](https://whop.com/billcraft-pro/billcraft-pro-lifetime-access) · [🐞 Report Bug](https://github.com/yusufkukus58/free-invoice-generator-php-crm/issues)

</div>

---

### 🌟 Looking for the Full Enterprise PHP 8 & MySQL Backend Suite?

> **Replace expensive $49/month recurring subscriptions with a high-performance, self-hosted business engine!**  
> Get the full **BillCraft Pro Enterprise Suite** with **PHP 8 PDO + MySQL 7-Table Database**, **Bcrypt Server-Side Authentication**, **CSRF Guard**, **1-Click Auto-Installer Wizard**, **Client CRM Ledger**, and **Excel/CSV Export**.
>
> 🛒 **[Get BillCraft Pro Lifetime Access on Whop ($29 — Instant Download)](https://whop.com/billcraft-pro/billcraft-pro-lifetime-access)**

---

## 📊 Community Edition (Free) vs. Enterprise Pro SaaS ($29)

| Feature | Community Edition (This Repo) | Enterprise Pro Suite (Whop / Self-Hosted) |
| :--- | :---: | :---: |
| **Pricing** | **Free (MIT License)** | **$29 (One-Time Lifetime Access)** |
| **A4 Document Studio** | Invoices & Quotes | **Invoices, Quotes & Legal Contracts** |
| **Wet-Ink Digital Signature Pad** | ✅ Yes (Mouse / Touch) | **✅ Yes (120 FPS High-Res Canvas)** |
| **Instant Live PDF Export** | ✅ Yes (Clean Vector A4) | **✅ Yes (Clean Vector A4, Print-Ready)** |
| **Multi-Currency ($ / € / £ / ₺ / C$ / A$)** | ✅ Yes (6 Currencies) | **✅ Yes (6 Currencies + Custom Decimals)** |
| **Multi-Language UI** | EN, TR, DE, ES | **EN, TR, DE, ES (Instant Switcher)** |
| **Backend Database Architecture** | ❌ Browser LocalStorage only | **✅ PHP 8 PDO + MySQL (7 InnoDB Tables)** |
| **Server-Side Authentication** | ❌ None | **✅ Bcrypt `password_verify()` + Sessions** |
| **Security & Rate-Limiting** | ❌ None | **✅ CSRF Token Guard + IP Brute-Force Throttling** |
| **1-Click Auto-Installer Wizard** | ❌ None | **✅ Yes (`/install/index.php` with Admin Setup)** |
| **Client CRM & Financial Ledger** | ❌ Basic | **✅ Real-Time SQL Ledger + Status Toggling** |
| **Excel & JSON Exports** | ❌ None | **✅ 1-Click CSV Excel & JSON Database Backup** |
| **Service & Item Pre-Saved Catalog**| ❌ Basic | **✅ Full SQL Catalog with 1-Click Line Insertion** |
| **Commercial Usage License** | Personal / Open Source | **✅ Unlimited Commercial Agency / Client Use** |
| **Direct Download** | `git clone` | **👉 [Instant Download on Whop ($29)](https://whop.com/billcraft-pro/billcraft-pro-lifetime-access)** |

---

## ✨ Features (Community Edition)

- 📄 **3-in-1 Live A4 Document Studio:** Seamlessly switch between commercial Invoices, Price Quotes / Proposals, and legal Service Contracts with instant side-by-side live sheet rendering.
- 🖋️ **Wet-Ink Digital Signature Pad:** Sign invoices and contracts directly using your mouse, trackpad, or touch screen.
- 🌍 **Instant 4-Language Switcher:** Built-in 1-click internationalization (`English`, `Türkçe`, `Deutsch`, `Español`).
- 💱 **Multi-Currency Engine:** Full support for `$` USD, `€` EUR, `£` GBP, `₺` TRY, `C$` CAD, and `A$` AUD.
- 🎨 **5 Executive Color Themes:** Corporate Navy, Emerald Slate, Royal Violet, Warm Amber, and Modern Crimson.
- 🖨️ **Zero-Watermark Print & PDF Export:** Clean CSS `@media print` rules ensure pixel-perfect, watermark-free vector A4 prints.
- 💾 **Instant Local Persistence:** Auto-saves your branding, default tax rate, and active drafts directly to browser `localStorage`.

---

## 🚀 Quick Start (Free Version)

### Option 1: Run in Browser Directly (No Server Needed)
Simply double-click `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari) or open the [Live Demo](https://billcraft-pro.pages.dev).

### Option 2: Clone and Serve via CLI
```bash
# Clone this repository
git clone https://github.com/yusufkukus58/free-invoice-generator-php-crm.git

# Navigate to project folder
cd free-invoice-generator-php-crm

# Serve locally using PHP built-in server
php -S localhost:8000

# Open in browser: http://localhost:8000
```

---

## 🏢 Upgrade to Enterprise Pro Edition

The **Enterprise Pro Edition** adds complete server-side persistence, SQL database transactions, enterprise security, and team management:

```text
billcraft-pro/
├── api/v1/
│   ├── auth.php               # Session & Profile API (GET ?action=me, POST ?action=logout)
│   └── documents.php          # Authenticated + CSRF-Protected RESTful JSON API
├── config/
│   ├── Database.php           # Strict PHP 8.0+ PDO Singleton MySQL Connector
│   └── config.local.php       # Environment & Local DB Credentials Array
├── includes/
│   ├── Auth.php               # Server-Side Authentication, Bcrypt, Brute-force Throttling
│   └── bootstrap.php          # Hardened Session (BCSESSID), CSRF Token & API Guard
├── install/
│   └── index.php              # 1-Click Visual Auto-Installer & Admin Generator
├── sql/
│   └── billcraft_schema.sql   # 7 Normalized InnoDB Tables (Users, Attempts, Settings, CRM, Docs)
├── views/
│   └── dashboard.php          # Protected 5-Module SPA Workspace
├── index.php                  # Main Entry Point
└── login.php                  # Secure Sign-In View
```

👉 **[Get BillCraft Pro Lifetime License on Whop ($29)](https://whop.com/billcraft-pro/billcraft-pro-lifetime-access)**

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to check the [issues page](https://github.com/yusufkukus58/free-invoice-generator-php-crm/issues).

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

The Community Edition is open-source software licensed under the **[MIT License](LICENSE)**.  
For commercial agency deployment with the PHP 8 PDO & MySQL backend, purchase the **[Commercial Enterprise License](https://whop.com/billcraft-pro/billcraft-pro-lifetime-access)**.
