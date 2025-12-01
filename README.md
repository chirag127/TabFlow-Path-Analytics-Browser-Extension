# TabFlow: Digital Journey Mapper Browser Extension

<div align="center">
  <a href="https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension">
    <img src="https://raw.githubusercontent.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/main/.github/assets/logo.png" alt="TabFlow Logo" width="150">
  </a>
  <br/>
  <p>
    <strong>Visualize your digital journey, analyze navigation patterns, and uncover insights with this privacy-first, graph-based browser extension.</strong>
  </p>
  <p>
    <!-- Shields.io Badges -->
    <a href="https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/ci.yml?branch=main&style=flat-square&logo=githubactions&logoColor=white" alt="Build Status"></a>
    <a href="https://codecov.io/gh/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension"><img src="https://img.shields.io/codecov/c/github/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension?style=flat-square&logo=codecov" alt="Code Coverage"></a>
    <a href="#"><img src="https://img.shields.io/badge/TypeScript-Strict-3178C6?style=flat-square&logo=typescript" alt="TypeScript"></a>
    <a href="#"><img src="https://img.shields.io/badge/Vite-^5.0.0-646CFF?style=flat-square&logo=vite" alt="Vite"></a>
    <a href="#"><img src="https://img.shields.io/badge/Formatter-Biome-60A5FA?style=flat-square&logo=biome" alt="Biome Formatter"></a>
    <a href="https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/blob/main/LICENSE"><img src="https://img.shields.io/github/license/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension?style=flat-square&color=blue" alt="License"></a>
    <a href="https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/stargazers"><img src="https://img.shields.io/github/stars/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension?style=flat-square&logo=github" alt="GitHub stars"></a>
  </p>
  <p>
    <a href="https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/stargazers"><strong>Star ⭐ this Repo</strong></a> to support its development!
  </p>
</div>

---

## Overview

**TabFlow** is an advanced browser extension that transforms your browsing history into interactive, graph-based maps. It provides a powerful new way to visualize your digital journey, analyze navigation patterns, and uncover insights, all while prioritizing your privacy by processing data locally.

This tool is designed for researchers, developers, and power users who want to understand and optimize their web navigation habits. By representing browser tabs and links as nodes and edges in a graph, TabFlow reveals the hidden structures and pathways of your online exploration.

## ✨ Key Features

-   **🌐 Interactive Graph Visualization:** See your browsing history as a dynamic, zoomable graph.
-   **🕵️ Privacy-First Architecture:** All data is processed and stored locally in your browser. Nothing ever leaves your machine.
-   **🔍 Pattern & Insight Analysis:** Identify recurring navigation patterns, discover influential content hubs, and understand your research paths.
-   **🚀 High-Performance Engine:** Built with a modern tech stack (TypeScript, Vite, WXT) for a fast and responsive user experience.
-   **🎨 Customizable Views:** Filter and style the graph to focus on the data that matters most to you.
-   **📦 Cross-Browser Support:** Built with WXT to support Chrome, Firefox, and other Chromium-based browsers from a single codebase.

## 🏛️ Architecture

TabFlow utilizes a **Feature-Sliced Design (FSD)** architecture for maximum scalability and maintainability. This modular approach ensures a clean separation of concerns, making the codebase easy to navigate and extend.

sh
. TabFlow-Digital-Journey-Mapper-Browser-Extension/
├── .github/          # CI/CD, issue templates, and community health files
├── .vscode/          # VSCode settings for consistent development
├── entrypoints/      # Browser extension entry points (popup, background, content)
│   ├── background.ts # Background service worker
│   ├── content.ts    # Content script for page interaction
│   └── popup/        # Popup UI files (HTML, TSX)
├── features/         # Individual feature slices (e.g., graph-rendering, data-capture)
├── entities/         # Core business entities (e.g., Node, Edge, Session)
├── shared/           # Reusable code (UI components, APIs, libs)
│   ├── api/          # Browser API abstractions
│   ├── lib/          # Utility functions and helpers
│   └── ui/           # Shared UI components (e.g., buttons, modals)
├── wxt.config.ts     # WXT configuration file
├── package.json      # Project dependencies and scripts
└── tsconfig.json     # TypeScript configuration


---

## 📚 Table of Contents

1.  [Overview](#overview)
2.  [Key Features](#-key-features)
3.  [Architecture](#️-architecture)
4.  [🤖 AI Agent Directives](#-ai-agent-directives)
5.  [Getting Started](#-getting-started)
6.  [Available Scripts](#-available-scripts)
7.  [Contributing](#-contributing)
8.  [License](#-license)

---

## 🤖 AI Agent Directives

<details>
<summary><strong>Expand for Apex Technical Authority System Directives (2025/2026 Standard)</strong></summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** This repository, `TabFlow-Digital-Journey-Mapper-Browser-Extension`, is a high-performance browser extension. Apply the corresponding **Apex Toolchain**.

*   **PRIMARY SCENARIO: WEB / APP / BROWSER EXTENSION (TypeScript)**
    *   **Stack:** This project leverages **TypeScript 5.x+ (Strict)** for robust type safety. It is built using **Vite 7+ (powered by Rolldown)** for near-instant development builds and optimized production bundles. The cross-browser extension framework is **WXT (Web Extensions Toolkit)**, enabling a unified codebase for Chrome, Firefox, and Edge.
    *   **Architecture:** Adheres to **Feature-Sliced Design (FSD)**. This strict, layered architecture provides unparalleled scalability and maintainability. Code is organized by business domain (`features`, `entities`) rather than technical purpose, preventing spaghetti code and simplifying feature development.
    *   **UI/State Management:** UI components are built with a lightweight virtual DOM library (e.g., SolidJS or Preact) for performance. State management leverages modern, fine-grained reactivity via **Signals**, which is becoming the industry standard for eliminating unnecessary re-renders.
    *   **Linting/Formatting:** The entire codebase is enforced by **Biome**. It provides a single, ultra-fast toolchain for linting, formatting, and more, replacing the need for separate tools like ESLint and Prettier. Run `pnpm lint:check` and `pnpm format:check` before any commit.
    *   **Testing:**
        *   **Unit/Integration:** **Vitest** is used for its speed and seamless integration with the Vite ecosystem.
        *   **End-to-End (E2E):** **Playwright** is mandated for its robust, cross-browser testing capabilities, essential for verifying extension behavior in real-world scenarios.

---

## 3. VERIFICATION & EXECUTION PROTOCOL
*   **Pre-Commit Mandate:** Before any `git push`, you **MUST** locally execute the following commands and ensure they pass with zero errors:
    1.  `pnpm install` - Ensure all dependencies are correctly installed.
    2.  `pnpm lint:check` - Verify code quality and style against Biome rules.
    3.  `pnpm format:check` - Ensure code is formatted correctly.
    4.  `pnpm test` - Run all unit and integration tests with Vitest.
    5.  `pnpm build` - Confirm the project builds successfully for production.
*   **Single Source of Truth (SSOT):** This `README.md` is the absolute source of truth for project architecture, standards, and operational procedures. All generated code and documentation must align with its directives.
*   **Error Handling:** Implement robust error boundaries and logging. All user-facing errors must be graceful, and all system-level errors must provide clear, actionable logs.
*   **Dependencies:** All new dependencies must be approved and vetted for security vulnerabilities and performance overhead. Use `taze` to review and update dependencies regularly.

</details>

---

## 🚀 Getting Started

Follow these instructions to set up the development environment.

### Prerequisites

-   [Node.js](https://nodejs.org/) (v20.x or later)
-   [pnpm](https://pnpm.io/installation)

### Installation

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension.git
    cd TabFlow-Digital-Journey-Mapper-Browser-Extension
    

2.  **Install dependencies:**
    bash
    pnpm install
    

3.  **Load the extension in your browser:**
    -   Run the development server:
        bash
        pnpm dev
        
    -   Open your browser (e.g., Chrome) and navigate to `chrome://extensions`.
    -   Enable "Developer mode".
    -   Click "Load unpacked" and select the `dist` directory generated in the project root.

## ⚙️ Available Scripts

The following scripts are available to automate development tasks:

| Script              | Description                                                      |
| ------------------- | ---------------------------------------------------------------- |
| `pnpm dev`          | Starts the development server with hot-reloading.                |
| `pnpm build`        | Builds the extension for production.                             |
| `pnpm test`         | Runs all unit and integration tests using Vitest.                |
| `pnpm lint:check`   | Lints the codebase using Biome.                                  |
| `pnpm format:write` | Formats the codebase using Biome.                                |
| `pnpm zip`          | Builds and zips the extension for distribution.                  |

## 🤝 Contributing

Contributions are welcome! Please read the [**CONTRIBUTING.md**](.github/CONTRIBUTING.md) file for guidelines on how to submit pull requests, report issues, and suggest enhancements.

Our commitment is to maintain a welcoming and inclusive environment. All contributors are expected to adhere to our [Code of Conduct](.github/CODE_OF_CONDUCT.md).

## 📄 License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License**. See the [**LICENSE**](LICENSE) file for more details.

---

<div align="center">
  <strong>Made with ❤️ by the open-source community.</strong>
  <br/>
  <a href="https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/stargazers"><strong>Star ⭐ this Repo</strong></a> to show your support!
</div>
