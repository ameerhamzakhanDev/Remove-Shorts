# 🚫 Remove YouTube Shorts (Chrome & Brave Extension)

A lightweight, blazing-fast, and privacy-friendly browser extension that completely removes YouTube Shorts from your browsing experience. 

Stop the doom-scrolling! This extension hides Shorts from the homepage, search results, subscriptions, and sidebars. If you accidentally click a direct Shorts link, it forces the video to open in the **standard, normal YouTube video player**.

## ✨ Features

- **Nukes the Shorts Shelf:** Completely hides Shorts from the Homepage, Subscriptions, and Search results.
- **Cleans Video Grids:** Removes individual Shorts videos that are mixed into standard video feeds.
- **Hides Navigation Buttons:** Removes the "Shorts" button from the left navigation menus.
- **Cleans Channel Pages:** Hides the "Shorts" tab on YouTube Channel pages.
- **Smart Redirect:** Automatically intercepts direct `/shorts/` URLs and redirects them to the classic YouTube video player (`/watch?v=`).
- **Zero Tracking:** No data collection, no background analytics, and no external server requests. 100% private.

## 📂 File Structure

```text
Remove-Shorts/
 ├── manifest.json   # Extension configuration
 ├── hide.css        # CSS to hide Shorts UI elements
 ├── content.js      # JS script for the URL redirect logic
 ├── icon.png        # Extension icon (128x128)
 └── README.md       # This documentation file
