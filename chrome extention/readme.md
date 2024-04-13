<h1>Chrome Extension for Drink Water Reminder (Every 10 Minutes)<\h1>
  <\br>
    This Chrome extension helps you stay hydrated by reminding you to drink water every 10 minutes. It utilizes a combination of HTML, CSS, and JavaScript to deliver a user-friendly notification.
    
  <h1>Technical Breakdown:<\h1>
    manifest.json: This file serves as the configuration center for your extension. It specifies details like the extension name, description, permissions, and the files it uses (HTML, CSS, and JS).
    index.html: This is the main HTML file that structures the content displayed in the notification popup. It includes elements like text message, icons, and buttons (if needed).
    styles.css: This file defines the visual style of the notification popup. You can customize fonts, colors, and layout using CSS properties.
    script.js: This JavaScript file is the heart of the reminder functionality. It utilizes the Chrome extension APIs to:
    Schedule an alarm to trigger a notification every 10 minutes.
    Create the notification content with the desired message (e.g., "Time for a sip of water!").
    Optionally, play a sound or vibrate the device on notification (requires additional permissions in manifest.json).

  <h1>How it Works:<\h1>
      Upon installing the extension, the background script (script.js) gets loaded.
      The script schedules an alarm to repeat every 10 minutes using the chrome.alarms.create API.
      When the alarm triggers, the script creates a notification popup using the chrome.notifications.create API.
      The notification displays the message defined in the HTML and styled using CSS.
      Clicking the notification (optional) could lead to a hydration tracking page or simply dismiss the reminder.

  **Benefits:**
    Simple and effective way to stay hydrated throughout the day.
    Customizable notification message using HTML.
    Easy to understand code structure for future modifications.

  **Future Enhancements:**
    Implement a tracking mechanism to monitor water intake.
    Allow users to adjust the reminder interval.
    Integrate with hydration tracking apps or wearables.

  **Getting Started:**
    Download and extract the extension files (manifest.json, index.html, styles.css, and script.js).
    Load the unpacked extension into Chrome by going to chrome://extensions/ and enabling "Developer mode". Then, click "Load unpacked" and select the extracted folder.
    That's it! The extension should be active and remind you to drink water every 10 minutes.
