# 🚀 Facebook Enhancer v3.32 – by Eliminater74

Take back control of your Facebook feed. This is a lightweight, powerful, and *smart* script to hide distractions, block unwanted content, and customize your experience — all from a simple, draggable floating menu.

This version features a **major performance overhaul**, using an efficient observer to keep your feed clean without slowing down your browser.

---

## 🧰 Core Features

### 🛑 Hide Annoyances
* **Reels:** Aggressive, multi-method blocking to remove all Reels and "short videos" modules.
* **Stories:** Hide the Stories bar.
* **"People You May Know":** Remove PYMK suggestions.
* **Sponsored & Suggested:** Block "Sponsored" and "Suggested for you" posts in the feed.
* **Sidebar Clutter:** Hide Marketplace, Events, and "Your Shortcuts" from the left sidebar.
* **Right-Rail Ads:** Remove the entire right-side ad column.
* **Gaming:** Hide Facebook Gaming tabs and video sections.
* **Reels Tab:** Specific option to hide the "Reels" button in the sidebar (separate from feed reels).
* **Create Room:** Remove the "Create Room" / Video Chat banners.

### 🧠 Smart Feed & Video
* **Smarter "Force Most Recent":** Intelligently switches you to the "Most Recent" feed *only* on the main homepage. It won't fight you if you temporarily switch back to "Top Posts."
* **Disable Autoplay:** Puts a stop to videos playing automatically.
* **Mute Videos:** Automatically mutes all videos by default.
* **Pause Off-screen:** Pauses videos when they scroll out of view to save resources.

### 🛠️ Keyword & Link Tools
* **Keyword & Regex Filtering:** Block any post containing specific words, phrases, or complex regex patterns (e.g., “tiktok”, “politics”, `\b(crypto|giveaway)\b`).
* **Per-Post Quick Hide:** A new button on every post lets you "Hide posts like this," which then suggests keywords to add to your filter.
* **Unwrap Tracking Links:** Automatically cleans Facebook's "l.php" tracking links so you go straight to the real website.
* **Auto-Expand Comments:** Instantly expands "View more comments" and replies.

### 🎨 UI & Customization
* **Draggable Menu:** A floating ⚙️ Enhancer menu and settings panel that save their position.
* **Hiding Modes:**
    * **Soft Remove (default):** Hides items with `display:none`.
    * **Blur Mode:** Blurs hidden items so you can see what *would* be blocked.
    * **Review Mode:** Outlines hidden items with a red box for debugging.
* **"Show Hidden" Toggle:** A hotkey (`Alt+H`) and setting to temporarily reveal everything the script has hidden.
* **Custom CSS:** A built-in field to add your own custom CSS tweaks.
* **Import/Export:** Save and load your settings as a JSON file.
* **Custom Hotkeys:** Set your own hotkeys for toggling the panel, forcing "Most Recent," and showing hidden items.

---

## 📌 How to Use

1.  **Install this script** in Tampermonkey (Chrome, Edge, Brave) or Violentmonkey (Firefox).
2.  Visit **facebook.com** — the floating ⚙️ button will appear in the corner.
3.  Click the ⚙️ to open the settings panel.
4.  Enable/disable features by checking the boxes.
5.  **Save** to apply — changes take effect immediately or on reload.
6.  Drag the ⚙️ or panel anywhere — positions are saved automatically.

---

## 🔄 Latest Updates (v3.32)

* **New Features:** Added options to hide **Gaming**, **Create Room** banners, and the specific **Reels Sidebar Tab**.
* **Performance:** Further refined the page scanner to run smoother and faster.
* **Selectors:** Updated internal selectors for better stability.

### Recent Major Updates (v3.31)
* **Major Performance Overhaul!** The script no longer re-scans the whole page constantly. It now uses a highly efficient observer to catch *new* items as they appear. **This means a faster, smoother scroll with less lag.**
* **Smarter "Force Most Recent":** The sticky feed feature is now context-aware.
* **Full-Page Clean-up on Navigation:** The script now performs a full clean-up whenever you navigate (e.g., click the "Home" button) to catch anything missed.

---

## 🔮 Planned & Possible Future Features

* Pagelet blacklist (block by internal FB module IDs)
* Custom keyword auto-learn from your hides
* Optional ad-replacement with filler content or quotes
* Export/import keyword filter lists
* Theme presets for custom UI styles

---

**Created by:** Eliminater74
*(v3.31/3.32 refinements in collaboration with Gemini)*

💬 Feedback, suggestions, or contributions welcome. [Visit GitHub](https://github.com/Eliminater74/FacebookEnhancer) or comment on the GreasyFork page.
