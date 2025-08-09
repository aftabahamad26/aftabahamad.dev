# Aftab Ahamad - Portfolio Website

A modern, responsive portfolio website for Aftab Ahamad, an aspiring software developer and tech enthusiast from Ismailpur, Bulandshahr, Uttar Pradesh.

## 🌟 Features

### Design & UX
- **Modern & Minimal Design** - Clean, professional layout with soft pastel colors
- **Dark/Light Theme Toggle** - Seamless theme switching with persistent preferences
- **Responsive Design** - Mobile-first approach, optimized for all screen sizes
- **Smooth Animations** - Fade-ins, hover effects, and smooth scrolling
- **Typewriter Effect** - Animated text on the homepage

### Sections
- **Home** - Hero section with profile placeholder and CTA buttons
- **About** - Personal bio, education details, and background information
- **Skills & Languages** - Visual progress bars for technical skills and languages
- **Experience** - Volunteer work, leadership roles, and internship placeholders
- **Projects** - Filterable project showcase with categories
- **Resume & Certificates** - Download resume and view certificates
- **Contact** - Contact form with Google Maps integration

### Technical Features
- **Performance Optimized** - Lazy loading, debounced scroll events
- **Accessibility** - ARIA labels, keyboard navigation, semantic HTML
- **SEO Friendly** - Meta tags, structured data, semantic markup
- **Cross-browser Compatible** - Works on all modern browsers
- **PWA Ready** - Service worker registration for offline capabilities

## 🎨 Color Palette

### Light Theme
- Primary: `#6366f1` (Indigo)
- Secondary: `#8b5cf6` (Purple)
- Accent: `#ec4899` (Pink)
- Background: `#ffffff` (White)
- Surface: `#f8fafc` (Light Gray)

### Dark Theme
- Background: `#0f172a` (Dark Blue)
- Surface: `#1e293b` (Dark Gray)
- Text: `#f1f5f9` (Light Gray)

## 🚀 Quick Start

### Prerequisites
- Modern web browser
- Local development server (optional)

### Installation

1. **Clone or Download**
   ```bash
   git clone <repository-url>
   cd portfolio_web
   ```

2. **Open in Browser**
   - Simply open `index.html` in your web browser
   - Or use a local development server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Access the Website**
   - Navigate to `http://localhost:8000` (if using server)
   - Or open `index.html` directly in browser

## 📁 Project Structure

```
portfolio_web/
├── index.html          # Main HTML file
├── styles.css          # CSS styles with theme support
├── script.js           # JavaScript functionality
├── assets/             # Static assets
│   └── favicon.svg     # Custom favicon
├── README.md           # Project documentation
└── .gitignore          # Git ignore file
```

## 🛠️ Customization

### Personal Information
Update the following sections in `index.html`:

1. **Personal Details**
   - Name, title, bio in hero section
   - About section content
   - Contact information

2. **Skills & Experience**
   - Modify skill percentages in skills section
   - Add/remove experience items
   - Update project details

3. **Contact Information**
   - Update email, phone, social media links
   - Modify Google Maps location

### Styling
Customize colors and styling in `styles.css`:

```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    /* ... other variables */
}
```

### Adding Projects
Add new project cards in the projects section:

```html
<div class="project-card" data-category="web-dev">
    <div class="project-image">
        <img src="path/to/image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Project Title</h3>
        <div class="project-stack">
            <span class="stack-tag">HTML</span>
            <span class="stack-tag">CSS</span>
        </div>
        <p>Project description...</p>
        <div class="project-buttons">
            <a href="#" class="btn btn-small">View Code</a>
            <a href="#" class="btn btn-small btn-secondary">Live Demo</a>
        </div>
    </div>
</div>
```

## 📱 Responsive Breakpoints

- **Mobile**: < 480px
- **Tablet**: 480px - 768px
- **Desktop**: > 768px

## 🔧 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📈 Performance Features

- **Lazy Loading** - Images load only when needed
- **Debounced Events** - Optimized scroll and resize handlers
- **CSS Variables** - Efficient theme switching
- **Minimal Dependencies** - Only Font Awesome for icons

## 🎯 SEO Features

- Semantic HTML structure
- Meta tags for social sharing
- Open Graph tags
- Structured data markup
- Alt text for images
- Proper heading hierarchy

## 🔒 Security

- Form validation on client-side
- XSS protection through proper escaping
- HTTPS ready for production

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Contact

For questions or support:
- Email: aftabahamad809@gmail.com
- Phone: +91 7818982635

## 🚀 Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Connect your GitHub repository
2. Build settings: leave empty (static site)
3. Deploy automatically on push

### Vercel
1. Import your GitHub repository
2. Framework preset: Other
3. Deploy automatically

## 📊 Analytics

To add Google Analytics:

1. Get your tracking ID from Google Analytics
2. Add this script before `</head>` in `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

## 🎨 Future Enhancements

- [ ] Blog section
- [ ] Portfolio gallery
- [ ] Testimonials section
- [ ] Newsletter subscription
- [ ] Multi-language support
- [ ] Advanced animations
- [ ] CMS integration
- [ ] E-commerce features

---

**Built with ❤️ for Aftab Ahamad**

*Last updated: December 2024* 