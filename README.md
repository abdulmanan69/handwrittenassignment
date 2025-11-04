# 📝 Handwritten Assignment Generator

[![GitHub Pages](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge&logo=github)](https://abdulmanan69.github.io/handwrittenassignment/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

Transform typed text into realistic handwritten assignments with this powerful, free online tool. Perfect for students, educators, and anyone who needs to create authentic-looking handwritten documents.

## ✨ Features

### 🎨 Rich Text Editing
- **28+ Handwriting Fonts** - Choose from a diverse collection of realistic English handwriting styles (cursive and normal)
- **Rich Text Editor** - Full-featured Quill.js editor with formatting options
- **Mathematical Formulas** - Built-in KaTeX support for mathematical expressions
- **Code Blocks** - Syntax highlighting with highlight.js

### ✏️ Drawing Tools
- **Built-in Canvas** - Draw diagrams, sketches, and illustrations
- **Shape Tools** - Lines, circles, rectangles
- **Color Picker** - Customize your drawing colors
- **Undo/Redo** - Full history management
- **Image Upload** - Add external images to your canvas
- **Flexible Positioning** - Add drawings inside or on top of paper

### 📄 Page Customization
- **Multiple Page Sizes** - A4, Letter, Legal, A5
- **Orientation Control** - Portrait or Landscape
- **Custom Margins** - Adjustable top and left margins with visual borders
- **Background Options**:
  - Custom background colors
  - Background images
  - Ruled lines (toggleable)
  - Shadow effects
- **Spacing Controls**:
  - Line spacing (input and paper)
  - Letter spacing
  - Word spacing

### 🎯 Typography Controls
- **Font Size** - Adjustable from 10px to 100px
- **Font Color** - Full color customization
- **Heading Fonts** - Separate font size for headings
- **Custom Font Upload** - Upload your own .ttf fonts
- **Math Font Toggle** - Use default math fonts when needed

### 📋 Multi-Page Management
- **Page Navigation** - Previous/Next page controls
- **Create New Pages** - Unlimited pages support
- **Delete Pages** - Remove unwanted pages
- **Page Counter** - Track your current page

### 💾 Export Options
- **Download Current Page** - Save individual pages as high-quality images
- **PDF Export** - Combine all pages into a single PDF document
- **Quality Control** - Adjustable image quality (0-10 scale)

### 🎛️ Advanced Features
- **Mini Toolbar** - Quick formatting for headings and margin text
- **Interactive Canvas** - Drag and resize elements with interact.js
- **Responsive Design** - Works on desktop and mobile devices
- **No Installation Required** - 100% browser-based

## 🚀 Quick Start

### Online Access
Visit the live demo: **[https://abdulmanan69.github.io/handwrittenassignment/](https://abdulmanan69.github.io/handwrittenassignment/)**

The main page automatically redirects to `/app/` where the application runs.

### Local Development

1. **Clone the repository**
```bash
git clone https://github.com/abdulmanan69/handwrittenassignment.git
cd handwrittenassignment
```

2. **Open in browser**
```bash
# Simply open app/index.html in your browser
# Or use a local server (recommended)
python -m http.server 8000
# Then visit: http://localhost:8000/app/
```

No build process or dependencies required! This is a pure HTML/CSS/JavaScript application.

## 📁 Project Structure

```
handwrittenassignment/
├── index.html              # SEO-optimized landing page (redirects to /app/)
├── app/
│   ├── index.html         # Main application
│   └── static/
│       ├── final.css      # Application styles
│       ├── final.js       # Application logic
│       ├── fonts/         # Handwriting font files
│       └── icons/         # UI icons
├── robots.txt             # SEO crawler instructions
├── sitemap.xml            # Search engine sitemap
└── README.md              # This file
```

## 🌐 SEO Features

This project is fully optimized for search engines:

- ✅ **Meta Tags** - Comprehensive title, description, and keywords
- ✅ **Open Graph** - Social media preview cards (Facebook, Twitter)
- ✅ **Schema.org** - Structured data for rich snippets
- ✅ **Robots.txt** - Proper crawler directives
- ✅ **Sitemap.xml** - Complete site structure
- ✅ **Canonical URLs** - Prevent duplicate content
- ✅ **Semantic HTML** - Proper heading hierarchy

## 🎓 Use Cases

- 📚 **Students** - Create assignments that look hand-written
- 👨‍🏫 **Teachers** - Generate practice worksheets
- 📝 **Note-taking** - Digital handwritten notes
- 🎨 **Design** - Mock up handwritten documents
- 📋 **Forms** - Create realistic filled forms

## 🛠️ Technologies Used

- **[Quill.js](https://quilljs.com/)** - Rich text editor
- **[KaTeX](https://katex.org/)** - Math formula rendering
- **[jsPDF](https://github.com/parallax/jsPDF)** - PDF generation
- **[html2canvas](https://html2canvas.hertzen.com/)** - HTML to image conversion
- **[interact.js](https://interactjs.io/)** - Drag and drop functionality
- **[highlight.js](https://highlightjs.org/)** - Code syntax highlighting
- **[html2pdf.js](https://github.com/eKoopmans/html2pdf.js)** - Advanced PDF export

## 🔧 Configuration

### GitHub Pages Deployment

1. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Deploy from branch
   - Branch: `main` / `(root)`
   - Save

2. **Update URLs** (if using custom domain)
   - Edit `index.html` - Update canonical and og:url
   - Edit `sitemap.xml` - Update domain
   - Edit `robots.txt` - Update sitemap URL

3. **Push changes**
```bash
git add .
git commit -m "Configure for GitHub Pages"
git push origin main
```

Your site will be live at: `https://[username].github.io/[repository]/`

## 📝 Usage Guide

### Basic Workflow

1. **Enter Text** - Type or paste your content in the rich text editor
2. **Choose Font** - Select from 28+ handwriting styles
3. **Customize** - Adjust font size, color, spacing, and margins
4. **Add Drawings** - Use the canvas to draw diagrams or upload images
5. **Format Pages** - Set paper size, orientation, and background
6. **Export** - Download as images or combine into PDF

### Pro Tips

- 🎯 Use the **mini toolbar** for quick heading formatting
- 📐 Toggle **left/top margins** to create realistic notebook paper
- 🎨 Add **background images** for branded paper templates
- 📊 Use **shadow effects** for realistic paper appearance
- 🔢 Enable **math font** for complex mathematical expressions
- 💾 Adjust **image quality** based on file size needs

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues and pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Abdul Manan**
- GitHub: [@abdulmanan69](https://github.com/abdulmanan69)
- Project Link: [https://github.com/abdulmanan69/handwrittenassignment](https://github.com/abdulmanan69/handwrittenassignment)

---

<div align="center">

**Created with ❤️ — dedicated to Werda**

If you find this project helpful, please consider giving it a ⭐!

</div>
