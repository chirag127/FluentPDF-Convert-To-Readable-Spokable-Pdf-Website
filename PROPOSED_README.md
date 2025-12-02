# FluentPDF-AI-PDF-To-Audio-Web-Platform

[![Build Status](https://img.shields.io/github/actions/workflow/ci.yml?style=flat-square&logo=github&label=Build&user=chirag127)](https://github.com/chirag127/FluentPDF-AI-PDF-To-Audio-Web-Platform/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/FluentPDF-AI-PDF-To-Audio-Web-Platform?style=flat-square&logo=codecov&label=Coverage)](https://codecov.io/gh/chirag127/FluentPDF-AI-PDF-To-Audio-Web-Platform)
[![Tech Stack](https://img.shields.io/badge/Tech%20Stack-TypeScript%2C%20Vite%2C%20React%2C%20TailwindCSS-blue?style=flat-square&logo=typescript&label=Stack)](https://github.com/chirag127/FluentPDF-AI-PDF-To-Audio-Web-Platform)
[![Lint/Format](https://img.shields.io/badge/Lint%2FFormat-Biome-green?style=flat-square&logo=biome&label=Lint)](https://github.com/chirag127/FluentPDF-AI-PDF-To-Audio-Web-Platform)
[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey?style=flat-square)](https://creativecommons.org/licenses/by-nc/4.0/)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/FluentPDF-AI-PDF-To-Audio-Web-Platform?style=flat-square&logo=github&label=Stars)](https://github.com/chirag127/FluentPDF-AI-PDF-To-Audio-Web-Platform/stargazers)

⭐ Star this Repo

## BLUF
FluentPDF is a privacy-first web platform that transforms technical PDFs into natural audio using in-browser, multi-provider LLMs. Experience high-performance, spoken-word narratives for enhanced learning, all while ensuring your data remains private.

## Architecture
ascii
  +-----------------------+
  |   FluentPDF Web App   |
  +-----------------------+
  |  +-----------------+  |
  |  |   User Input    |  |  (PDF Upload)
  |  +-----------------+  |
  |          |              |
  |          V              |
  |  +-----------------+  |
  |  |  PDF Parsing      |  |
  |  +-----------------+  |
  |          |              |
  |          V              |
  |  +-----------------+  |
  |  | Text Extraction  |  |
  |  +-----------------+  |
  |          |              |
  |          V              |
  |  +-----------------+  |
  |  | LLM Interaction  |  |
  |  +-----------------+  |
  |  | (Gemini, Groq)   |  |
  |  +-----------------+  |
  |          |              |
  |          V              |
  |  +-----------------+  |
  |  | Audio Generation |  |
  |  +-----------------+  |
  |          |              |
  |          V              |
  |  +-----------------+  |
  |  |  Audio Playback   |  |
  |  +-----------------+  |
  +-----------------------+


## Table of Contents

-   [AI Agent Directives](#ai-agent-directives)
-   [Development Standards](#development-standards)

<details>
<summary>🤖 AI Agent Directives</summary>

This section provides directives for AI agents interacting with the repository.

### Tech Stack Definition

*   **Language:** TypeScript (Strict Mode)
*   **Frontend Framework:** React
*   **Build Tool:** Vite
*   **Styling:** Tailwind CSS v4
*   **Testing:** Vitest (Unit Tests), Playwright (E2E Tests)
*   **Linting/Formatting:** Biome (speed)
*   **Architecture:** Feature-Sliced Design (FSD) principles are to be applied.

### Architectural Patterns

*   **SOLID Principles:** All code adheres to SOLID principles for maintainability and extensibility.
*   **DRY (Don't Repeat Yourself):** Minimize code duplication through reusable components and functions.
*   **YAGNI (You Ain't Gonna Need It):** Avoid implementing features unless they are explicitly required.

### Verification Commands

*   **Build:** `npm run build`
*   **Lint:** `npm run lint`
*   **Test:** `npm run test` (Runs Vitest unit tests and Playwright E2E tests)
*   **Format:** `npm run format`

</details>

## Development Standards

### Setup

bash
git clone https://github.com/chirag127/FluentPDF-AI-PDF-To-Audio-Web-Platform.git
cd FluentPDF-AI-PDF-To-Audio-Web-Platform
npm install


### Scripts

| Script          | Description                                           | Example                                  | 
| --------------- | ----------------------------------------------------- | ---------------------------------------- |
| `npm run dev`    | Starts the development server.                        | `npm run dev`                            |
| `npm run build`  | Builds the production-ready application.              | `npm run build`                          |
| `npm run lint`   | Runs the linter (Biome) to check code quality.       | `npm run lint`                           |
| `npm run format` | Formats the code using Biome.                      | `npm run format`                         |
| `npm run test`   | Runs unit and end-to-end tests using Vitest/Playwright. | `npm run test`                           |

### Principles

*   **SOLID:** Adhere to SOLID principles for maintainable code.
*   **DRY:** Avoid code duplication.
*   **YAGNI:** Implement only necessary features.
