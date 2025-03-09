# Discord Webhook Sender Chrome Extension 🚀

## Description

The **Discord Webhook Sender** is a Chrome extension that simplifies sending links 🔗, images 🖼️, and clipboard content 📋 directly to your Discord channels via webhooks 🌐.  No more copying and pasting webhook URLs or manually formatting messages! 🎉 This extension allows you to quickly share content from the web to your Discord server with just a few clicks🖱️.

## Features

* **Context Menu Integration:** ✨
    * **Share Link:** Right-click on any link or webpage to quickly share the URL to your Discord webhook.
    * **Share Image:** Right-click on any image to send the image file directly to your Discord webhook.
* **Popup Interface:** ⚙️
    * **Profile Management:** Create and manage multiple webhook profiles for different Discord servers or channels. 👤
    * **URL Sharing:** Manually enter and share any URL with an optional description. 🔗✍️
    * **File Upload:** Drag and drop or select files to upload and send to Discord. Supports multiple file uploads. 📁⬆️
    * **Clipboard Sharing:** Paste text or images directly from your clipboard to send to Discord. 📋➡️
* **Customizable Messages:** Add optional descriptions or messages when sharing links, files, or clipboard content. ✍️
* **Notifications:** Receive confirmation notifications ✅ when content is successfully shared or if there are any errors ❌. 🔔
* **Username Customization:** Set a custom username for each webhook profile, making it easier to identify the sender in Discord. 🏷️

## Installation

1. **Download the extension files:** You can either download the provided code as a ZIP file 📦 or clone the repository if available.
2. **Open Chrome Extensions:** In your Chrome browser, navigate to `chrome://extensions/` or go to `Menu > More tools > Extensions`. 🧩
3. **Enable Developer Mode:** In the top right corner of the Extensions page, toggle the "Developer mode" switch to ON. 🧑‍💻
4. **Load unpacked:** Click the "Load unpacked" button in the top left corner. 📂
5. **Select the extension directory:**  Browse to the directory where you extracted the extension files and select the folder containing `manifest.json`. 🎯
6. The **Discord Webhook Sender** extension should now be installed and visible on your Chrome Extensions page. ✅

## How to Use

1. **Setup Webhook Profiles:** 🛠️
    * Click the extension icon in your Chrome toolbar to open the popup. 🖱️
    * By default, you'll start with the "Add New Profile" option selected.
    * Enter a **Profile Name** (optional, a random name will be generated if left blank). 📝
    * Paste your **Discord Webhook URL** into the "Webhook URL" field.  You can create a webhook in your Discord server settings under "Integrations". 🌐🔑
    * Enter a **Username** (optional) to customize the name that appears in Discord when sending messages. 👤🏷️
    * Click "Save Settings". ✅
    * You can create multiple profiles for different webhooks by selecting "Add New Profile" from the dropdown. ➕
    * To edit or delete an existing profile, select it from the dropdown and use the "Edit" ✏️ or "Delete" 🗑️ buttons.

2. **Share Links via Context Menu:** 🔗➡️
    * Right-click on any link on a webpage. 🖱️
    * Select "Share Link to Discord" from the context menu. ➡️
    * The link will be sent to your currently selected webhook profile in Discord. 💬

3. **Share Pages via Context Menu:** 🌐➡️
    * Right-click anywhere on a webpage. 🖱️
    * Select "Share Link to Discord" from the context menu. ➡️
    * The URL of the current page will be sent to your selected webhook profile. 💬

4. **Share Images via Context Menu:** 🖼️➡️
    * Right-click on any image on a webpage. 🖱️
    * Select "Share Image to Discord" from the context menu. ➡️
    * The image will be uploaded and sent to your selected webhook profile. 💬

5. **Share via Popup Interface:** 📤
    * Click the extension icon in your Chrome toolbar. 🖱️
    * **Share Link:** Select the "Share Link" option, enter a URL and optional description, and click "Share Link". 🔗✍️
    * **Upload Files:** Select the "Upload Files" option, drag and drop files into the designated area or click to select files. Add an optional message and click "Upload Files". 📁⬆️✍️
    * **Share Clipboard:** Select the "Clipboard" option, click "Click here to paste from clipboard". The extension will attempt to read text or image data from your clipboard.  Preview the content, add an optional description and click "Share Clipboard Content". 📋➡️👁️✍️

## Permissions

This extension requires the following permissions: 🔐

* **`storage`:** To store your webhook profiles and settings locally in your browser. 🗄️
* **`contextMenus`:** To add the "Share to Discord" options to the right-click context menu. 🖱️
* **`activeTab`:**  Although not explicitly used in the provided code, this is often included for extensions that might need to access the active tab's URL or content in future updates. 🌐
* **`clipboardWrite`:**  Potentially for future features where the extension might copy information to the clipboard (currently not used). 📋➡️
* **`clipboardRead`:** To read content from your clipboard for the "Clipboard Share" feature. 📋⬅️
* **`notifications`:** To display success and error notifications when sharing content. 🔔

## Support

If you encounter any issues or have suggestions for improvements, please feel free to open an issue on the project's repository (if available) or contact the developer. 🙏

## Disclaimer

This extension is provided as-is and is intended for personal use. Please use webhooks responsibly and respect Discord's Terms of Service and Community Guidelines. ⚠️
