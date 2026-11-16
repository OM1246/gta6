# GTA VI Countdown — 9:16 Vertical Stream Edition 📱🎮

A cinematic, modern, high-performance standalone countdown landing page for **Grand Theft Auto VI**, scheduled for worldwide release on **19 November 2026, 00:00 (Local Time)**.

Custom-engineered for **Ultra Gaming Live** specifically for **9:16 vertical streams** (YouTube Shorts Live, TikTok Live, Instagram Live, and OBS Vertical).

---

## 📱 9:16 Vertical Stream Optimizations

1. **2x2 High-Impact Countdown Grid:**
   - Stacked into a **2x2 layout** (`[DAYS | HOURS]` on top, `[MINUTES | SECONDS]` below) with huge, glowing neon digits.
   - Designed to be easily readable on mobile phone screens and compact live stream feeds.

2. **Mobile Live Chat Safe Zone:**
   - Thoughtfully padded and proportioned so that YouTube Shorts Live / TikTok bottom chat overlays and comment boxes do **not** block the countdown numbers.
   - Includes a toggleable **Safe Zone Guide** (click `💬 Safe Zone` or press `G`) to preview where mobile comments float.

3. **Livestreamer Controls & Hotkeys:**
   - **`H` (Clean UI):** Hides buttons and footer links for an ultra-clean broadcast overlay in OBS.
   - **`B` (Frame Toggle):** Toggles between a phone bezel frame (great for previewing on a 16:9 desktop monitor) and borderless full-bleed mode.
   - **`G` (Safe Zone):** Toggles chat overlay guides.
   - **`Left / Right Arrow` or `Spacebar`:** Manually skip between background slideshow images.
   - **`🔊 Audio`:** Built-in ambient 80s Miami synthwave pad sound generator using zero-dependency Web Audio API.

4. **Cinematic 5-Second Background Slideshow:**
   - Automatically crossfades every 5 seconds through high-res artworks in the `images/` folder.
   - Vertical Ken Burns pan & zoom (`scale(1.0)` to `scale(1.09)`).
   - High-contrast dark vignette overlay ensuring maximum legibility of the countdown.

---

## 🎥 OBS Studio / Streamlabs Setup (9:16 Vertical)

1. In OBS, set your canvas to **1080 x 1920** (or use the OBS Vertical plugin / Aitum Vertical).
2. Add a new **Browser Source**:
   - **URL / Path:** `file:///c:/Users/Om/Documents/gta6/index.html`
   - **Width:** `1080`
   - **Height:** `1920`
3. Optional: Press **`H`** inside the browser window or interact with the source to activate **Clean Mode**.

---

**Ultra Gaming Live** • Made for GTA VI fans
