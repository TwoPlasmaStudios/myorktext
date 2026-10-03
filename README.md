# MyorkText

**MyorkText** is an open-source, browser-based document editor prototype from Two Plasma Studios. The long-term goal is to build an Office-style editor that can work with text, tables, images, code snippets and common document export formats.

## Current features

- Turkish and English interface
- Rich text editing, headings, font family/size, colors and alignment
- Lists, links, tables and local image insertion
- Code blocks with language labels for JavaScript, TypeScript, Python, HTML, CSS, Java, Dart, React/JSX, JSON, SQL, C++, C#, Go, Rust, Kotlin and Swift
- Browser-local draft autosave and recovery
- Keyboard shortcuts: `Ctrl/Cmd+S` save, `Ctrl/Cmd+O` open, `Ctrl/Cmd+N` new
- Export to HTML, PDF, PNG, JPEG and DOCX
- Local `.myorktxt` file workflow

## Run

Open `program/myorktext.html` in a modern desktop browser. PDF, image and DOCX exports use browser-loaded libraries, so those features require an internet connection unless the libraries are bundled locally.

## Current limitations

- **Prototype:** this is not yet a complete replacement for Microsoft Word or LibreOffice.
- DOCX export currently focuses on common paragraphs, headings and some embedded images; complex page layouts, tracked changes, footnotes, advanced tables and full style fidelity are not guaranteed.
- PDF and image exports render the current editor content; very long documents may need pagination and layout improvements.
- Code blocks are stored as document content. The editor does not execute arbitrary code inside the document.
- Draft autosave uses browser local storage on the current browser/profile; it is not cloud sync.
- Some formatting commands depend on browser editing APIs and may vary between browsers.

## Roadmap

- Add a structured, versioned Myork document format and robust import validation
- Improve DOCX round-trip compatibility and pagination
- Add a sandboxed HTML/JavaScript preview for code blocks
- Add more export tests and accessibility checks
- Package desktop builds after core workflows are stable

## Links

- **Studio:** https://twoplasmastudios.github.io/
- **All projects:** https://twoplasmastudios.github.io/projects.html
- **Source:** https://github.com/TwoPlasmaStudios/myorktext

---

Made by **Two Plasma Studios**.
