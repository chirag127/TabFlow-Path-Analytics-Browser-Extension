# 🚀 Pull Request Checklist & Review Guide

**Project:** TabFlow-Digital-Journey-Mapper-Browser-Extension

This template ensures that all PRs are reviewed efficiently and adhere to the highest architectural standards established by the Apex Technical Authority.

---

## 1. Summary & Motivation

<!-- Briefly describe what this PR does and why it is necessary. Link to any relevant issues (e.g., `Closes #123`). -->

**Type of Change:**

- [ ] Feature/New Capability
- [ ] Bug Fix (Non-breaking)
- [ ] Refactoring / Code Cleanup
- [ ] Documentation Update
- [ ] Build/CI Configuration
- [ ] Performance Improvement

### Value Proposition

*What tangible benefit does this change bring to the user or the codebase?*

---

## 2. Technical Scope & Verification

<!-- Detail the architectural decisions made and how this change impacts the existing structure (FSD, strict TypeScript, etc.). -->

### Architecture Review

*   **Affected Modules/Features:** (e.g., `history-tracking-service`, `graph-renderer`)
*   **Design Pattern Adherence:** (e.g., Did this follow the established Feature-Sliced Design principles?)
*   **Testing Implemented?** (Crucial for non-trivial changes)

### Verification Steps

**Instructions for the Reviewer:** Please use these steps to validate the functionality.

1.  **Setup:** Checkout branch and install dependencies (`npm install` or `pnpm install`).
2.  **Build:** Run the local build command (`npm run build`).
3.  **Feature Test:** Navigate to `chrome://extensions`, enable Developer Mode, and load the unpacked extension.
4.  **Scenario:** (e.g., Visit 5 distinct external websites in sequence).
5.  **Expected Result:** The resulting graph visualization in the extension popup accurately reflects the sequence, including correct referral chaining.
6.  **Linter Check:** Run `npx @biomejs/biome check --apply src/` to confirm linting standards.

---

## 3. Self-Assessment Checklist (Author)

I confirm that I have reviewed my own code against the following standards:

- [ ] **Code Clarity:** Variables and functions are clearly named (e.g., no single-letter variables).
- [ ] **Type Safety:** All new or modified functions adhere to strict TypeScript types.
- [ ] **Error Handling:** Edge cases and potential API failures are handled gracefully (using custom exceptions if necessary).
- [ ] **Documentation:** Affected public APIs/components have updated JSDoc comments.
- [ ] **Dependencies:** No new, unvetted dependencies were added without justification.
- [ ] **Performance:** I have considered the impact on DOM manipulation/memory usage, given this is a persistent extension.
- [ ] **Security:** No secrets or unauthorized third-party calls have been introduced.

---

## 4. Final Notes

<!-- Any final comments, screenshots, or specific areas the reviewer should focus on. -->
