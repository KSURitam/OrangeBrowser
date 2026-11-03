<p align="center">
  <img src="logo.png" alt="Orange Browser" width="160">
</p>

<h1 align="center">Orange Browser</h1>
<p align="center"><b>A Private &amp; Secure Browser</b></p>

<p align="center">
  <a href="https://github.com/KSURitam/OrangeBrowser/releases/tag/Apk">
    <img src="https://img.shields.io/badge/Download-APK-EA580C?style=for-the-badge&logo=android&logoColor=white" alt="Download APK">
  </a>
</p>

**[⬇ Download APK](https://github.com/KSURitam/OrangeBrowser/releases/tag/Apk)**
---

## About

Orange Browser is a lightweight Android web browser focused on privacy and security. It uses the Android System WebView engine, Google as the default search engine, and has no accounts, no ads, no analytics and no servers of its own. Your bookmarks, settings and (only if you allow it) history stay on your device.

- **Version:** Beta 3.1
- **Package:** `com.orangebrowser.app`
- **Requires:** Android 5.0 (API 21) or newer, with an up-to-date Android System WebView

## Install

1. Tap **Download APK** above and save the file.
2. Open it. If Android asks, allow **Install unknown apps** for your browser or file manager.
3. Tap **Install**, then open **Orange Browser**.

## Features

### Browsing
- Combined address and search bar. Type a website to open it, or type a search to use Google (Bing and DuckDuckGo are selectable in Settings)
- Multiple tabs, back / forward / refresh / stop, home button, bookmark star
- Desktop site mode, switchable per site from the menu, with a list of sites that open in desktop mode automatically
- Find in page, share, copy link, open in another browser
- Bookmarks and a download manager (uses Android's downloads screen)
- File upload support through the system file picker
- Pop-up blocking, and sign-in pop-ups open as tabs
- Pinch zoom, adjustable text size and font style
- White, dark and system themes, with a clean splash screen

### Privacy
- **History is your choice.** On first use the browser asks: *Save History*, *Don't Save History* or *Decide Later*. Nothing is saved until you agree. History can be searched, deleted entry by entry, or cleared completely
- **Private mode** runs in its own separate process:
  - Browsing is never added to history
  - On Android 9 and newer it has its own cookie and storage area, separate from normal browsing
  - Private cookies are cleared every 2 minutes and when the private session ends
  - No cache, no downloads, no saved bookmarks, and screenshots are blocked
  - Normal-mode cookies and logins are never touched
  - Private mode reduces traces on your device. It does not make you anonymous: websites, your network and your internet provider can still see your activity
- **Third-party cookies** are blocked by default, with per-site exceptions
- **Ad blocker** and **tracking protection** (blocks known ad and tracker domains, sends Do Not Track / Global Privacy Control). Both can be switched off in Settings, and the ad blocker pauses on Google sign-in pages. The built-in lists are a starting point and do not block every ad
- No analytics, no advertising SDKs, no user accounts

### Security
- HTTPS by default. Plain HTTP sites show a clear **Not secure** warning page
- Certificate errors are never bypassed
- Suspicious redirects and deceptive addresses (for example `user@site`) are blocked
- Local blocklist of malicious domains, plus Google Safe Browsing check (can be switched off)
- Website permissions for **location, camera and microphone** always ask first, with *Allow / Block / Ask* per site, a permission manager and Android's own permission dialogs
- Localhost and local-network addresses (`localhost`, `127.0.0.1`, `192.168.x.x`) work over HTTP for development. This can be switched off in Settings

### Settings
Privacy & security, website permissions, browser options (JavaScript, cookies, pop-ups, homepage, search engine), storage & downloads, appearance (theme, text size, font style, toolbar buttons) and an About page.

## Known limitations

- Google may refuse sign-in inside any embedded browser. If that happens, Orange Browser offers to open the page in a Chrome tab, but that sign-in is not shared with Orange Browser
- Android WebView does not support website notifications or contacts access
- Private mode needs Android 9 or newer for its separate cookie area. On older versions it accepts no cookies
- Search suggestions are not included

## Privacy policy

Orange Browser has no servers, accounts, analytics or advertising. Bookmarks, settings, site permissions and (only if you allow it) history are stored on your device only and are never uploaded by the app. Websites you visit, and Google Safe Browsing if enabled, receive normal web requests.

## Terms

Provided as is, without warranty. You are responsible for the sites you visit and the permissions you grant.

---

<p align="center">Orange Browser · A Private &amp; Secure Browser</p>
