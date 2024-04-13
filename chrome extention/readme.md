## Chrome Extension for Drink Water Reminder (Every 10 Minutes)

This Chrome extension helps you stay hydrated by reminding you to drink water every 10 minutes. It utilizes a combination of HTML, CSS, and JavaScript to deliver a user-friendly notification.

**Features:**

* Simple and effective hydration reminders
* Customizable notification message (using HTML)
* Easy to understand code structure for future modifications

**Project Files:**

* **manifest.json:** Configuration file for the extension (name, description, permissions, references other files).
* **background.js:** JavaScript file handling reminder functionality (schedules alarms using Chrome extension APIs).
* **popup.html:** Main HTML file for the notification popup content (message, icons, buttons - optional).
* **popup.js:** JavaScript file for the notification popup (complements popup.html, might handle functionalities like displaying content or button clicks).
* **readme.md:** This file (you're reading it now!) explains the extension's purpose, features, and usage.

**How it Works:**

1. **manifest.json** defines the extension's configuration and references the other files.
2. **background.js** runs in the background, scheduling alarms using the Chrome extension API to trigger every 10 minutes.
3. When an alarm triggers, **background.js** might display a notification popup using the Chrome extension API.
4. The notification popup content is defined in **popup.html** (message, styling with CSS - not included here).
5. **popup.js** (if used) might handle functionalities specific to the popup itself.

**Getting Started:**

1. Download the extension files (manifest.json, background.js, popup.html, popup.js).
2. Load the unpacked extension into Chrome:
    * Go to `chrome://extensions/`.
    * Enable "Developer mode".
    * Click "Load unpacked" and select the folder containing the extension files.
3. The extension is now active and will remind you to drink water every 10 minutes.

**Note:**

* The included image files (`alarm.jpg` and `logo.png`) might be for visual aspects not essential for the core reminder functionality. Their usage depends on your specific implementation.
* This is a basic example. You can customize it further based on your needs. Refer to the Chrome extension development documentation for more advanced functionalities: [https://developer.chrome.com/docs/extensions](https://developer.chrome.com/docs/extensions)
