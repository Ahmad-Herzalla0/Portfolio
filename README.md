# Ahmad Herzalla - Portfolio Homepage

A professional, responsive, and accessible portfolio homepage showcasing Computer Systems Engineering expertise and web development projects.

## 👨‍💻 About

**Ahmad Herzalla**  
Computer Systems Engineer | Bachelor's Degree from Palestine Technical University - Kadoorie (PTUK)  
Based in Kafr Ra'i, Jenin, Palestine

## 🌟 Project Overview

This portfolio homepage demonstrates modern web development practices including responsive design, accessibility standards, and advanced CSS techniques. Built following BEM methodology with SCSS preprocessor, the site showcases real GitHub projects and provides comprehensive contact information.

## 🚀 Features

### Core Sections
- **Fixed Navigation Header**: Clean navigation with logo and menu items
- **Intro Banner**: Professional introduction with personal background
- **Latest Projects Section**: Showcasing real GitHub repositories
- **Contact Section**: Complete contact information with icons
- **Footer**: Simple copyright information

### Technical Features
- **100% Responsive**: Mobile-first design adapting to all screen sizes
- **Accessibility Compliant**: Meets WCAG A and AA standards
- **No JavaScript**: Pure CSS/HTML implementation
- **SEO Optimized**: Comprehensive meta tags and Open Graph
- **Performance Optimized**: Fast loading with optimized images

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup with proper document structure
- **CSS3**: Advanced features including Grid, Flexbox, animations
- **SCSS**: Preprocessor with variables, mixins, and modular architecture

### Methodology
- **BEM**: Block Element Modifier for maintainable CSS
- **Mobile-First**: Responsive design approach
- **Progressive Enhancement**: Works without JavaScript

## 📁 Project Structure

```
portfolio-homepage/
├── index.html                 # Main HTML file
├── package.json              # Project dependencies and scripts
├── README.md                 # Project documentation
├── dist/
│   ├── main.css             # Compiled CSS (production)
│   └── main.min.css         # Minified CSS backup
└── src/
    ├── img/                 # Optimized SVG images
    │   ├── profile-placeholder.png
    │   ├── project-1.png
    │   ├── project-2.png
    │   ├── project-3.png
    │   └── banner-bg.jpg
    └── scss/                # SCSS source files
        ├── main.scss        # Main SCSS file
        ├── base/           # Reset and typography
        │   ├── _resets.scss
        │   ├── _typography.scss
        │   └── base.scss
        ├── blocks/         # Component styles (BEM)
        │   ├── _header.scss
        │   ├── _intro-banner.scss
        │   ├── _projects.scss
        │   ├── _contact.scss
        │   ├── _button.scss
        │   ├── _footer.scss
        │   ├── _main.scss
        │   └── blocks.scss
        └── utils/          # Variables and mixins
            ├── _variables.scss
            ├── _mixins.scss
            └── utils.scss
```

## 🎨 Design Features

### Color Scheme
- **Primary**: Blue (#2563eb) - Professional and trustworthy
- **Secondary**: Green (#10b981) - Growth and success
- **Neutral**: Gray scale for text and backgrounds

### Typography
- **Font Family**: System fonts for optimal performance
- **Responsive Text**: Clamp() functions for fluid typography
- **Hierarchy**: Proper heading structure (h1 → h2 → h3)

### Animations
- **Smooth Transitions**: 300ms cubic-bezier timing
- **Hover Effects**: Subtle lift and color changes
- **Reduced Motion**: Respects user preferences

## 📱 Responsive Breakpoints

- **Mobile**: < 640px
- **Small**: 640px - 768px
- **Medium**: 768px - 1024px
- **Large**: 1024px - 1280px
- **Extra Large**: > 1280px

## ♿ Accessibility Features

### WCAG Compliance
- ✅ **Semantic HTML**: Proper document structure
- ✅ **Keyboard Navigation**: Full keyboard support
- ✅ **Screen Readers**: ARIA labels and roles
- ✅ **Color Contrast**: 4.5:1 ratio minimum
- ✅ **Focus Indicators**: Visible focus states
- ✅ **Alternative Text**: Meaningful image descriptions

### Inclusive Design
- ✅ **Reduced Motion**: Animation controls
- ✅ **Touch Targets**: 44px minimum size
- ✅ **Clear Language**: Simple, direct content
- ✅ **Logical Flow**: Intuitive navigation order

## 🚀 Getting Started

### Prerequisites
- Modern web browser
- Node.js (for SCSS compilation)

### Installation
1. **Clone/Download** the project files
2. **Install dependencies**:
   ```bash
   npm install
   ```

### Development
**Compile SCSS** (if making changes):
```bash
npm run sass:watch    # Watch for changes
npm run build        # Production build
```

### Viewing
Simply open `index.html` in your web browser or use a local server.

## 📊 Performance Optimizations

### Image Optimization
- **SVG Format**: Scalable vector graphics for crisp display
- **Optimized Sizes**: Reduced dimensions for faster loading
- **Lazy Loading**: Below-fold images load when needed
- **Proper Alt Text**: SEO and accessibility benefits

### CSS Optimization
- **CSS Containment**: Improved rendering performance
- **Hardware Acceleration**: GPU-optimized animations
- **Minimal Repaints**: Efficient property animations
- **Tree Shaking**: No unused CSS

### Loading Strategy
- **Critical CSS**: Above-fold styles prioritized
- **Resource Hints**: DNS prefetch for external links
- **Optimized Fonts**: System fonts for instant rendering

## 🎯 Project Highlights

### Real GitHub Projects
1. **[BizGrow Landing Website](https://github.com/Ahmad-Herzalla0/BizGrow-Landing-Website)**
   - Responsive business landing page
   - HTML/CSS with Flexbox/Grid layouts

2. **[Basic Logic Circuit Simulator](https://github.com/Ahmad-Herzalla0/Basic-Logic-circut)**
   - Interactive digital logic circuit designer
   - JavaScript with HTML5 Canvas

3. **[Municipal Complaints Management](https://github.com/Ahmad-Herzalla0/Municipalities-Complaints-Management)**
   - Online platform for Palestine municipalities
   - PHP/MySQL with security features

### Contact Information
- **Location**: Kafr Ra'i, Jenin, Palestine
- **Phone**: +970 568 789 593 (click to call)
- **Email**: ahmadherzalla31@gmail.com (click to send)
- **GitHub**: [@Ahmad-Herzalla0](https://github.com/Ahmad-Herzalla0)

## 🔧 Customization

### Personalizing Content
1. **Update personal information** in `index.html`
2. **Modify colors** in `src/scss/utils/_variables.scss`
3. **Replace images** in `src/img/` folder
4. **Adjust layout** in respective SCSS files

### Development Workflow
1. **Edit SCSS files** for styling changes
2. **Compile to CSS** using npm scripts
3. **Test responsiveness** across devices
4. **Validate accessibility** with tools

## 🏅 Project Standards

### Code Quality
- **BEM Methodology**: Consistent naming convention
- **SCSS Architecture**: Modular and maintainable
- **Semantic HTML**: Meaningful document structure
- **Clean Code**: Well-commented and organized

### Performance Standards
- **Fast Loading**: Optimized assets and code
- **Smooth Animations**: 60fps performance target
- **Efficient CSS**: Minimal specificity and reflows
- **Cross-Browser**: Compatible with modern browsers

## 📋 Browser Support

- **Chrome**: Latest versions
- **Firefox**: Latest versions  
- **Safari**: Latest versions
- **Edge**: Latest versions

## 📄 License

MIT License - Free to use for personal and educational purposes.

## 📞 Contact

**Ahmad Herzalla**
- **Email**: ahmadherzalla31@gmail.com
- **Phone**: +970 568 789 593
- **GitHub**: [@Ahmad-Herzalla0](https://github.com/Ahmad-Herzalla0)
- **Location**: Kafr Ra'i, Jenin, Palestine

---

> 🇵🇸 Built with pride in Palestine | Computer Systems Engineer | PTUK Graduate

**Last Updated**: January 2025