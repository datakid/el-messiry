# Lawha

Arabic announcement designer. Choose a preset, edit the text on the page, and print it at the paper size shown.

## What it does

- Seven presets: private tutor, clinic, gym, shop or restaurant, event programme, course and prayer times. Each sets the labels for the title and the groups.
- Edits in place. Click any text to change it, add or remove groups and slots, and undo or redo.
- Contact lines for WhatsApp, phone, email, address, Instagram and website. Each line can also be shown as a QR code.
- One photo per design, resized to 400 px on its longer side.
- Paper size A4, A5 or Letter, portrait or landscape, with an ink saver and a mode that hides the editing controls. Text is scaled down to fit one page.
- Arabic or English interface, Arabic or Western digits, 24-hour or 12-hour time, and light, dark or automatic colour.

Ctrl+S saves, Ctrl+P prints and Esc closes a menu.

## What it does not do

- It produces one page. Longer content is scaled down to fit, not split across pages.
- It has no PDF export of its own. Printing uses the browser's print dialog.
- It has no accounts, sharing or cloud storage. The current design is kept in `localStorage` under `lawha:v2`, and Save writes a `lawha.json` file that Open reads back.

## Network and install

Loads qrcode-generator 1.4.4 from jsDelivr and the fonts from Google Fonts. It makes no other requests, and photos and designs are not uploaded. Not installable; no service worker.

## Built with

One HTML file, with no build step and no framework. qrcode-generator 1.4.4 draws the QR codes.

## Run locally

Open `index.html` in a browser, or serve the folder with any static file server.
