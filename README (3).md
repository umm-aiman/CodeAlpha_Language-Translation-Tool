# 🌐 Language Translator

![Python](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![API](https://img.shields.io/badge/MyMemory-API-orange?style=for-the-badge)
![No Framework](https://img.shields.io/badge/No_Framework-Vanilla-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)
![Responsive](https://img.shields.io/badge/Responsive-Yes-blue?style=for-the-badge)

> A clean, fully front-end **Language Translator** that works instantly in your browser — **no account, no API key, no setup required.** Supports 19+ languages with auto-detection, text-to-speech, and one-click copy.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Supported Languages](#-supported-languages)
- [Getting Started](#-getting-started)
- [How It Works](#-how-it-works)
- [Built With](#-built-with)
- [Color Scheme](#-color-scheme)
- [Project Structure](#-project-structure)
- [Notes](#-notes)
- [License](#-license)

---

## 🧠 Overview

A lightweight, single-file web app that translates text across 19+ languages in real time using the **MyMemory free translation API**. Built entirely with plain HTML, CSS, and JavaScript — no frameworks, no dependencies, no backend.

---

## ✨ Features

- 🔍 **Auto language detection** — paste any text and it figures out the source language automatically
- 🔄 **Swap languages** — flip source and target with one click
- 🔊 **Text-to-speech** — listen to both source and translated text
- 📋 **One-click copy** — copy the translation to clipboard instantly
- ⌨️ **Keyboard shortcut** — press `Ctrl + Enter` to translate without using the mouse
- 📏 **Character counter** — live 500-character limit tracker with color warning
- 📱 **Fully responsive** — works on mobile and desktop

---

## 🌍 Supported Languages

| | | | |
|---|---|---|---|
| 🇬🇧 English | 🇵🇰 Urdu | 🇸🇦 Arabic | 🇮🇳 Hindi |
| 🇪🇸 Spanish | 🇫🇷 French | 🇩🇪 German | 🇨🇳 Chinese |
| 🇯🇵 Japanese | 🇰🇷 Korean | 🇧🇷 Portuguese | 🇷🇺 Russian |
| 🇮🇹 Italian | 🇹🇷 Turkish | 🇳🇱 Dutch | 🇵🇱 Polish |
| 🇸🇪 Swedish | 🇮🇩 Indonesian | 🇮🇷 Persian | |

---

## 🚀 Getting Started

No installation needed. Just open the file in your browser.

```bash
# Clone the repository
git clone https://github.com/your-username/language-translator.git

# Navigate into the folder
cd language-translator

# Open in browser
open index.html
```

Or simply **drag and drop** `index.html` into any browser window and it works.

---

## ⚙️ How It Works

```
User types text
      ↓
Selects source + target language (or uses Auto Detect)
      ↓
Clicks Translate → or presses Ctrl + Enter
      ↓
App calls MyMemory API (free, no key needed)
      ↓
Translation appears in the right panel
      ↓
User can Copy / Speak / Listen
```

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 (Custom Properties) | Styling & theming |
| Vanilla JavaScript | Logic & API calls |
| [MyMemory API](https://mymemory.translated.net/) | Free translation engine |
| Web Speech API | Browser-native text-to-speech |
| Google Fonts (Inter) | Typography |

---

## 🎨 Color Scheme

| Role | Hex | Preview |
|---|---|---|
| Page background | `#a9fbfa` | Cyan mint |
| Main card | `#ffffff` | White |
| Buttons & selects | `#edb2d6` | Pink |
| Text | `#000000` | Black |

---

## 📁 Project Structure

```
language-translator/
│
└── index.html        # Everything in one file — HTML, CSS & JS
└── README.md         # Project documentation
```

---

## 📌 Notes

- The free MyMemory API allows up to **1,000 words/day** per IP address
- Text-to-speech quality depends on your **browser and OS** language support
- An **internet connection** is required for translation (API call)
- All logic lives in a single `index.html` — no build tools, no npm, no config

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Made with 💙 using plain HTML, CSS & JavaScript — no frameworks, no fuss.
