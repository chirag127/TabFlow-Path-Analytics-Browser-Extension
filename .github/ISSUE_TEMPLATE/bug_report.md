---
name: "🐛 System Integrity Failure Report"
about: Report a failure in tracking, rendering, or core architectural logic of the extension.
title: "[BUG] Descriptive summary of the unexpected behavior or failure point"
labels: ['bug', 'triage:needed', 'priority:medium', 'type:integrity']
assignees: ['chirag127']
---

Thank you for taking the time to report this critical issue. Your detailed input helps us maintain the **Zero-Defect Standard** for the **TabFlow Digital Journey Mapper**. Before submitting, please ensure you have completed the following diagnostic steps.

---

## 🛑 Pre-flight Diagnostic Checklist

Please check all relevant boxes before proceeding. **Incomplete reports will be immediately closed pending required information.**

- [ ] I have searched the [existing issues](https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/issues) to ensure this bug has not already been reported.
- [ ] I am running the **latest stable release or the current main branch build**.
- [ ] I have read the [CONTRIBUTING Guidelines](CONTRIBUTING.md).
- [ ] This bug occurs consistently and is easily reproducible.
- [ ] I have attached relevant diagnostic logs (console output, network tab details).

---

## 1. System and Environment Integrity

Provide crucial information about the environment where the bug was encountered. This is essential for accurate reproduction.

### Extension Details
*   **TabFlow Version:** [e.g., v1.2.5, or `main` branch commit SHA]
*   **Installation Method:** [e.g., Chrome Web Store, Firefox Add-on Store, Local build]
*   **Active Mode:** [e.g., Default (Full Tracking), Incognito Mode, Selective Tracking]

### Host Environment
*   **Browser Name & Version:** [e.g., Chrome 127.0.6533.0, Firefox 128]
*   **Operating System:** [e.g., macOS Sonoma 14.4, Windows 11, Linux]
*   **System Architecture:** [e.g., x64, ARM64]

---

## 2. Steps to Reproduce (GIVEN/WHEN/THEN Format)

Provide a precise, step-by-step description using the **GIVEN-WHEN-THEN** structure. Aim for deterministic reproduction.

1.  **GIVEN** I have initiated a tracking session by [Describe state, e.g., opening a new window, clearing history].
2.  **WHEN** I navigate from `Page A` (`[Start URL]`) to `Page B` (`[Next URL]`) via [e.g., link click, form submission, programmatic redirect].
3.  **AND THEN** [Next critical step, e.g., I close the original tab or wait 60 seconds].
4.  **RESULT:** [Describe the immediate failure point].

### Relevant URLs
If applicable, list the sequence of URLs involved in the journey where the tracking failed:
*   URL 1: `[Start URL]`
*   URL 2: `[Next URL]`
*   ...

---

## 3. Expected vs. Actual Behavior (CQS Analysis)

### Expected Behavior (The Query Result)
Describe exactly what the software should have done, adhering to the principle of Command-Query Separation (CQS).
> *Example: The journey map should correctly render a directed edge from the node representing Page A to the node representing Page B, with appropriate timestamp metadata.* 

### Actual Behavior (The Observed Failure)
Describe exactly what happened instead, including any visual discrepancies, frozen UI elements, or data loss.

---

## 4. Diagnostic Output and Context

Please provide any additional information that might assist in zero-day debugging. Logs are the single most important component of a valid bug report.

### Console Logs (Browser Developer Tools F12)
Capture all output from the background service worker or the extension popup console, focusing on red error messages and stack traces.

javascript
// Paste error logs, stack traces, or console output here.


### Screenshots / Recordings
If the issue is visual (e.g., graph rendering corruption), please attach high-resolution screenshots or a short screen recording.

### Potential Root Cause Analysis (Optional)
If you have investigated the codebase or network activity, provide a hypothesis here. This accelerates the fix process.

---
*This bug report template enforces the **Apex Technical Authority** standard for maximum diagnostic efficiency.*
