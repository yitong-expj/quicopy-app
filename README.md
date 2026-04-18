<div align="center">
  <img src="https://www.quicopy.com/assets/logo.png" alt="QUICOPY Logo" width="120" height="120" />

  # QUICOPY

  **Quick text, one shortcut away.**

  A lightweight macOS menu bar app that maps global keyboard shortcuts to text snippets. Press a shortcut in any app — your pre-set text appears instantly at the cursor.

  [![Download on the Mac App Store](https://img.shields.io/badge/Download-Mac_App_Store-007AFF?style=for-the-badge&logo=apple&logoColor=white)](https://apps.apple.com/app/quicopy/id6761418490)
  [![Website](https://img.shields.io/badge/Website-www.quicopy.com-2563EB?style=for-the-badge)](https://www.quicopy.com)
  [![Product Hunt](https://img.shields.io/badge/Product_Hunt-Launch-FF873C?style=for-the-badge&logo=producthunt&logoColor=white)](https://www.producthunt.com/products/quicopy)

  ![macOS](https://img.shields.io/badge/macOS-13.0+-000000?logo=apple&logoColor=white)
  ![Swift](https://img.shields.io/badge/Swift-Native-FA7343?logo=swift&logoColor=white)
  ![Size](https://img.shields.io/badge/Size-2.8_MB-green)
  ![Price](https://img.shields.io/badge/Lifetime-%249.99-gold)
</div>

---

## What is QUICOPY?

QUICOPY is a **native macOS menu bar app** for blazing-fast text input via global keyboard shortcuts. It is the lightweight alternative to TextExpander, aText, and Raycast Snippets — built for users who want instant text output without the subscription cost or Electron bloat.

Assign any text snippet to a global shortcut like `⌘⇧1`. Press the shortcut in any app — Chrome, Safari, VS Code, Slack, ChatGPT, Claude, Mail — and your text appears at the cursor in under 100 ms.

## Why QUICOPY?

- ⚡ **Sub-100 ms response** — feels instant, no lag
- 🎯 **Works everywhere** — browsers, editors, email, chat, AI tools
- 🤖 **7 built-in AI prompt templates** — stop re-typing "think step by step"
- 🪶 **Only 2.8 MB** — 100% native Swift, no Electron
- 🔒 **Privacy-first** — all data stays on your Mac
- ☁️ **Optional iCloud sync** — across your own Macs only
- 💰 **$9.99 lifetime** — one-time purchase, no subscription

## Key Features

### 🔑 Global Keyboard Shortcuts for Any Text
Set up unlimited shortcut → text pairs. Works system-wide in every macOS app.

### 🤖 7 Pre-loaded AI Prompt Templates
Mapped to `⌘⇧1` through `⌘⇧7`:

| Shortcut | Template | Use Case |
|----------|----------|----------|
| `⌘⇧1` | **Step-by-Step** | Force AI into structured reasoning |
| `⌘⇧2` | **Ask First** | Make AI ask clarifying questions before answering |
| `⌘⇧3` | **Writing Polish** | Instant proofreading and style refinement |
| `⌘⇧4` | **ELI5** | Explain Like I'm 5 — simple explanations |
| `⌘⇧5` | **Translation** | Quick multilingual translation |
| `⌘⇧6` | **Prompt Optimizer** | Rewrite your prompt for better AI output |
| `⌘⇧7` | **CO-STAR Framework** | Structured prompt engineering framework |

### 🪶 Menu Bar Native
Lives in your menu bar. No Dock icon clutter. Zero background CPU when idle.

### 🔒 Privacy by Design
- All snippets stored locally (macOS Keychain + sandboxed container)
- No telemetry, no analytics, no tracking
- Optional iCloud sync uses Apple's end-to-end encryption
- Sandboxed (Mac App Store compliant)

---

## Screenshots

<div align="center">
  <img src="https://www.quicopy.com/assets/screenshot_1.png" alt="QUICOPY Main Interface" width="600" />
  <p><em>Main interface — shortcut mapping list with search</em></p>

  <img src="https://www.quicopy.com/assets/screenshot_2.png" alt="QUICOPY Editor" width="600" />
  <p><em>Edit shortcut + text pair with real-time preview</em></p>

  <img src="https://www.quicopy.com/assets/screenshot_3.png" alt="QUICOPY AI Prompts" width="600" />
  <p><em>7 built-in AI prompt templates, ready to use</em></p>
</div>

---

## System Requirements

- **macOS 13.0 (Ventura) or later**
- Apple Silicon (M1/M2/M3/M4) or Intel
- ~ 10 MB free disk space
- Accessibility is **not required** — QUICOPY uses Automation (System Events) instead, which is less invasive

## Pricing

| Plan | Price | Includes |
|------|-------|----------|
| **Free Trial** | $0 | 7 days, full Pro access |
| **Lifetime** ⭐ | **$9.99** one-time | All features, forever, all future updates |
| **Monthly** | $1.99 / month | All features, cancel anytime |

> 💡 Lifetime is the recommended plan. Pay once, yours forever — saves ~58% vs monthly over a year.

---

## How It Works

1. **Open QUICOPY** from your menu bar
2. **Add a snippet** — type your text, assign a shortcut
3. **Press the shortcut in any app** — your text appears at the cursor

Under the hood:

- **Shortcut capture**: `CGEvent Tap` monitors global keyboard input
- **Text output**: `AppleScript System Events` simulates `⌘V` paste
- **Storage**: Sandboxed local file + optional iCloud CloudKit sync
- **App Sandbox compliant** — distributed through Mac App Store

---

## FAQ

### Is QUICOPY a good alternative to TextExpander?
Yes. QUICOPY is a lightweight alternative for users who want global shortcuts without the subscription. $9.99 lifetime vs TextExpander's recurring cost. Plus 7 AI prompt templates out of the box.

### Does QUICOPY work in ChatGPT, Claude, and other AI tools?
Yes — it works in every macOS app, including all web-based AI tools. The 7 built-in AI prompt templates are designed specifically for this use case.

### Is my data uploaded anywhere?
No. All snippets stay on your Mac. Optional iCloud sync uses Apple's end-to-end encrypted iCloud infrastructure — only your own devices can read it.

### Does QUICOPY require Accessibility permission?
No. QUICOPY uses Automation (System Events) which is less invasive than Accessibility. You grant Automation permission on first run.

### What keyboard shortcuts can I use?
Any combination — modifiers (`⌘` `⌃` `⌥` `⇧`) plus any key. Function keys (F1–F12), number keys, letters all supported.

---

## Links

- 🌐 **Website**: [www.quicopy.com](https://www.quicopy.com)
- 📱 **Mac App Store**: [apps.apple.com/app/quicopy/id6761418490](https://apps.apple.com/app/quicopy/id6761418490)
- 🚀 **Product Hunt**: [producthunt.com/products/quicopy](https://www.producthunt.com/products/quicopy)
- 🔒 **Privacy Policy**: [www.quicopy.com/privacy](https://www.quicopy.com/privacy)
- 💬 **Support**: [support@quicopy.com](mailto:support@quicopy.com)

---

## Tech Stack

- **Language**: Swift (100% native)
- **UI**: SwiftUI + AppKit
- **Min OS**: macOS 13.0 (Ventura)
- **Frameworks**: StoreKit 2, CloudKit, CGEvent, ScriptingBridge
- **Distribution**: Mac App Store only (sandboxed)

## About

QUICOPY is built by a solo indie developer who was tired of re-typing the same AI prompts, email templates, and code snippets dozens of times a day. One shortcut — text appears. That's it.

If QUICOPY saves you time, the best thing you can do is leave a review on the [Mac App Store](https://apps.apple.com/app/quicopy/id6761418490) ⭐️⭐️⭐️⭐️⭐️

---

## Keywords

<sub>macOS text shortcut app · global keyboard shortcut · text expander alternative · AI prompt shortcut · menu bar app · text snippet tool · ChatGPT prompt template · Claude prompt shortcut · productivity tool · macOS menu bar · keyboard shortcut text paste · quick text input · text automation mac · snippet manager · macOS productivity</sub>

---

<div align="center">
  <sub>© 2026 QUICOPY · Built with 💙 in Swift for macOS</sub>
</div>
