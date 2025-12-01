---
name: Bug Report
about: Report a bug in the project.
labels: bug, triage
---/

## :bug: Bug Report

Thank you for reporting a bug! Please provide as much detail as possible to help us diagnose and fix the issue.

**Before submitting:**

1.  **Search:** Please search the existing [Issues](https://github.com/FluentPDF/FluentPDF-AI-PDF-To-Audio-Web-Platform/issues) to see if this bug has already been reported.
2.  **Reproducibility:** Ensure the bug can be reliably reproduced.

---

### 1. Environment Details

*   **Project Version:** (e.g., `1.0.0` or commit hash if not released)
*   **Operating System:** (e.g., Windows 11, macOS Sonoma, Ubuntu 22.04)
*   **Browser:** (e.g., Chrome 120, Firefox 118, Safari 17) - **If applicable**
*   **Device:** (e.g., Desktop, Mobile - iPhone 15, Pixel 8) - **If applicable**

---

### 2. Describe the Bug

A clear and concise description of what the bug is. What did you expect to happen, and what actually happened?

**Expected Behavior:**

> (Describe what you expected to happen)

**Actual Behavior:**

> (Describe what actually happened)

---

### 3. Steps to Reproduce

Provide a step-by-step guide to reproduce the behavior. Include any data or files necessary to reproduce the issue.

1.  Go to `[URL or Section]`
2.  Click on `[Button/Element]`
3.  Enter `[Specific Input]`
4.  Observe `[The Unexpected Outcome]`

---

### 4. Screenshots or Screen Recordings

If possible, add screenshots or a short screen recording to help explain your problem. You can attach files directly in the comment box.

*   [Attach Screenshot 1]
*   [Attach Screenshot 2]

---

### 5. Additional Context

Any other context about the problem. For example, performance issues, specific PDF files that cause problems, error messages, etc.

*   **Error Message:** (If any, copy and paste the full error)
*   **Specific PDF:** (If the issue is related to a specific PDF, describe its characteristics or attach a sanitized version if possible)
*   **Network Conditions:** (e.g., Slow, Fast, Offline)

---

### :robot: AI Agent Directives (Internal Use)

<details>
  <summary>Apex Technical Authority - AI Directives</summary>

  **Project:** FluentPDF-AI-PDF-To-Audio-Web-Platform
  **Language:** TypeScript
  **Framework/Environment:** Tauri v2.x, Vite 7, TypeScript 6.x, Browser/Electron Runtime
  **Key Technologies:** LLMs (Gemini, Groq, Cerebras), WebAssembly, Client-side Processing
  **Architecture:** Feature-Sliced Design (FSD), Client-Side Data Processing, Privacy-First, Zero-Dependency (Client-side).
  **Linting/Formatting:** Biome
  **Testing:** Vitest (Unit), Playwright (E2E)
  **CI/CD:** GitHub Actions (Lint, Test, Build, Release)
  **Core Principles:** SOLID, DRY, KISS, CQS, 12-Factor App, Zero Trust Security.
  **DevSecOps:** Input Sanitization (OWASP 2025), SBOM generation, Fail Fast, Encryption.
  **UI/UX:** Liquid Glass + Neo-Brutalist + Material You 3.0, Fluid Animations, INP Optimization, Optimistic UI, Hyper-Personalization, Micro-interactions.

  **Diagnostic Directives:**
  *   Trace LLM API calls and responses.
  *   Analyze client-side PDF parsing logic for errors.
  *   Verify browser/Electron sandbox interactions.
  *   Check for race conditions in asynchronous audio generation.
  *   Validate data privacy adherence during processing.
  *   Review UI state management for consistency.
  *   Ensure adherence to ARIA standards for accessibility.

  **Debug Strategy:** Leverage Biome for static analysis, Vitest for targeted unit tests, and Playwright for end-to-end scenario validation. Analyze console logs and network requests for anomalies. Isolate the problematic feature slice.

</details>
