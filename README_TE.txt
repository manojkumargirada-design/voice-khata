Voice Khata v0.3 — Telugu-first demo

Files to upload to GitHub repository root:
- index.html
- manifest.webmanifest
- sw.js

Changes in v0.3:
- Debt preview shows unit price and calculation (quantity × rate = total).
- Debt history detail includes the unit rate.
- After preparing a preview, browser Telugu text-to-speech attempts to speak the total.
- Existing localStorage keys remain unchanged: vk_products, vk_customers, vk_tx.

Important:
- This is still a prototype, not production accounting software.
- Browser text-to-speech availability/voice depends on the Android device and installed voices.
- Speech recognition may require internet; offline Telugu microphone recognition is not guaranteed.
- Data remains in this browser's localStorage. Clearing site data can erase it.
- No cloud sync, login, encrypted backup, or multi-shop security yet.
- Test with sample data only; do not rely on it for real shop accounts.
