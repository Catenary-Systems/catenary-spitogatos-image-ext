# SPITOGATOS Image Extractor

Install locally in Chrome/Chromium:

1. Open `chrome://extensions` and enable "Developer mode".
2. Click "Load unpacked" and select the folder `spitogatos-extractor` inside this repository.
3. Visit a page that may contain an element with class `photoSlider__slide hooper-slide`.
4. Click the extension icon in the toolbar — the extracted content will open in a new tab.

Notes:
- The extractor grabs the element's outerHTML; page styles from the original site may not be included.
- If no element is found, a message tab will be opened.
