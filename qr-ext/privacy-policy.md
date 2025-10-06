# QR Overlay Scanner — Privacy Policy

**Last updated:** October 7, 2025

---

## Summary

QR Overlay Scanner processes all data locally in your browser. We do not collect, store, or transmit any personal information.

---

## Data Processing

* The extension captures a temporary image of the currently visible browser tab (via the `chrome.tabs.captureVisibleTab` API).
* This image is used only once to detect and decode a QR code.
* The image never leaves your device — it remains fully within the browser’s memory and is immediately discarded after processing.

---

## Permissions Justification

| Permission  | Purpose                                                          | Data Stored or Transmitted |
| ----------- | ---------------------------------------------------------------- | -------------------------- |
| `activeTab` | Allows access to the current tab for scanning a visible QR code. | No                         |
| `scripting` | Injects the floating overlay UI and styles into the page.        | No                         |
| `storage`   | Saves local preferences (theme, language, search engine).        | Stored locally only        |
| `tabs`      | Required by Chrome to identify the current tab for capture.      | No                         |

---

## Data Collection

* ❌ No telemetry or analytics
* ❌ No cookies
* ❌ No user accounts
* ❌ No external API calls

All processing (QR recognition, UI state, and preferences) happens offline within the browser.

---

## Third-Party Services

The extension does not use or integrate with any third-party services or SDKs.

---

## Security

* No network requests are made.
* The extension cannot access data outside the currently active tab.
* All source code is open and available for audit on GitHub.

---

## Contact

For questions, suggestions, or concerns:

**Email:** [kirillsakharov.personal@gmail.com](mailto:kirillsakharov.personal@gmail.com)
---