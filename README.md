# Cnv-Mu File Studio ⚡

> **Deterministic, 100% Offline Document & PDF Utility Suite with Liquid Glass UI**

A powerful, client-side document processing web app built with zero server dependencies. All file compressions, conversions, and manipulations run directly inside your browser memory using WebAssembly, HTML5 Canvas, PDF.js, PDF-Lib, SheetJS, and JSZip.

---

## 🌟 Key Features

- **Strict Target Compression**: Compress PDFs, JPGs, and PNGs to strict portal thresholds ($\le 1\text{ MB}$, $\le 2\text{ MB}$, $\le 3\text{ MB}$, $\le 500\text{ KB}$, or Custom) with auto-deskew and contrast optimization.
- **Accurate PDF to Excel (`.xlsx`)**: Coordinate-based row and column grid extraction with automatic dynamic cell widths (`!cols`), preserving tables without data mangling.
- **Accurate PDF to Word (`.docx`)**: Paragraph-level coordinate clustering and page demarcation rendered into valid Office OpenXML (`.docx`) via JSZip.
- **PDF Grayscale (CPNS & BKN Portal Ready)**: Pixel-level 8-bit ITU-R BT.601 monochrome conversion, cutting file weight by up to $\approx 75\%$ to satisfy strict government portal upload criteria.
- **Excel to PDF (`.pdf`)**: Formats `.xlsx` / `.csv` sheets into printable, neatly proportioned PDF tables.
- **20+ Document Utilities**: Merge, Split, Rotate, Watermark, Password Protect, Unlock, Page Numbers, OCR Text Extraction, PDF to Markdown, Crop Margins, and Selective Page Removal.
- **Tactile Audio Feedback**: Zero-latency synthesized Web Audio synthesizer for punchy tactile clicks, mode toggles, and completion chimes.
- **Privacy & Security First**: Zero cloud egress, zero third-party telemetry, zero server-side storage. Your files never leave your device.

---

## 🚀 Live Demo & Hosting

This app is hosted directly on **GitHub Pages**:
- **Live URL**: [https://darussaalam.github.io/](https://darussaalam.github.io/) *(or your custom repository subpath)*

---

## 🛠️ Tech Stack

- **Client Runtime**: Pure Vanilla HTML5, Modern ECMAScript (ES2022), CSS3 Liquid Glass UI
- **PDF Parsing & Rendering**: PDF.js (`pdfjs-dist`)
- **PDF Generation & Manipulation**: PDF-Lib (`pdf-lib`)
- **Spreadsheet Processing**: SheetJS (`xlsx.full.min.js`)
- **Document Packaging**: JSZip
- **Icons**: Lucide Icons
- **Audio**: Web Audio API (Synthesized Real-time DSP)

---

## 👨‍💻 Creator & Architect

Developed by **ds-xinn** ([@darussaalam](https://github.com/darussaalam)).

Distributed under the MIT License.
