# Snakes YouTube Remove Playlists and Mixes

Chrome extension that automatically removes:

- Playlists & playlist panels
- Mixes / Auto-generated radio
- Playlist parameters from URLs (`?list=`, `?index=`, `?start_radio=`)
- Annoying playlist sidebar on watch pages

## Features
- Automatically cleans video URLs (prevents playlist/mix redirection)
- Blocks clicks that lead to playlists or mixes
- Simple toggle switch in popup (Enabled / Disabled)
- Page auto-reloads when toggle state changes
- Stylish rusty metallic popup design with bronze glow
- Light code obfuscation on core scripts

## Installation (Developer Mode – sideload only)
1. Download or clone this repository
2. Open `chrome://extensions/` in Chrome
3. Enable **Developer mode** (top right)
4. Click **Load unpacked**
5. Select the folder containing the extension files

## VirusTotal Verification (latest ZIP – v1.102)
Scanned clean:  
[View full scan results → 0 detections expected](https://www.virustotal.com/gui/file/302bcf851f7068417c9bfa4f88ebc374db1fe234d4ce45b7e65bd8cf073688cc/detection)

**SHA-256 Hash:**  
`302bcf851f7068417c9bfa4f88ebc374db1fe234d4ce45b7e65bd8cf073688cc`

(Minor flags from obfuscation are false positives – no malicious code.)

Feedback, bug reports and suggestions are welcome!  
-<img src="Logo3.png" alt="Snakes Logo" width="24" height="24" style="vertical-align: middle; margin-right: 12px;">

**Note:** Currently sideload-only (not yet in Chrome Web Store).  
License: [MIT](LICENSE)
