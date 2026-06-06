# 🧪 Lab Report Cover Page Generator
live link: https://bikash-20.github.io/cover-page-generator/

A sleek, lightweight, client-side web application designed to help university students instantly generate standardized, print-ready lab report cover pages. 

This utility project was developed independently outside of my standard coursework during my **2nd Year, 1st Semester** to deepen my understanding of reactive vanilla web development, responsive user interfaces, and browser-native print optimization.

---

## 🎯 Purpose & Core Problem Solved
At Metropolitan University (and many academic institutions), students manually format cover pages for every lab submission. Minor inconsistencies in spacing, font sizing, and margins frequently occur. 

This tool abstracts away the layout complexities. Students simply fill out a clean form, preview their document dynamically in real time, and trigger a native browser print command that outputs a pixel-perfect, beautifully aligned, institution-compliant A4 cover page.

## ✨ Key Features
*   **Live Reactive Data-Binding:** Form fields listen for real-time keystrokes (`oninput`) to instantly render user input onto the document layout preview.
*   **Native CSS Print Optimization:** Leverages dedicated CSS `@media print` directives to gracefully hide configuration forms, control panels, and navigation bars when printing or saving as PDF—leaving only the pristine cover page.
*   **Intuitive UI/UX:** Built using an executive color palette (`#1a3a6b`) matching institutional tones, alongside clear semantic sectioning and interactive micro-animations (e.g., dynamic pulsing indicators for live previews).
*   **Zero Dependencies:** Crafted exclusively with standard modern semantic HTML5, localized responsive CSS grid/flexbox layouts, and optimized vanilla JavaScript. No external bloated frameworks required.

---

## 🛠️ Tech Stack & Implementation Details

*   **Markup:** HTML5 (Structured with strict semantic access points for interactive document modeling).
*   **Styling:** CSS3 (Custom Google Fonts integration, smooth state transitions, fluid flexbox layouts, custom `@keyframes` pulsing, and tailored `@media print` queries).
*   **Scripting:** Native JavaScript (ES6+ declarative DOM query functions, state fallback logic, and real-time element mutation tracking).

### Architectural Choices Focus
Rather than loading heavy framework scripts for a single-view system, I designed this tool using strict functional programming in vanilla JavaScript. DOM reads and updates are isolated using custom validation and fallback utilities to guarantee that empty inputs gracefully display sample placeholder layouts without breaking document aesthetics.

---

## 📂 Project Structure & Usage

### File Manifest
*   `index.html` - The single-entry master file containing the application markup, layout logic, reactive styling, and DOM rendering engine.
*   `logo.png` - Institutional branding identity file (Expected asset placeholder for Metropolitan University alignment).

### How to Run Locally
1. Clone this repository or download the source directory.
2. Open `index.html` directly in any modern desktop web browser (Chrome, Edge, Firefox, or Safari).
3. Fill out the input modules under **Fill in Details**.
4. Click **Print / Save as PDF** to generate an accurately scaled A4 layout ready for submission.

---

## 📄 License
This project is open-source software licensed under the **MIT License**.

```text
MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
