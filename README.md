# TronClass-PDF-Downloader

## Example only for TKU iClass

You can modify the .slice(`num`) in content_script.js

```javascript=
window.open(decodeURIComponent(document.getElementById('pdf-viewer').src.slice(51)));
```

## How to use

### Chrome

1. Goto [chrome://extensions/](chrome://extensions/)
2. Open developer mode
3. Load unpacked extensions
4. Select directory folder

### Firefox

1. Goto [about:debugging#addons](about:debugging#addons)
2. Load Temporary Add-on...
3. Select manifest.json

## Directory structure

```bash=
.
├── README.md
├── content_script.js
├── event.js
├── icon128.png
├── icon16.png
├── icon32.png
├── icon48.png
└── manifest.json

0 directories, 8 files
```
