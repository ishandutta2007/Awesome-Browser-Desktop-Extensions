# Awesome-Browser-Desktop-Extensions

## Top Browser & Desktop Extensions Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Productivity, Password Management, Content Clipping & Asynchronous Communication*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Browser & Desktop Extensions**. These tools extend browser and desktop functionality—covering password management, grammar checking, screen recording, web clipping, CRM integration, and read-later workflows—helping users capture, organize, and act on information without leaving their workflow.

**Examples** include Zoho Plug-in, LastPass Extension, Grammarly Extension, Loom Extension, Evernote Web Clipper, HubSpot Sales Extension, 1Password Extension, Notion Web Clipper, ClickUp Extension, and Pocket Extension (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted password managers, open-source grammar checkers, local-first web clippers, and community-driven screen recording tools—ideal for privacy-conscious users, developers, and teams seeking transparent, vendor-neutral alternatives to proprietary extensions.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Zoho Plug-in (Zoho CRM for Gmail)](https://chromewebstore.google.com/detail/zoho-crm-for-gmail/ojhlgnehlajjgpneocngnphjellkjgch)**  
  Gmail extension for managing Zoho CRM leads and contacts directly from the inbox; create contacts/leads, log calls, add tasks/events, and create deals without switching tabs .

- **[LastPass Extension](https://support.lastpass.com/)**  
  Password manager extension with autofill, secure password generation, vault access, and at-risk password alerts; supports federated login via identity providers including Microsoft Entra ID, Okta, and Google Workspace [citation:2][citation:13].

- **[Grammarly Extension](https://www.grammarly.com/browser/chrome)**  
  AI writing assistant working across 500,000+ apps and sites including Gmail, Google Docs, Salesforce, and Jira; provides grammar correction, tone detection, generative AI drafts, and plagiarism detection [citation:3][citation:14].

- **[Loom Extension](https://chromewebstore.google.com/detail/loom-%E2%80%93-screen-recorder-sc/liecbddmkiiihnedobmlmillhodjkdmb)**  
  Screen and camera recording extension with instant cloud link sharing; supports time-stamped comments, viewer analytics, and integration with Slack and Microsoft Teams [citation:4].

- **[Evernote Web Clipper](https://chromewebstore.google.com/detail/evernote-web-clipper/pioclpoplcdbaefihamjohnefbikjilc)**  
  Saves web pages, articles, PDFs, and screenshots directly to Evernote; supports full-page capture, annotations, tagging, and notebook organization .

- **[HubSpot Sales Extension](https://chromewebstore.google.com/detail/hubspot-sales/oiiaigjnkhngdbnoookogelabohpglmd)**  
  Gmail CRM sidebar with email tracking, templates, meeting scheduling, and Breeze AI Copilot; connects inbox activity to HubSpot Smart CRM for pipeline management .

- **[1Password Extension](https://1password.com/downloads/browser-extension)**  
  Password manager with autofill, passkey support, 2FA code filling, and secure item sharing; syncs across Chrome, Firefox, Safari, Edge, and Brave [citation:7].

- **[Notion Web Clipper](https://www.notion.com/help/web-clipper)**  
  Saves any web page to a Notion workspace or database; auto-adds URL property, supports tagging, and works on Chrome and Safari (desktop) plus mobile share sheets [citation:8].

- **[ClickUp Extension](https://clickup.com/chrome-extension)**  
  Creates tasks from websites and emails, captures annotated screenshots, and tracks time natively; website tasks include screenshots and hyperlinks .

- **[Pocket Extension](https://getpocket.com/)**  
  Read-later extension for saving articles, videos, and web pages to a personal library; organizes content with tags and offers offline access across devices.

## Open-Source GitHub Projects

- **[LanguageTool](https://github.com/languagetool-org/languagetool)**  
  Open-source grammar and style checker supporting 25+ languages; privacy-focused alternative to Grammarly with browser extensions for Chrome and Firefox [citation:16][citation:23].

- **[SingleFile](https://github.com/gildas-lormeau/SingleFile)**  
  Web extension for saving a faithful copy of a complete web page as a single HTML file; open-source alternative to Evernote Web Clipper with annotation support and offline access [citation:17].

- **[Notesnook Web Clipper](https://github.com/streetwriters/notesnook)**  
  End-to-end encrypted note-taking app with a dedicated web clipper extension; clips pages into a privacy-focused notes system using XChaCha20-Poly1305 encryption [citation:24].

- **[TriliumNext Notes (Web Clipper)](https://github.com/TriliumNext/Trilium)**  
  Hierarchical note app with built-in web clipper for capturing pages with one click; self-hostable via Docker with SQLite backend and full-text search [citation:21][citation:28].

- **[Cap (Open-Source Loom Alternative)](https://github.com/CapSoftware/Cap)**  
  Cross-platform screen recording and video messaging tool built with Rust and Tauri; supports self-hosting, browser recording, and shareable links as a Loom alternative .

- **[SendRec](https://github.com/sendrec/sendrec)**  
  Self-hosted async video messaging platform; open-source Loom alternative with browser recording, AI transcription (local Whisper or cloud), timestamped comments, and viewer analytics [citation:19].

- **[StashRead](https://addons.mozilla.org/firefox/addon/stashread/)**  
  Privacy-first read-later extension as a local alternative to Pocket; saves articles, extracts full content, supports tagging, and exports to EPUB for Kindle [citation:18].

- **[Stashed](https://chromewebstore.google.com/detail/stashed/kkobgegdpdfgghkodioiadheabllcflg)**  
  Open-source Pocket alternative for saving and organizing web pages; supports one-click saving, tags, folders, and cross-device sync with user-controlled data [citation:25].

### Additional Strong Open-Source Options

- **[Zecrypt Server](https://github.com/zecrypt-io/zecrypt-server)** — Open-source password manager and encrypted data platform positioned as a LastPass alternative, built with FastAPI and Next.js [citation:20].
- **[SleekAddons Browser Extensions](https://github.com/SleekAddons/browser-extensions)** — Monorepo of open-source extensions including Table Extractor, Pi-hole Manager, and Website Blocker built with WXT and React [citation:11].
- **WebExtension-based password managers** (Bitwarden, KeePassXC-Browser) and **open-source clipboard managers** for custom productivity stacks.

**Frameworks for building custom systems**: Combine **LanguageTool** for writing assistance, **SingleFile** or **Notesnook Clipper** for content capture, **Cap** or **SendRec** for self-hosted video messaging, and **StashRead** for local-first read-later workflows—all integrable via browser extension APIs and Docker deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Browser extensions request varying levels of data access; review permissions and privacy policies before installation, especially for tools handling passwords, email, or browsing history.
- Self-hosted open-source extensions and services require proper security hardening, regular updates, and backup strategies to protect user data.

---

**Made for privacy-conscious users, productivity enthusiasts, developers, and teams building open browser tooling.**  
Let's make browser extensions more open, transparent, and user-controlled.
