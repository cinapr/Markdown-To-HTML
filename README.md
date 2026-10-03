# MARKDOWN TO HTML
A simple, zero-setup browser tool that turns raw Markdown or text into polished technical documentation. 

I built this because copying code and documentation from a browser into clipboard usually strips out all the formatting, colors, and backgrounds. 
This tool fixes that by baking the CSS styles directly into your clipboard, meaning your documentation looks exactly the same in Word as it does on the screen.

## Features
- **Live Markdown Parsing:** Uses Marked.js to instantly build your documentation.
- **IDE-like Syntax Highlighting:** Uses Highlight.js (GitHub Dark theme) to colorize your code blocks.
- **MS Word Integration:** A custom copy script injects computed CSS inline, forcing Word to keep your dark code backgrounds and font colors.
- **PDF Export:** Clean print media queries that strip away the UI so you can save a perfect PDF.
- **Smart Code Wrapping:** Long lines of code wrap automatically so nothing gets cut off in PDFs or Word docs.

## How to use
There is no build process, no npm install, and no backend. 

1. Download or clone this repository.
2. Open `index.html` in any modern web browser.
3. Paste your Markdown into the input box and click **Format Document**.
4. Use the **Copy for MS Word** or **Save as PDF** buttons to export your work.

## Dependencies
This tool relies on a couple of great open-source libraries via CDN:
- [Marked.js](https://marked.js.org/) for parsing Markdown.
- [Highlight.js](https://highlightjs.org/) for syntax highlighting.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
