# MyorkText

**MyorkText** is a lightweight, browser-based rich-text editor prototype by Two Plasma Studios. The current implementation is a single HTML file and can be opened locally in a modern browser.

> **Project status:** Prototype / work in progress. This repository currently contains a single-page editor rather than a packaged desktop application. Some browser editing commands may behave differently between browsers.

## Current features

- Turkish and English interface toggle
- Create a new document
- Open and save documents using the `.myorktxt` extension
- Rich-text editing through the browser's content-editable surface
- Font family and size controls
- Bold, italic and underline
- Normal text, Heading 1 and Heading 2 styles
- Left, center, right and justified alignment
- Text and highlight color controls
- Find and replace prompts
- Live word counter

## Run it

1. Clone or download this repository.
2. Open `program/myorktext.html` in a current desktop browser.
3. Use **New**, **Open** and **Save** from the toolbar.

No package installation or build step is required for the current HTML prototype.

## Important limitations

- The editor relies on browser editing APIs such as `document.execCommand`; support and formatting behavior can vary.
- Files are handled locally by the browser. There is no account system, cloud sync or online storage.
- The `.myorktxt` format currently stores editor HTML content; it is not yet a formally versioned document format.
- This project should be considered an early prototype, not a production word processor.

## Roadmap

- Improve document format and import/export reliability
- Add autosave and recovery
- Improve accessibility and keyboard shortcuts
- Add automated browser tests
- Package the editor for desktop use if needed

## Links

- **Studio website:** https://twoplasmastudios.github.io/
- **All studio projects:** https://twoplasmastudios.github.io/projects.html
- **Source code:** https://github.com/TwoPlasmaStudios/myorktext

---

Made by **Two Plasma Studios**.
