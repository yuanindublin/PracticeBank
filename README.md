# Practice Bank 🚀

This is a web-based practice and mock exam application designed specifically for the **SAA-C03** certification exam. Featuring a clean, cool-themed interface inspired by Pearson VUE and official AWS styles, it aims to provide an immersive, feature-rich, and efficient study experience.

## ✨ Core Features

*   **🎯 Practice Mode**
    *   Instantly compare the **community vote distribution** with the official answer key to understand why wrong answers happen.
    *   Support for **strikethrough options** via right-click (process of elimination) and **text highlighting** for key terms.
    *   Question **starring (★)** management for focused review.
    *   Collapsible, upvote-ranked community discussion sections.
*   **⏱️ Exam Mode**
    *   1:1 simulation of the real Pearson VUE exam environment.
    *   Randomly draws **65 questions** per session with a **130-minute countdown timer** (can be hidden/restored).
    *   Question flagging (Mark for Review), question grid overview, and status filtering (All, Answered, Flagged, Unanswered).
    *   Generates an **AWS 100–1000 scaled score** upon submission, with a **720 passing threshold** (Pass/Fail) and a detailed review panel featuring official rationale and community discussions.
*   **📚 Review Mode**
    *   Read-only review mode with persistent highlights.
    *   **Personal Notes**: Add, edit, and save custom notes for each question (such as mnemonics, gotchas, or reasonings) with local persistence.
    *   Focuses on correct options and community consensus.
*   **🧭 Question Navigator**
    *   Real-time global keyword search (e.g., `CloudFront`, `S3`, `KMS`).
    *   Multi-dimensional status filtering (All, Wrong, Starred, Multi-select).
    *   Section quick preview and navigation.
*   **💾 Progress Persistence & Cross-Device Migration**
    *   All answers, wrong-question history, starred items, and personal notes are automatically persisted locally via the browser's `localStorage`.
    *   One-click **Export/Import Progress (JSON)** feature to seamlessly sync data across devices.
*   **⌨️ Keyboard Shortcuts**
    *   Full keyboard navigation support for enhanced study efficiency.

---

## ⌨️ Keyboard Shortcuts Guide

| Shortcut | Action |
| :--- | :--- |
| <kbd>A</kbd> – <kbd>F</kbd> | Select option |
| <kbd>Enter</kbd> / <kbd>Space</kbd> | Submit answer / Go to next when locked |
| <kbd>→</kbd> / <kbd>N</kbd> | Next question |
| <kbd>←</kbd> / <kbd>P</kbd> | Previous question |
| <kbd>S</kbd> | Toggle star status for current question |
| <kbd>R</kbd> | Reveal answer without answering / Retry when locked |
| <kbd>U</kbd> | Retry current question |
| <kbd>M</kbd> / <kbd>[</kbd> | Open Question Navigator |
| <kbd>T</kbd> | Toggle community discussion (when available) |
| <kbd>?</kbd> | Open help & shortcuts panel |
| <kbd>Esc</kbd> | Close any open modal dialog |

---

## 🛠️ Tech Stack

*   **Frontend**: Vanilla HTML5, CSS3, Modern JavaScript (ES6+)
*   **Design Tokens**: Geist Font, JetBrains Mono
*   **Storage**: Browser LocalStorage API

---

## 🚀 Quick Start & Deployment

Since this is a pure static frontend application with no complex backend required, you can run it easily:

1. **Clone the repository**
   ```bash
   git clone [https://github.com/YourUsername/YourRepository.git](https://github.com/YourUsername/YourRepository.git)
