# ⚡ BlazeShot - Premium Productivity Suite

Welcome to **BlazeShot**, a powerful and lightweight browser extension designed to supercharge your web browsing experience. Whether you need to declutter annoying web elements permanently, save important research links, or record tab audio, BlazeShot puts an entire suite of premium tools right inside your browser.

This repository hosts the official distribution releases for BlazeShot. 

## Key Features

### DOM Zapper Mode
Interactively select and permanently hide/delete annoying elements (banners, popups, sidebars) from any webpage.
* **Keyboard Shortcuts**:
  * `Ctrl + Shift + Z` - Activate the Zapper cursor.
  * `Ctrl + Shift + X` - Undo the last zapped element.
  * `Esc` - Cancel and exit Zapper mode.
* **Rules Registry**: View, manage, search, and delete your active zapper rules per domain directly from the premium Options dashboard.

### Reading List ("Save for Later")
Never lose track of important information. Save pages or specific text snippets instantly using the Right-Click context menu:
* **Save Page**: Right-click anywhere on a page to save the URL and title.
* **Save Text Note**: Highlight any text, right-click, and save it as a quoted note.
* **Dashboard**: Access and manage all your saved items in a beautiful, glassmorphic Reading List tab.

### Tab Audio Recorder (Chrome Only)
Capture high-quality internal tab audio streams natively. 
* Listen to the audio live while recording.
* Generates clean `.mp3` / `.webm` downloads without requiring external desktop software. 
* *(Note: Due to browser engine limitations, this feature is hidden on Firefox).*

### Color Picker & Link Grabber
Quickly extract colors (HEX/RGB) or compile a list of all URLs present on the current webpage right from the popup menu.

### Premium Dashboard
* Beautiful, responsive glassmorphism UI.
* Safe Import/Export utility with strict JSON verification to backup and restore your settings, snippets, and zapper rules across devices.

---

## How to Install (Manual Installation)

Since BlazeShot is currently not distributed via the official Web Stores, you can easily install it manually using the Developer Mode in your browser.

### For Google Chrome, Edge, and Brave:
1. Go to the [Releases page](../../releases) of this repository.
2. Download the latest `BlazeShot Chrome vX.X.X.zip` file.
3. Extract/Unzip the downloaded file into a folder on your computer.
4. Open your browser and go to the extensions page:
   * Chrome: `chrome://extensions/`
   * Edge: `edge://extensions/`
   * Brave: `brave://extensions/`
5. Turn on **Developer mode** (usually a toggle in the top right corner).
6. Click on the **Load unpacked** button.
7. Select the folder where you extracted the BlazeShot files. 
8. **Done!** Pin the extension to your toolbar for quick access.

### For Mozilla Firefox:
1. Go to the [Releases page](../../releases) of this repository.
2. Download the latest `BlazeShot Firefox vX.X.X.zip` file.
3. Extract/Unzip the downloaded file into a folder on your computer.
4. Open Firefox and type `about:debugging#/runtime/this-firefox` in the address bar.
5. Click on the **Load Temporary Add-on...** button.
6. Navigate to your extracted folder and select the `manifest.json` file.
7. **Done!** The extension is now active. *(Note: Firefox requires you to reload temporary add-ons if you restart the browser).*

---

## 🔒 Privacy First
BlazeShot is built with absolute respect for your privacy. **No data ever leaves your device.** 
All saved links, zapper rules, and text snippets are stored entirely within your browser's local storage (`chrome.storage.local`). We do not use any external databases or tracking analytics.
