# file2txt
One single-file JavaScript app that converts PDF, EPUB, and DOCX files to TXT format. 
# 📄 File to TXT Converter

A beautiful, browser-based application that converts PDF, EPUB, and DOCX files to plain text format. No installation required - just open in your browser and start converting!

## ✨ Features

- **🖱️ Drag & Drop Support** - Simply drag files onto the upload area
- **📱 Responsive Design** - Works on desktop, tablet, and mobile devices
- **⚡ Client-Side Processing** - No server required, everything runs in your browser
- **🔄 Real-Time Progress** - Visual feedback during conversion
- **📥 Automatic Download** - Converted files download automatically
- **🎨 Modern UI** - Beautiful, intuitive interface with smooth animations
- **🔒 Privacy Focused** - Files never leave your device

## 📋 Supported File Formats

| Format | Extension | Description |
|--------|-----------|-------------|
| PDF | `.pdf` | Portable Document Format |
| EPUB | `.epub` | Electronic Publication (eBooks) |
| DOCX | `.docx` | Microsoft Word Document |

## 🚀 Quick Start

1. **Download the app**: Save the HTML file to your computer
2. **Open in browser**: Double-click the file or open with any modern web browser
3. **Select a file**: Click the upload area or drag & drop your file
4. **Convert**: Click "Convert to TXT" button
5. **Download**: Your converted text file will automatically download

## 💻 Browser Requirements

- **Chrome** 60+ ✅
- **Firefox** 55+ ✅
- **Safari** 11+ ✅
- **Edge** 79+ ✅

*Note: Internet connection required for initial load to fetch CDN libraries*

## 🛠️ How It Works

The application uses several powerful JavaScript libraries loaded from CDN:

- **[PDF.js](https://mozilla.github.io/pdf.js/)** - Mozilla's PDF rendering engine for extracting text from PDF files
- **[Mammoth.js](https://github.com/mwilliamson/mammoth.js)** - Converts DOCX files to HTML/text
- **[JSZip](https://stuk.github.io/jszip/)** - Handles EPUB files (which are ZIP archives containing HTML)

###
