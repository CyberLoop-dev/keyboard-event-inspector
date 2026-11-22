<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:2563eb&height=180&section=header&text=Keyboard%20Event%20Inspector&fontColor=ffffff&fontSize=34" alt="Keyboard Event Inspector banner"/>
  <br/><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2600&pause=700&center=true&vCenter=true&width=650&lines=See+key+and+code+side+by+side;Inspect+modifiers+and+repeat;Understand+IME+composition+events" alt="Animated title"/>
  <br/><img src="https://img.shields.io/github/license/CyberLoop-dev/keyboard-event-inspector" alt="License"/> <img src="https://img.shields.io/github/languages/top/CyberLoop-dev/keyboard-event-inspector" alt="Language"/> <img src="https://img.shields.io/github/stars/CyberLoop-dev/keyboard-event-inspector" alt="Stars"/> <img src="https://img.shields.io/github/last-commit/CyberLoop-dev/keyboard-event-inspector" alt="Last commit"/>
  <br/><img src="assets/mark.svg" width="210" alt="Keyboard illustration"/>
</p>

## 🧭 Overview

Keyboard Event Inspector is a local browser tool for understanding keyboard events. Type in the test area to compare the logical `key`, physical `code`, modifier flags, repeat state, and composition lifecycle.

## ✨ Features

- ⌨️ Inspect `keydown` and `keyup` events.
- 🧭 Compare `event.key` with `event.code` and key location.
- 🎛️ See Shift, Control, Alt, Meta, repeat, and composition flags.
- 🌐 Observe IME composition start, update, and end events.
- 🔒 No event is sent to a server or saved to browser storage.

## 🎬 Demo

Run the app, focus the test area, and press a few keys. The event table updates locally. Avoid typing passwords or other secrets into the test area. No hosted demo is claimed.

## 🚀 Quick Start

Requires Node.js 18 or newer.

```bash
npm start
```

Open http://localhost:4173.

## 🧰 Tech Stack

- 🟢 Node.js built-in HTTP server
- 🌐 HTML, CSS, and browser KeyboardEvent APIs
- 📦 No third-party dependencies

## 🗂️ Folder Structure

```text
keyboard-event-inspector/
├── assets/mark.svg
├── app.js
├── index.html
├── server.js
├── package.json
├── README.md
├── LICENSE
└── .gitignore
```

## 🛣️ Roadmap

- [ ] Add a printable keyboard layout view.
- [ ] Add optional beforeinput and input event panels.
- [ ] Add export of a sanitized event trace.

## 🤝 Contributing

Include browser and operating-system details when reporting behavior differences. Keep the inspector passive: it must not block normal keyboard input.

## 📄 License

MIT licensed. See [LICENSE](LICENSE).

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,100:111827&height=105&section=footer" alt="Wave footer"/></p>
