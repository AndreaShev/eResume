# eResume - Modern Personal Resume Portfolio

## Overview
eResume is a sleek, modern personal portfolio and resume website designed to showcase professional skills, experience, and projects in an elegant, user-friendly interface. Built with performance and aesthetics in mind, this responsive solution helps professionals stand out in the digital space.

## Key Features
- 🌐 **Fully Responsive Design** - Looks perfect on all devices
- ⚡ **Blazing Fast Performance** - Optimized for speed
- 🎨 **Modern UI/UX** - Clean, professional aesthetics
- 📄 **Multi-section Resume** - Comprehensive professional profile
- 📱 **Mobile-First Approach** - Priority mobile experience
- ♿ **WCAG Accessibility** - Inclusive design standards
- 🌓 **Dark/Light Mode** - User preference support

## Technologies Used
- **Frontend**: 
  ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)
- **Frameworks**: 
  ![SASS](https://img.shields.io/badge/-SASS-CC6699?logo=sass&logoColor=white)
- **Tools**: 
  ![Webpack](https://img.shields.io/badge/-Webpack-8DD6F9?logo=webpack&logoColor=black)
  ![Babel](https://img.shields.io/badge/-Babel-F9DC3E?logo=babel&logoColor=black)
- **Performance**: Lighthouse optimizations, Critical CSS, Image compression

## Live Demo
[View Live Portfolio](https://andreashev.github.io/eResume/)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/AndreaShev/eResume.git
cd eResume
```

2. Install dependencies:
```bash
npm install
```

3. Start development server:
```bash
npm run dev
```

4. Build production version:
```bash
npm run build
```

## Project Structure
```
eResume/
├── src/                # Source files
│   ├── assets/         # Images, fonts, icons
│   ├── js/             # JavaScript modules
│   ├── scss/           # SASS stylesheets
│   └── index.html      # Main HTML file
├── dist/               # Production build
├── webpack.config.js   # Build configuration
├── package.json        # Dependencies and scripts
└── README.md           # Documentation
```

## Key Components
1. **Hero Section** - First impression with personal introduction
2. **Skills Section** - Technical competencies visualization
3. **Experience Timeline** - Professional journey
4. **Project Gallery** - Portfolio showcase
5. **Education Section** - Academic background
6. **Contact Form** - Direct communication channel
7. **Theme Switcher** - Light/Dark mode toggle

## Performance Optimization
- **Asset Optimization**: 
  - Image compression with WebP format
  - Font subsetting and preloading
- **Efficient Loading**:
  - Code splitting with Webpack
  - Lazy loading for non-critical resources
- **CSS Management**:
  - Critical CSS inlining
  - SASS partials with modular structure
- **JavaScript Efficiency**:
  - ES6+ transpilation with Babel
  - Minification and tree-shaking

## Accessibility Features
- Semantic HTML5 structure
- ARIA landmarks and roles
- Keyboard navigation support
- Color contrast compliance (WCAG 2.1)
- Screen reader compatibility
- Reduced motion preferences
- Focus management for interactive elements

## Customization Guide
### 1. Personal Information
Edit `src/js/config.js`:
```javascript
const personalData = {
  name: "Andrii Shevchenko",
  title: "Frontend Developer",
  location: "Milano, Italy",
  email: "contact@example.com",
  // ... other personal details
};
```

### 2. Customize Sections
Modify the HTML structure in:
- `src/index.html` - Main sections
- `src/scss/sections/` - Section-specific styles

### 3. Theme Colors
Edit color variables in `src/scss/abstracts/_variables.scss`:
```scss
:root {
  --primary-color: #3498db;
  --secondary-color: #2ecc71;
  --text-color: #333;
  // ...
}

[data-theme="dark"] {
  --primary-color: #2980b9;
  --text-color: #f5f5f5;
  // ...
}
```

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a pull request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
- **Author**: AndreaShev
- **GitHub**: [AndreaShev](https://github.com/AndreaShev)
- **Portfolio**: [https://andreashev.github.io/eResume/](https://andreashev.github.io/eResume/)

---

**Version**: 2.1.0  
