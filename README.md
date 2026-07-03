# AI Session Archiver (ASA)

ASA is a Windows tool that saves your AI conversations to your own PC with a single click. It works with the web versions of ChatGPT, Claude, and Gemini — choose the edition that matches the service you use.

A small button (widget) is added to the chat screen of each AI service. Press it to save the conversation currently on screen as HTML, plain text, Markdown, or PDF. There is no limit on how many times you can save. Title, tags, and destination folder are all freely configurable, so ASA fits naturally into your existing workflow.

All data is stored on your device. Nothing is uploaded to the cloud or sent anywhere externally.

## Where to Get It
ASA is available from the following stores:
- **BOOTH:** <BOOTH_PRODUCT_URL>
- **Lemon Squeezy:** <LEMONSQUEEZY_PRODUCT_URL>

This repository is for **product information only** — the tool itself is not distributed here. Please purchase and download from the stores above.

In addition to normal chats, ASA supports saving shared chats, temporary/incognito chats, opted-out chats (Gemini), group chats (ChatGPT), and </> Code (Claude).

*Support for </> Code (Claude) is currently in beta.*

*Attached content such as AI-generated images is saved in HTML and PDF. In Markdown and plain text it is replaced with a placeholder such as [image].*

━━━━━━━━━━━━━━━━━━━━━━
## Specifications
━━━━━━━━━━━━━━━━━━━━━━
- **Product name:** AI Session Archiver (ASA)
- **Version:** 1.0.5
- **Lineup:** ChatGPT edition / Claude edition / Gemini edition
- **Supported OS:** Windows 10 / 11
- **Requirements:** Google Chrome
- **Output formats:** HTML / plain text (txt) / Markdown (md) / PDF
- **Storage:** On your device (fully local — no cloud upload)
- **Key features:**
  - One-click save widget
  - Capture mode
  - Auto-recovery (prevents loss of unsaved data)
  - Tagging (up to 50) / freely composed titles
  - Purpose-based subfolder routing / detailed PDF settings
- **Integration:** Chrome extension (distributed via the Web Store) + desktop app
- **Languages:** Japanese / English

━━━━━━━━━━━━━━━━━━━━━━
## How to Use
━━━━━━━━━━━━━━━━━━━━━━
1. Open a conversation page of an AI website in Chrome
2. Display the conversation you want to save
3. Click the ⬇ (save) on the widget — the conversation is saved
   (If the title confirmation dialog is enabled, continue to step 4)
4. In the title confirmation dialog you can edit the title and choose tags. Press OK to save.

━━━━━━━━━━━━━━━━━━━━━━
## Main Features
━━━━━━━━━━━━━━━━━━━━━━
**Save**
Saves the conversation currently on screen, as is.

**Capture mode**
Follows the screen as you scroll, gathering content and stitching it back into a single conversation before saving. While active, it keeps holding the conversation in real time.

**Auto-recovery**
Only during capture mode, it temporarily keeps the conversation even if you close the app or Chrome before saving. (Works only when enabled in settings.) On the next launch, if an unsaved conversation is found, a screen appears asking whether to save it. Intended for situations — such as temporary chats — where a conversation could be lost to a misclick or accident.

**Tagging**
Tags (labels) can be applied in three places: the file name, the title in the body, and the beginning of the body. Up to 50 can be registered, and you can choose whether they go at the start or end of the title.

**Title composition**
Builds the file name from parts such as date, time, and service name, arranged in the order you choose. Date/time formats and separators are adjustable. You can also edit the title on the spot before saving.

**Destination routing**
Beyond a shared destination, you can set an individual destination per format (HTML / md / txt / PDF). Subfolder splitting by format, and routing by project name or chat type, are also supported.

**Detailed PDF settings**
Page size, font, margins, and more can be configured. Custom fonts can be specified.

━━━━━━━━━━━━━━━━━━━━━━
## System Requirements
━━━━━━━━━━━━━━━━━━━━━━
- **OS:** Windows 10 / 11
- **Requirements:** Google Chrome
- No Python installation needed (bundled with the executable)

━━━━━━━━━━━━━━━━━━━━━━
## Getting Started
━━━━━━━━━━━━━━━━━━━━━━
1. Purchase from [BOOTH](<BOOTH_PRODUCT_URL>) or [Lemon Squeezy](<LEMONSQUEEZY_PRODUCT_URL>)
2. Extract the downloaded ZIP to any location
3. Run the setup file inside the folder
4. Follow the guide to add the extension from the Chrome Web Store

Detailed steps are provided in the bundled manual (README).

━━━━━━━━━━━━━━━━━━━━━━
## Notes
━━━━━━━━━━━━━━━━━━━━━━
- Due to specification changes on the AI service side, the tool may stop working without notice.
- In environments with mixed monitor resolutions, the display may break. This version is recommended for use on the main monitor.
- When using this tool, please review the terms of service of each AI service.

━━━━━━━━━━━━━━━━━━━━━━
## Copyright / License
━━━━━━━━━━━━━━━━━━━━━━
© 2026 Dialogue & Volts

- Copyright of this software belongs to Dialogue & Volts.
- It may be used within the scope of the purchaser's own personal use.
- Redistribution, resale, and distribution of modified versions are prohibited.
- This software is provided "as is" and its operation is not guaranteed.
- The author is not liable for any damages arising from its use.

This product uses the following open-source software:
reportlab / ttkbootstrap / Markdown / Python / Tcl-Tk
(See the bundled OSS_LICENSES.txt for each license.)
