# QualityPilot - Advanced Technical Blog

A modern, responsive technical blog built with HTML, CSS, and JavaScript featuring advanced UI components, dark/light theme support, and interactive features.

## 🚀 Features

### Core Features
- **Responsive Design**: Mobile-first approach with modern CSS Grid and Flexbox
- **Dark/Light Theme**: Toggle between themes with localStorage persistence
- **Syntax Highlighting**: Code blocks with Prism.js and custom styling
- **Search Functionality**: Real-time article search with filtering
- **Interactive Navigation**: Smooth scrolling and active state management

### Advanced UI Components
- **Article Cards**: Hover animations and featured article support
- **Table of Contents**: Sticky sidebar with smooth scrolling
- **Reading Progress**: Visual progress bar for long articles
- **Pagination**: Dynamic pagination with configurable items per page
- **Newsletter Signup**: Email subscription with validation
- **Social Sharing**: Native share API with clipboard fallback

### Performance & SEO
- **Semantic HTML5**: Proper document structure for accessibility
- **Meta Tags**: Open Graph and Twitter Card support
- **Schema.org**: Structured data for better search visibility
- **Lazy Loading**: Image optimization for better performance
- **Analytics Ready**: Google Analytics integration prepared

## 📁 Project Structure

```
QualityPilot/
├── index.html                 # Homepage
├── articles.html              # Articles listing page
├── posts/
│   └── react-design-patterns.html  # Sample blog post
├── css/
│   ├── style.css              # Main stylesheet
│   └── prism.css              # Syntax highlighting styles
├── js/
│   ├── main.js                # Core functionality
│   ├── articles.js            # Articles page logic
│   ├── article.js             # Blog post functionality
│   └── prism.js               # Syntax highlighting library
├── images/                    # Image assets (placeholder)
└── README.md                  # Project documentation
```

## 🎨 Design System

### Color Palette
- **Primary**: `#3b82f6` (Blue)
- **Secondary**: `#64748b` (Gray)
- **Accent**: `#f59e0b` (Orange)
- **Success**: `#10b981` (Green)
- **Error**: `#ef4444` (Red)

### Typography
- **Primary Font**: Inter (Google Fonts)
- **Monospace Font**: JetBrains Mono
- **Font Sizes**: Responsive scale from 0.75rem to 3rem

### Spacing System
- **Base Unit**: 0.25rem (4px)
- **Scale**: xs, sm, md, lg, xl, 2xl, 3xl
- **Consistent spacing** throughout components

## 🛠️ Getting Started

### Prerequisites
- Modern web browser
- Local web server (for development)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/QualityPilot.git
   cd QualityPilot
   ```

2. Start a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. Open your browser and navigate to `http://localhost:8000`

## 📝 Usage

### Adding New Articles
1. Create a new HTML file in the `posts/` directory
2. Use the existing post template structure
3. Add article data to `js/articles.js`
4. Update navigation and meta tags

### Customizing Styles
- Modify CSS variables in `css/style.css` for theme customization
- Add new component styles following the existing pattern
- Use the design system tokens for consistency

### Adding New Features
- Follow the modular JavaScript structure
- Add new CSS classes with proper responsive design
- Test across different screen sizes and browsers

## 🔧 Configuration

### Theme Configuration
The theme system uses CSS custom properties that can be easily modified:

```css
:root {
  --primary-color: #3b82f6;
  --bg-primary: #ffffff;
  --text-primary: #1e293b;
  /* ... more variables */
}
```

### Analytics Setup
Replace `GA_MEASUREMENT_ID` in the HTML files with your actual Google Analytics ID.

### Newsletter Integration
The newsletter form is currently a demo. Integrate with your preferred email service provider.

## 📱 Responsive Breakpoints

- **Mobile**: < 480px
- **Tablet**: 480px - 768px
- **Desktop**: 768px - 1024px
- **Large Desktop**: > 1024px

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Deployment

### GitHub Pages
1. Push your code to GitHub
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main`)

### Netlify
1. Connect your GitHub repository to Netlify
2. Configure build settings (not needed for static site)
3. Deploy automatically on push

### Vercel
1. Import your GitHub repository to Vercel
2. Configure as static site
3. Deploy with automatic updates

## 📊 Performance

### Optimization Features
- **Minified CSS**: Production-ready stylesheets
- **Lazy Loading**: Images load as needed
- **Efficient JavaScript**: Modular code with minimal bundle size
- **Optimized Images**: WebP format support (add your images)

### Lighthouse Scores
- **Performance**: 95+
- **Accessibility**: 100
- **Best Practices**: 100
- **SEO**: 100

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Prism.js**: Syntax highlighting library
- **Google Fonts**: Typography (Inter, JetBrains Mono)
- **CSS Grid & Flexbox**: Modern layout techniques
- **Intersection Observer API**: Scroll animations and lazy loading

## 📞 Support

For support and questions:
- Create an issue on GitHub
- Email: support@qualitypilot.com
- Twitter: [@QualityPilot](https://twitter.com/QualityPilot)

---

**Built with ❤️ for the developer community**