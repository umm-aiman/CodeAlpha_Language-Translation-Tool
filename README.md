🌐 Language Translator

A clean, fully front-end Language Translator that works instantly in your browser — no account, no API key, no setup required. Supports 19+ languages with auto-detection, text-to-speech, and one-click copy.




📌 Table of Contents


Overview
Features
Supported Languages
Getting Started
How It Works
Built With
Color Scheme
Project Structure
Notes
License



🧠 Overview

A lightweight, single-file web app that translates text across 19+ languages in real time using the MyMemory free translation API. Built entirely with plain HTML, CSS, and JavaScript — no frameworks, no dependencies, no backend.


✨ Features


🔍 Auto language detection — paste any text and it figures out the source language automatically
🔄 Swap languages — flip source and target with one click
🔊 Text-to-speech — listen to both source and translated text
📋 One-click copy — copy the translation to clipboard instantly
⌨️ Keyboard shortcut — press Ctrl + Enter to translate without using the mouse
📏 Character counter — live 500-character limit tracker with color warning
📱 Fully responsive — works on mobile and desktop



🌍 Supported Languages

🇬🇧 English🇵🇰 Urdu🇸🇦 Arabic🇮🇳 Hindi🇪🇸 Spanish🇫🇷 French🇩🇪 German🇨🇳 Chinese🇯🇵 Japanese🇰🇷 Korean🇧🇷 Portuguese🇷🇺 Russian🇮🇹 Italian🇹🇷 Turkish🇳🇱 Dutch🇵🇱 Polish🇸🇪 Swedish🇮🇩 Indonesian🇮🇷 Persian


🚀 Getting Started

No installation needed. Just open the file in your browser.

bash# Clone the repository
git clone https://github.com/your-username/language-translator.git

# Navigate into the folder
cd language-translator

# Open in browser
open index.html

Or simply drag and drop index.html into any browser window and it works.


⚙️ How It Works

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


🛠️ Built With

TechnologyPurposeHTML5StructureCSS3 (Custom Properties)Styling & themingVanilla JavaScriptLogic & API callsMyMemory APIFree translation engineWeb Speech APIBrowser-native text-to-speechGoogle Fonts (Inter)Typography


🎨 Color Scheme

RoleHexPreviewPage background#a9fbfaCyan mintMain card#ffffffWhiteButtons & selects#edb2d6PinkText#000000Black


📁 Project Structure

language-translator/
│
└── index.html        # Everything in one file — HTML, CSS & JS
└── README.md         # Project documentation


📌 Notes


The free MyMemory API allows up to 1,000 words/day per IP address
Text-to-speech quality depends on your browser and OS language support
An internet connection is required for translation (API call)
All logic lives in a single index.html — no build tools, no npm, no config



📄 License

This project is open source and available under the MIT License.

