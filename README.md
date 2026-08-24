# PDF or Image to Word

A browser-only converter that supports:

- PDF text to Word, preserving the PDF text layer as provided
- Scanned PDF pages to editable text with OCR
- Image to editable text with OCR
- Original image embedded in Word

## Publish online 24/7

This is a static website. Upload the contents of this folder to any static host:

- **Netlify:** Open Netlify Drop and drag this folder into the page.
- **Vercel:** Import the folder as a static project; use `index.html` as the entry page.
- **GitHub Pages:** Create a repository, upload `index.html`, then enable Pages from the repository's main branch.

No server or database is required. Conversion runs in the visitor's browser. The app loads PDF.js, docx, and Tesseract.js from public CDNs, so the deployed page needs internet access.
