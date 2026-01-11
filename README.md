# 📄 DocCompare

**AI-Powered Document Comparison with Live Character-Level Diff**

A modern, browser-based tool for comparing text documents with real-time character-level difference highlighting. Features OCR support for extracting text from images and PDFs using OpenAI's GPT-4 Vision.

![DocCompare Screenshot](https://img.shields.io/badge/Status-Active-success) ![License](https://img.shields.io/badge/License-MIT-blue)

## ✨ Features

- **🔴 Live Character-Level Diff** - Highlights individual character differences as you type (like Mergely)
- **📁 OCR Document Upload** - Extract text from PDFs and images (JPG, PNG, WebP) using GPT-4 Vision
- **✍️ Handwriting Recognition** - Accurately reads handwritten text from uploaded documents
- **🎨 5 Color Themes** - Dark, Light, Ocean, Forest, and Sunset themes
- **📏 Line Numbers** - With highlighting for changed lines
- **🔗 Center Gutter** - Visual connections showing differences between documents
- **🔄 Synced Scrolling** - Both editors scroll together
- **⚡ Real-time Updates** - Diff updates instantly as you type

## 🚀 Quick Start

### Option 1: Open Directly
Simply open `index.html` in your browser - no build process required!

### Option 2: Use a Local Server
```bash
# Using Python
python -m http.server 8080

# Using Node.js
npx http-server -p 8080

# Using PHP
php -S localhost:8080
```

Then open http://localhost:8080

## 📖 Usage

### Text Comparison
1. Type or paste text in **Document 1** (left panel)
2. Type or paste text in **Document 2** (right panel)
3. Differences highlight automatically in real-time!

### Document Upload (OCR)
1. Click **"Upload Left"** or **"Upload Right"** in the toolbar
2. Drop a file (PDF, JPG, PNG, WebP) or click to browse
3. Enter your OpenAI API key (required for OCR)
4. Text will be extracted and compared automatically

## 🎨 Themes

Click the theme buttons in the header to switch:

| Theme | Description |
|-------|-------------|
| 🌑 **Dark** | Purple/Cyan on black (default) |
| ☀️ **Light** | Clean white with purple accents |
| 🌊 **Ocean** | Deep blue with cyan highlights |
| 🌲 **Forest** | Dark green with lime accents |
| 🌅 **Sunset** | Warm red/orange tones |

## 🔑 API Key

For OCR functionality, you need an OpenAI API key:

1. Go to [platform.openai.com](https://platform.openai.com)
2. Create an account and add credits
3. Generate an API key
4. Paste it in the toolbar

**Note:** The API key is only used client-side and is never sent to any server except OpenAI.

## 🛠️ Tech Stack

- **Pure HTML/CSS/JavaScript** - No build process required
- **PDF.js** - PDF rendering and page extraction
- **OpenAI GPT-4 Vision** - OCR and handwriting recognition
- **LCS Algorithm** - Character-level diff computation

## 📁 Project Structure

```
DocCompare/
├── index.html    # Complete application (single file)
└── README.md     # This file
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

MIT License - feel free to use this project for personal or commercial purposes.

## 🙏 Acknowledgments

- Inspired by [Mergely](https://mergely.com) for the diff interface
- Uses [PDF.js](https://mozilla.github.io/pdf.js/) by Mozilla
- OCR powered by [OpenAI GPT-4 Vision](https://openai.com)

---

Made with ❤️ by [sahil-lab](https://github.com/sahil-lab)
