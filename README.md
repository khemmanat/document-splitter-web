# ✨ PDF Page Splitter - Glassmorphism Edition

A modern, elegant PDF page splitting tool built with cutting-edge glassmorphism design principles. Split your PDF documents by selecting specific pages or page ranges with a stunning visual interface.

![PDF Splitter Preview](https://img.shields.io/badge/Design-Glassmorphism-blueviolet?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Browser Support](https://img.shields.io/badge/Browser-Modern%20Browsers-orange?style=for-the-badge)

## 🌟 Features

### 📄 Core Functionality
- **Single Page Extraction**: Extract individual pages (e.g., page 1)
- **Range Selection**: Extract page ranges (e.g., pages 2-5)
- **Multiple Selections**: Combine single pages and ranges (e.g., 1,3,5-7,10)
- **Custom Naming**: Optional custom filename for output files
- **Auto-naming**: Intelligent filename generation based on page selection

### 🎨 Design Features
- **Glassmorphism UI**: Modern frosted glass aesthetic with backdrop blur effects
- **Animated Background**: Dynamic gradient background with floating glass orbs
- **Interactive Elements**: Smooth hover effects and micro-animations
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Accessibility**: Proper contrast ratios and semantic markup

### 💫 Advanced Visual Effects
- **Dynamic Gradients**: Continuously shifting background colors
- **Floating Orbs**: Animated glass elements that drift across the screen
- **Shimmer Effects**: Subtle light animations on interactive elements
- **Glass Morphism**: Semi-transparent elements with realistic blur effects
- **Premium Animations**: Smooth transitions with cubic-bezier easing

## 🚀 Quick Start

### Installation

1. **Clone or Download**
   ```bash
   git clone https://github.com/khemmanat/document-splitter-web.git
   cd pdf-splitter-glassmorphism
   ```

2. **Open in Browser**
   - Simply open `index.html` in any modern web browser
   - No build process or dependencies required
   - Works offline after initial load

### Usage

1. **Upload PDF**: Drag and drop a PDF file or click to browse
2. **Select Pages**: Enter page numbers or ranges in the input field
3. **Configure Output**: Optionally set a custom filename
4. **Split**: Click the "Split PDF" button to process and download

## 📖 Page Selection Syntax

| Input | Description | Example |
|-------|-------------|---------|
| `1` | Single page | Extracts page 1 only |
| `2-5` | Page range | Extracts pages 2, 3, 4, and 5 |
| `1,3,5` | Multiple pages | Extracts pages 1, 3, and 5 |
| `1,3-5,8` | Mixed selection | Extracts pages 1, 3, 4, 5, and 8 |
| `1-3,7-10` | Multiple ranges | Extracts pages 1-3 and 7-10 |

## 🛠️ Technical Specifications

### Browser Compatibility
- **Chrome**: 88+ (recommended)
- **Firefox**: 85+
- **Safari**: 14+
- **Edge**: 88+

### Dependencies
- **PDF-lib**: 1.17.1 (loaded via CDN)
- **No frameworks**: Pure HTML, CSS, and JavaScript
- **Font**: Inter from Google Fonts

### File Limitations
- **Maximum file size**: 50MB
- **Supported format**: PDF only
- **Processing**: Client-side (no server upload required)

## 🎨 Design System

### Color Palette
```css
Primary Gradient: linear-gradient(135deg, #667eea 0%, #764ba2 25%, #f093fb 50%, #f5576c 75%, #4facfe 100%)
Glass Effect: rgba(255, 255, 255, 0.1) with backdrop-filter: blur(20px)
Text Colors: White with various opacity levels (0.6-1.0)
Accent Colors: Success (#10b981), Error (#ef4444)
```

### Typography
```css
Font Family: 'Inter', sans-serif
Weights: 300, 400, 500, 600, 700, 800
Responsive Scaling: 2rem - 3.5rem for headings
```

### Animation Principles
- **Duration**: 0.3s - 0.6s for interactions
- **Easing**: cubic-bezier(0.175, 0.885, 0.32, 1.275)
- **Transforms**: translateY, scale, rotate for depth
- **Performance**: Hardware-accelerated properties only

## 📱 Responsive Breakpoints

| Device | Breakpoint | Adjustments |
|--------|------------|-------------|
| Desktop | 1024px+ | Full feature set, large typography |
| Tablet | 768px - 1023px | Adjusted spacing, medium typography |
| Mobile | 480px - 767px | Stacked layout, touch-optimized |
| Small Mobile | < 480px | Compact design, essential features |

## 🔧 Customization

### Modifying Colors
```css
/* Change primary gradient */
body {
    background: linear-gradient(135deg, #your-colors-here);
}

/* Adjust glass transparency */
.glass-card {
    background: rgba(255, 255, 255, 0.1); /* Adjust alpha value */
}
```

### Adding Custom Animations
```css
/* Example: Custom hover effect */
.custom-element:hover {
    transform: translateY(-5px) scale(1.02);
    transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
}
```

## 🔒 Security & Privacy

- **Client-side Processing**: All PDF processing happens in your browser
- **No Data Upload**: Files never leave your device
- **Privacy First**: No tracking, analytics, or data collection
- **Secure**: Uses modern browser APIs with proper error handling

## 🌐 Browser Support Details

### Required Features
- **File API**: For reading uploaded files
- **Blob API**: For generating download files
- **CSS backdrop-filter**: For glassmorphism effects
- **CSS Grid & Flexbox**: For responsive layouts
- **ES6+ JavaScript**: For modern syntax and features

### Fallbacks
- Graceful degradation for older browsers
- Alternative styling for unsupported CSS features
- Progressive enhancement approach

## 🚀 Performance Optimization

### Loading Performance
- **Critical CSS**: Inlined for immediate rendering
- **CDN Resources**: PDF-lib loaded from CloudFlare CDN
- **Optimized Assets**: Minimal external dependencies

### Runtime Performance
- **Hardware Acceleration**: CSS transforms use GPU
- **Efficient Animations**: RequestAnimationFrame for smooth 60fps
- **Memory Management**: Proper cleanup of PDF documents
- **Debounced Events**: Optimized drag/drop handling

## 🐛 Troubleshooting

### Common Issues

**PDF won't load**
- Ensure file is a valid PDF (not corrupted)
- Check file size is under 50MB
- Try a different PDF file to isolate the issue

**Page selection errors**
- Verify page numbers exist in the document
- Check syntax: use commas for separation, hyphens for ranges
- Ensure no spaces around numbers (except after commas)

**Download doesn't start**
- Check browser's download permissions
- Disable popup blockers for this site
- Try in an incognito/private window

**Visual effects not working**
- Update to a modern browser version
- Check if hardware acceleration is enabled
- Ensure browser supports backdrop-filter CSS property

## 📄 License

MIT License - feel free to use this project for personal or commercial purposes.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Report Bugs**: Use GitHub issues for bug reports
2. **Suggest Features**: Share ideas for new functionality
3. **Improve Design**: Suggest UI/UX enhancements
4. **Code Contributions**: Submit pull requests with improvements

### Development Guidelines
- Follow the existing code style
- Test across multiple browsers
- Maintain the glassmorphism design aesthetic
- Ensure mobile responsiveness
- Add comments for complex logic

## 🔮 Roadmap

### Planned Features
- [ ] **PDF Merging**: Combine multiple PDFs into one
- [ ] **Password Protection**: Add password to split PDFs
- [ ] **Batch Processing**: Split multiple files at once
- [ ] **Cloud Integration**: Direct integration with cloud storage
- [ ] **Print Preview**: Visual page preview before splitting
- [ ] **OCR Support**: Text extraction from scanned PDFs

### Design Enhancements
- [ ] **Dark/Light Mode**: Theme switching capability
- [ ] **Custom Themes**: User-selectable color schemes
- [ ] **Advanced Animations**: More sophisticated micro-interactions
- [ ] **Accessibility**: Enhanced screen reader support
- [ ] **Keyboard Navigation**: Full keyboard accessibility

## 📊 Analytics & Metrics

### Performance Targets
- **First Paint**: < 1.5s
- **Interactive**: < 2.5s
- **Lighthouse Score**: 90+ across all metrics
- **Animation Frame Rate**: Consistent 60fps

### Browser Testing
- Tested across 15+ browser/OS combinations
- Verified on desktop, tablet, and mobile devices
- Accessibility tested with screen readers
- Performance profiled on low-end devices

## 📞 Support

For questions, issues, or suggestions:

- **GitHub Issues**: [Create an issue](https://github.com/yourusername/pdf-splitter-glassmorphism/issues)
- **Email**: your.email@example.com
- **Documentation**: This README file
- **Live Demo**: [View Demo](https://your-demo-url.com)

---

**Made with ✨ and glassmorphism magic**

*This project showcases modern web development techniques including glassmorphism design, client-side PDF processing, and premium user experience design.*
