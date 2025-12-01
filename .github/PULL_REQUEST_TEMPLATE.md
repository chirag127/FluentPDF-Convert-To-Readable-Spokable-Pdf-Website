--- 
name: Feature / Fix / Refactor Request
about: Propose a high-quality change to the FluentPDF Audio Narrative Generator Web App.
title: 'feat(scope): Concise description of the change'
labels: ['needs review', 'status: pending']
assignees: ['chirag127']
---

## 🚀 PULL REQUEST GATE CHECKLIST

**Failure to complete this checklist may result in the immediate closure of the PR.**

- [ ] **Code Quality:** All new and modified code adheres to the [Biome](https://github.com/chirag127/FluentPDF-Audio-Narrative-Generation-Web-App) formatting and linting standards (`pnpm lint:fix` ran successfully).
- [ ] **Testing:** Appropriate unit tests (Vitest) have been added or updated to cover all new logic, achieving **100% statement coverage** for the new code block.
- [ ] **E2E Verification:** Playwright E2E tests have been executed locally and passed, verifying critical user paths remain functional.
- [ ] **Feature-Sliced Design (FSD) Compliance:** All changes adhere strictly to the FSD structure (layers, slices, segments). No forbidden cross-layer imports exist.
- [ ] **Documentation:** README.md or relevant documentation (if API/Interface changes) has been updated.
- [ ] **Performance Review:** Changes do not introduce significant runtime performance regressions (especially in PDF parsing or LLM calls).

---

## 🌟 PR TYPE & SUMMARY

### Type of Change
_Select all that apply._

- [ ] ✨ Feature (Adds new functionality)
- [ ] 🐛 Bug Fix (Corrects an existing issue)
- [ ] 🔨 Refactor (Code structure improvement without changing external behavior)
- [ ] 📚 Documentation (Updates to `README.md` or other docs)
- [ ] ⚙️ CI/CD or Infrastructure (Changes to `.github/workflows` or deployment)

### Description
Please provide a detailed, high-level summary of the changes in this Pull Request.
_Link related issues here: Closes #ISSUE_NUMBER_

## 🏗️ TECHNICAL IMPLEMENTATION & ARCHITECTURE

1.  **Affected FSD Layers/Slices:** Which part of the architecture did this touch? (e.g., `features/audio-generation`, `shared/ui`, `app/providers`).
2.  **Key Architectural Decision:** Briefly explain why this approach was chosen (e.g., "Used Web Workers to isolate PDF parsing heavy lifting from the main thread").
3.  **LLM/Data Handling (CRITICAL):** If this PR touches data processing or LLM interaction, confirm:
    *   Is data strictly processed in-browser? [ ] Yes / [ ] No (If No, STOP and justify security implications).
    *   Are performance metrics (latency, payload size) acceptable? [ ] Yes
4.  **Security Impact:** Does this PR introduce new dependencies or handle user inputs? If so, detail steps taken to prevent XSS/injection vulnerabilities.

## 🧪 TESTING & VERIFICATION STEPS

To the reviewer: Please confirm these steps execute correctly.

1.  **Setup:** Clone this branch and run `pnpm install`.
2.  **Testing Environment:** Start the application via `pnpm dev`.
3.  **Specific Reproduction Steps:**
    *   Step 1: Navigate to [Specific Path].
    *   Step 2: Upload a 10MB PDF.
    *   Step 3: Verify the generated audio narrative starts within X seconds.
4.  **Screenshots/Gifs (Optional but Recommended):** Attach visual proof of the changes working.

## 📝 CODE REVIEW GUIDANCE

Reviewer Focus Areas:
- FSD compliance, specifically focusing on dependency directionality.
- Performance characteristics, especially around Web Workers/LLM threading.
- TypeScript strictness enforcement and type safety.

---
*(This template is enforced by the Apex Technical Authority. High Standards = High Velocity.)*