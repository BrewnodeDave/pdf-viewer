# 📄 PDF Viewer Web App

A modern, responsive single-page web application for viewing PDF documents directly in the browser.

![PDF Viewer](https://img.shields.io/badge/PDF-Viewer-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![PDF.js](https://img.shields.io/badge/PDF.js-3.11.174-red.svg)

## 🍺 Features

### **Core Functionality**
- ✅ **High-Quality PDF Rendering** using PDF.js library
- ✅ **File Upload** via click or drag-and-drop
- ✅ **Page Navigation** with previous/next controls
- ✅ **Zoom Controls** for detailed viewing
- ✅ **Responsive Design** for desktop and mobile
- ✅ **Keyboard Shortcuts** for power users

### **User Experience**
- 🎨 **Modern UI** with glass-morphism effects
- 📱 **Mobile Responsive** touch-friendly interface
- 🔄 **Loading States** with visual feedback
- ❌ **Error Handling** for invalid files
- 🎯 **BrewNode Themed** to match your brewery branding

## 🚀 Quick Start

### **1. Open the App**
```bash
# Simply open in any modern web browser
open index.html

# Or serve it locally (if you have a web server)
python3 -m http.server 8000
# Then visit: http://localhost:8000
```

### **2. Load a PDF**
- **Method 1**: Click the "📁 Choose PDF File" button
- **Method 2**: Drag and drop any PDF file onto the page

### **3. Navigate & Control**
- Use **⬅️ ➡️** buttons to navigate pages
- Use **🔍➖ 🔍➕** buttons to zoom in/out
- View current **page info** in the header

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `← →` | Navigate pages |
| `Ctrl + +` | Zoom in |
| `Ctrl + -` | Zoom out |

## 🛠️ Technical Details

### **Dependencies**
- **PDF.js** (v3.11.174) - Loaded from CDN
- **Modern Browser** with Canvas support

### **Browser Support**
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

### **File Support**
- ✅ PDF files (.pdf)
- ❌ Other formats not supported

## 📁 Project Structure

```
pdf-viewer/
├── index.html          # Main application file
├── README.md           # This documentation
└── screenshots/        # (Optional) App screenshots
```

## 🎯 Use Cases

Perfect for viewing:
- 📋 **Technical Documentation** (BrewNode manuals, API docs)
- 📊 **Reports & Analytics** (Brewing reports, performance data)
- 📖 **User Manuals** (Hardware guides, setup instructions)
- 📑 **Presentations** (Training materials, specifications)
- 📄 **General PDFs** (Any PDF document viewing)

## 🔧 Customization

### **Theming**
The app uses CSS custom properties for easy theming:
```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --glass-bg: rgba(255, 255, 255, 0.1);
  --text-color: white;
}
```

### **Features to Add**
- 🔍 Search within PDF
- 📑 Bookmarks/Thumbnails
- 🖨️ Print functionality
- 📱 Full-screen mode
- 💾 Recent files list

## 🚀 Deployment Options

### **Static Hosting**
Deploy to any static hosting service:
- **GitHub Pages**: Push to a `gh-pages` branch
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your repository
- **AWS S3**: Upload as static website

### **Local Server**
```bash
# Python 3
python3 -m http.server 8000

# Node.js (if you have http-server installed)
npx http-server

# PHP
php -S localhost:8000
```

## 🔒 Security & Privacy

- ✅ **Client-Side Only**: No files uploaded to servers
- ✅ **Local Processing**: PDFs processed entirely in browser
- ✅ **No Tracking**: No analytics or external requests
- ✅ **HTTPS Ready**: Works on secure connections

## 🐛 Troubleshooting

### **PDF Won't Load**
- Ensure file is a valid PDF
- Check file size (very large PDFs may be slow)
- Try a different PDF file

### **Slow Performance**
- Large PDFs may take time to render
- Try zooming out for better performance
- Close other browser tabs to free memory

### **Mobile Issues**
- Use landscape orientation for better viewing
- Pinch-to-zoom is disabled (use app controls)
- Some complex PDFs may render slowly on mobile

## 📝 License

Licensed under the **Beerware License** 🍺

**Made with 🍺 by the BrewNode Team**
