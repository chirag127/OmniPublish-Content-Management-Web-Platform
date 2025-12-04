<div align="center">
  <!-- Placeholder for a real logo -->
  <img src="https://raw.githubusercontent.com/chirag127/OmniPublish-Content-Management-Web-Platform/main/.github/assets/logo.png" alt="OmniPublish Logo" width="150"/>
  <h1>OmniPublish</h1>
  <p><strong>A robust web platform for unified content publishing across multiple channels.</strong></p>
</div>

<div align="center">

[
![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/OmniPublish-Content-Management-Web-Platform/ci.yml?branch=main&style=flat-square&logo=githubactions&logoColor=white)
](https://github.com/chirag127/OmniPublish-Content-Management-Web-Platform/actions/workflows/ci.yml)
[
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/OmniPublish-Content-Management-Web-Platform?style=flat-square&logo=codecov&logoColor=white)
](https://codecov.io/gh/chirag127/OmniPublish-Content-Management-Web-Platform)
[
![Tech Stack](https://img.shields.io/badge/Stack-TypeScript%20%7C%20Vite%20%7C%20React%20%7C%20Tailwind-blue?style=flat-square&logo=typescript&logoColor=white)
](https://github.com/chirag127/OmniPublish-Content-Management-Web-Platform)
[
![Lint & Format](https://img.shields.io/badge/Lint%20%26%20Format-Biome-blueviolet?style=flat-square&logo=biome&logoColor=white)
](https://biomejs.dev/)
[
![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg?style=flat-square)
](https://github.com/chirag127/OmniPublish-Content-Management-Web-Platform/blob/main/LICENSE)
[
![GitHub Stars](https://img.shields.io/github/stars/chirag127/OmniPublish-Content-Management-Web-Platform?style=flat-square&logo=github&logoColor=white)
](https://github.com/chirag127/OmniPublish-Content-Management-Web-Platform/stargazers)

</div>

<div align="center">
  <a href="https://github.com/chirag127/OmniPublish-Content-Management-Web-Platform/stargazers">
    <img src="https://img.shields.io/static/v1?label=Star&message=this%20Repo&style=social&logo=github" alt="Star this Repo">
  </a>
</div>

---

**OmniPublish** is a robust web platform for unified content publishing across multiple channels. It streamlines content creation, scheduling, and distribution, providing a single source of truth for your digital presence.

## Table of Contents

- [Architecture](#architecture)
- [🤖 AI Agent Directives](#-ai-agent-directives)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Core Principles](#core-principles)
- [License](#license)

## Architecture

This project adheres to **Feature-Sliced Design (FSD)**, a scalable and maintainable architectural methodology for frontend applications. It promotes a clear separation of concerns and reduces complexity as the application grows.

sh
src/
├── app/          # App-level logic, routing, global styles, providers
├── pages/        # Composition of features and widgets into complete pages
├── widgets/      # Composition of multiple entities/features (e.g., Header, Sidebar)
├── features/     # Business logic units (e.g., publish-content, schedule-post)
├── entities/     # Core business entities (e.g., Post, User, Channel)
└── shared/       # Reusable modules (UI Kit, APIs, config, utils)


## 🤖 AI Agent Directives

<details>
<summary><strong>SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)</strong></summary>

### 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

### 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat this `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

### 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the corresponding **Apex Toolchain**. This repository, `OmniPublish-Content-Management-Web-Platform`, is an enterprise-grade web application.

*   **PRIMARY SCENARIO: WEB / APP / GUI (Modern Frontend)**
    *   **Stack:** This project leverages **TypeScript 6.x (Strict Mode)**, **Vite 7** (with the Rolldown Rust-based bundler), **React 19**, and **TailwindCSS v4**. The environment is managed by `pnpm` for efficient dependency handling.
    *   **Architecture:** Strictly adheres to **Feature-Sliced Design (FSD)** to ensure maximum scalability, maintainability, and logical separation of concerns. All new components, logic, and modules must be placed within the appropriate slice (`shared`, `entities`, `features`, `widgets`, `pages`, `app`).
    *   **Linting & Formatting:** A unified, high-performance toolchain is enforced via **Biome**. All code must pass Biome's linter and formatter before being committed. Run `pnpm format` and `pnpm lint`.
    *   **Testing:** A comprehensive testing strategy is mandatory:
        *   **Unit/Integration Tests:** Use **Vitest** for its speed and native Vite integration. Tests should be co-located with the source code.
        *   **E2E Tests:** Use **Playwright** for robust, cross-browser end-to-end testing of user flows.

</details>

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- Node.js (v20.x or later)
- pnpm (v9.x or later)

### Installation

1.  Clone the repository:
    sh
    git clone https://github.com/chirag127/OmniPublish-Content-Management-Web-Platform.git
    
2.  Navigate to the project directory:
    sh
    cd OmniPublish-Content-Management-Web-Platform
    
3.  Install dependencies:
    sh
    pnpm install
    

## Available Scripts

In the project directory, you can run:

| Script          | Description                                           |
| --------------- | ----------------------------------------------------- |
| `pnpm dev`      | Runs the app in development mode.                     |
| `pnpm build`    | Builds the app for production.                        |
| `pnpm test`     | Runs the unit and integration tests with Vitest.      |
| `pnpm test:e2e` | Runs the end-to-end tests with Playwright.            |
| `pnpm lint`     | Lints all files using Biome.                          |
| `pnpm format`   | Formats all files using Biome.                        |

## Core Principles

This project is built upon a foundation of industry-standard software design principles to ensure it remains clean, scalable, and maintainable.

-   **SOLID:** Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion.
-   **DRY (Don't Repeat Yourself):** Avoid duplicating code by abstracting common logic into reusable modules.
-   **YAGNI (You Ain't Gonna Need It):** Avoid implementing functionality that is not immediately required.

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License - see the [LICENSE](https://github.com/chirag127/OmniPublish-Content-Management-Web-Platform/blob/main/LICENSE) file for details.
