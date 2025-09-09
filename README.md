# Ahmad Herzalla - Portfolio Homepage

Computer Systems Engineer portfolio showcasing web development projects and technical expertise. Built with modern web development practices, featuring responsive design and accessibility standards.

## Features

### ✨ Key Components
- **Fixed Navigation Header**: Shrinks on scroll with quick access to GitHub and contact
- **Intro Banner**: Professional introduction with educational background from PTUK
- **Latest Projects Section**: Showcasing real GitHub projects including BizGrow, Logic Circuit, and Municipal Management System
- **Contact Section**: Complete contact information including location in Palestine and direct phone link
- **Responsive Design**: Fully responsive across all devices (mobile, tablet, desktop)
- **Accessibility**: Meets WCAG A and AA standards

### 🎨 Design Features
- Modern, clean design with consistent color scheme
- Smooth animations and transitions
- Advanced CSS techniques including:
  - CSS Grid and Flexbox layouts
  - Scroll-driven animations
  - Backdrop filters
  - Custom animations with keyframes
  - Responsive typography with clamp()

### 🛠️ Technical Implementation
- **BEM Methodology**: Organized CSS architecture
- **SCSS Preprocessor**: Modular styles with variables and mixins
- **Semantic HTML**: Proper document structure
- **No JavaScript**: Pure CSS implementation

## Project Structure

```
portfolio-homepage/
├── dist/
│   └── main.css           # Compiled CSS
├── src/
│   ├── img/               # Images and placeholders
│   │   ├── banner-bg.svg
│   │   ├── profile-placeholder.svg
│   │   └── project-*.svg
│   └── scss/
│       ├── base/          # Reset and typography
│       │   ├── _resets.scss
│       │   ├── _typography.scss
│       │   └── base.scss
│       ├── blocks/        # Component styles
│       │   ├── _header.scss
│       │   ├── _intro-banner.scss
│       │   ├── _projects.scss
│       │   ├── _button.scss
│       │   ├── _footer.scss
│       │   ├── _main.scss
│       │   └── blocks.scss
│       ├── utils/         # Variables and mixins
│       │   ├── _variables.scss
│       │   ├── _mixins.scss
│       │   └── utils.scss
│       └── main.scss      # Main SCSS file
├── index.html             # Main HTML file
├── package.json           # Dependencies and scripts
└── README.md
```

## Getting Started

### Prerequisites
- Node.js and npm installed
- Modern web browser

### Installation

1. Clone or download the project
2. Install dependencies:
   ```bash
   npm install
   ```

### Development

To compile SCSS and watch for changes:
```bash
npm run dev
```

To build for production (compressed CSS):
```bash
npm run build
```

### Viewing the Site

Open `index.html` in your web browser or use a local server for best results.

## Customization

### Personalizing Content

1. **Personal Information**: 
   - Name: Ahmad Herzalla
   - Education: Bachelor's in Computer Systems Engineering from PTUK
   - Location: Kafr Ra'i, Jenin, Palestine
   - Phone: +970 568 789 593

2. **GitHub Projects** (Click on any project card to view on GitHub):
   - **[BizGrow Landing Website](https://github.com/Ahmad-Herzalla0/BizGrow-Landing-Website)** - Responsive business landing page with HTML/CSS
   - **[Basic Logic Circuit](https://github.com/Ahmad-Herzalla0/Basic-Logic-circut)** - Interactive digital logic circuit simulator with JavaScript
   - **[Municipal Complaints System](https://github.com/Ahmad-Herzalla0/Municipalities-Complaints-Management)** - Online platform for Palestine municipalities
   - View all repositories at: https://github.com/Ahmad-Herzalla0

3. **Colors**: 
   - Modify color variables in `src/scss/utils/_variables.scss`
   - Primary and secondary colors can be easily changed

4. **Typography**:
   - Font families and sizes are defined in variables
   - Easily customizable in `_variables.scss`

## Accessibility Features

This portfolio meets WCAG A and AA standards:

- ✅ Semantic HTML structure
- ✅ Proper heading hierarchy
- ✅ Meaningful alt text for images
- ✅ ARIA labels and roles
- ✅ Keyboard navigation support
- ✅ Focus indicators
- ✅ Color contrast ratio > 4.5:1
- ✅ Responsive text sizing
- ✅ Reduced motion support

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

Note: Scroll-driven animations have fallbacks for browsers without support.

## Performance Optimizations

- Optimized CSS with minimal specificity
- Efficient animations using transform and opacity
- Lazy-loaded images (when using actual images)
- Minimal paint and reflow operations

## Future Enhancements

Potential improvements for future versions:
- Add more sections (Skills, Testimonials, Contact)
- Implement a blog section
- Add dark mode toggle
- Include more project details with modal views
- Integrate with a CMS for dynamic content

## License

MIT License - Feel free to use this project for your portfolio!

## Author

Ahmad Herzalla - Computer Systems Engineer
- GitHub: [@Ahmad-Herzalla0](https://github.com/Ahmad-Herzalla0)
- Education: Palestine Technical University - Kadoorie (PTUK)
- Location: Kafr Ra'i, Jenin, Palestine
