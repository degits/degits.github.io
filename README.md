# Chat Scraper Extension

A Chrome extension that allows users to save their AI chat conversations from supported platforms directly in their browser for personal reference. Supported platforms include:

- ChatGPT (`https://chatgpt.com/*`)
- Gemini (`https://gemini.google.com/app/*`)
- Claude (`https://claude.ai/*`)

All data is stored **locally** in the browser using Chrome's `chrome.storage.local` API.

---

## Features

- Scrape chat content visible to the user on supported AI platforms
- Save chat messages locally for offline reference
- Minimal permissions required for secure operation

---

## Permissions

The extension requires the following permissions:

- **`storage`**  
  Used to save chat content locally in the browser. No data is transmitted to external servers.

- **Host permissions**  
  Limited to the supported AI chat platforms only, to scrape content visible to the user:
  - `https://chatgpt.com/*`
  - `https://gemini.google.com/app/*`
  - `https://claude.ai/*`

The extension does **not** collect personal data, authentication info, financial data, health data, location, or browsing history.

---

## Privacy Policy

This extension does **not collect, transmit, or share** any personal data with third parties. All chat content is stored locally in the user’s browser.  

- No user data leaves the device.  
- No third-party services are used.  
- All processing happens locally.

For questions, contact: [tdm.dev2@gmail.com](mailto:tdm.dev2@gmail.com)

---

## Disclaimer

This extension only accesses content that the user can already see on supported AI chat platforms. It is designed for personal use and does not track or monitor user activity outside the specified platforms.
