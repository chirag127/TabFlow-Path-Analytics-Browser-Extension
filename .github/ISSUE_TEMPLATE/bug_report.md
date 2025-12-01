---
name: Bug Report
about: Report a bug in the TabFlow extension
title: "Bug: "
labels: bug, triage
assignees: ""

body:
  - type: markdown
    attributes:
      value: | # This is a markdown section header
        ### 🐛 Bug Report

        Thanks for reporting a bug! Please fill out the following information to help us diagnose and fix the issue quickly.

        **Please search our existing issues before opening a new one.**

        --- # Horizontal Rule

  - type: input
    id: version
    attributes:
      label: TabFlow Extension Version
      description: The version of the TabFlow extension you are using.
      placeholder: e.g., 1.2.3
    validations:
      required: true

  - type: input
    id: browser-version
    attributes:
      label: Browser and Version
      description: The browser (e.g., Chrome, Firefox) and its version where the bug occurred.
      placeholder: e.g., Chrome 120.0.0
    validations:
      required: true

  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: Describe the bug in detail. What were you doing when it occurred?
      placeholder: e.g., When I navigate to a specific website, the graph visualization becomes unresponsive.
    validations:
      required: true

  - type: textarea
    id: expected-behavior
    attributes:
      label: What did you expect to happen?
      description: Describe what you expected to happen instead.
      placeholder: e.g., I expected the visualization to update correctly and remain interactive.
    validations:
      required: true

  - type: textarea
    id: steps-to-reproduce
    attributes:
      label: Steps to Reproduce
      description: Provide a step-by-step guide on how to reproduce the bug.
      placeholder: |
        1. Install version X.Y.Z of TabFlow.
        2. Open Chrome.
        3. Navigate to `https://example.com`.
        4. Click on link A, then link B.
        5. Observe the visualization.
    validations:
      required: true

  - type: textarea
    id: screenshots-logs
    attributes:
      label: Screenshots or Screen Recordings (Optional)
      description: If possible, attach screenshots or a screen recording that demonstrates the bug. You can drag and drop files here.
    validations:
      required: false

  - type: textarea
    id: additional-context
    attributes:
      label: Additional Context (Optional)
      description: Any other relevant information that might help us understand the problem, such as your operating system, extensions you have installed, or specific website behaviors.
      placeholder: e.g., OS: Windows 11, Other extensions: AdBlock, Some sites with complex navigation chains seem to trigger this more often.
    validations:
      required: false

---
