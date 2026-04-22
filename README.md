# Band Eligibility Highlighter

Upload the weekly student ineligibility PDF, enter your band roster, and download a highlighted copy showing which of your students appear on the list.

## Usage

1. Open `index.html` in a browser
2. Upload the ineligibility PDF
3. Enter student names, one per line (e.g. `Smith, John`)
4. Choose a highlight color
5. Click **Highlight My Students** and download the result

**Flexible matching** is on by default — it finds a name even when it is split across columns in the PDF.

## Privacy

All processing happens locally in your browser. The PDF and student names are never uploaded to a server or sent over the internet. The page works fully offline once loaded.

## Libraries

Bundled in `libraries/` — no internet connection or package manager required.

| Library | Purpose | License |
|---|---|---|
| [PDF.js](https://github.com/mozilla/pdf.js) | PDF text extraction | Apache 2.0 |
| [pdf-lib](https://github.com/Hopding/pdf-lib) | Drawing highlight annotations | Apache 2.0 |

See [LICENSE](LICENSE) for full license text.