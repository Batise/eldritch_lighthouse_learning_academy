# 🏮 ELLA - Eldritch Lighthouse Language Academy

A sophisticated and mysterious landing page for an English language school that guides students through the fog of grammar to clarity and confidence.

## 🌟 Features

### Design System
- **Color Palette**: Deep emerald green (#009688) primary with dark charcoal (#212121) backgrounds
- **Typography**: Poppins for headings, Merriweather for body text
- **Responsive**: Mobile-first design with desktop and tablet optimization
- **Accessibility**: WCAG 2.1 compliant with keyboard navigation and screen reader support

### Interactive Elements
- **Animated Lighthouse Beam**: Rotating lighthouse beam effect in hero section
- **Mobile Navigation**: Hamburger menu with smooth animations
- **Scroll Effects**: Fade-in animations and navbar transformations
- **Interactive Cards**: Hover effects on course cards and feature cards
- **Counter Animation**: Animated statistics in hero section

### Sections
1. **Hero Section**: Main value proposition with animated lighthouse visual
2. **Social Proof**: Credibility cards showcasing unique selling propositions
3. **Course Overview**: Three main course offerings with detailed features
4. **How It Works**: Visual timeline of the student journey
5. **Call-to-Action**: Prominent conversion section
6. **Footer**: Comprehensive links and social media integration

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code recommended)
- Live server extension (optional, for development)

### Installation

1. **Clone or download the repository**
   ```bash
   git clone https://github.com/your-username/ELLA.git
   cd ELLA
   ```

2. **Open the project**
   - Open `index.html` in your web browser, or
   - Use a live server for development

3. **That's it!** The page is ready to use.

## 📁 File Structure

```
ELLA/
├── index.html          # Main HTML structure
├── styles.css          # Complete CSS design system
├── script.js           # Interactive JavaScript functionality
└── README.md           # This documentation
```

## 🎨 Design Specifications

### Color Palette
```css
Primary Colors:
- Emerald Green: #009688 (guidance light)
- Dark Charcoal: #212121 (night sky)
- Ocean Blue: #1976D2 (alternative accent)

Text Colors:
- Primary Text: #FFFFFF (crisp white)
- Secondary Text: #FBEEC1 (warm cream)
- Muted Text: #B0BEC5 (subtle grey)
```

### Typography Scale
```css
Headings: 'Poppins', sans-serif
- H1: clamp(2.5rem, 5vw, 4rem)
- H2: clamp(2rem, 4vw, 3rem)
- H3: clamp(1.5rem, 3vw, 2rem)

Body: 'Merriweather', serif
- Body: clamp(1rem, 2vw, 1.125rem)
- Small: clamp(0.875rem, 1.5vw, 1rem)
```

### Spacing System
```css
--spacing-xs: 0.5rem    (8px)
--spacing-sm: 1rem      (16px)
--spacing-md: 2rem      (32px)
--spacing-lg: 3rem      (48px)
--spacing-xl: 4rem      (64px)
--spacing-xxl: 6rem     (96px)
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+ (primary design target)
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

### Mobile Optimizations
- Collapsible hamburger navigation
- Stacked hero statistics
- Single-column course grid
- Simplified timeline layout
- Touch-optimized button sizes

## 🎯 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Customization

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #009688;     /* Change primary color */
    --secondary-color: #212121;   /* Change background */
    --text-primary: #FFFFFF;      /* Change text color */
}
```

### Content
Modify text content directly in `index.html`:
- Update hero headlines and descriptions
- Change course offerings and features
- Modify social proof statements
- Update contact information in footer

### Fonts
Change typography in the `<head>` section of `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;600;700&display=swap" rel="stylesheet">
```

## 🚀 Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/ELLA`

### Netlify
1. Drag and drop the project folder to [Netlify Deploy](https://app.netlify.com/drop)
2. Your site will be live instantly with a custom URL

### Traditional Hosting
Upload all files to your web hosting provider's public folder (usually `public_html` or `www`).

## 🎨 Figma Design System

This implementation follows the detailed Figma specifications:

### Reusable Components
- Navigation bar with logo and menu items
- Button variants (primary, secondary, hero, course)
- Course cards with icons and feature lists
- Social proof cards with hover effects
- Timeline steps with connecting elements

### Design Frames
- **Desktop (1440px)**: Full-featured layout with sidebar navigation
- **Mobile (375px)**: Responsive mobile-first experience

## 🔍 SEO Optimization

- Semantic HTML5 structure
- Meta descriptions and titles
- Proper heading hierarchy (H1 → H6)
- Alt text for decorative icons
- Schema markup ready (can be added)

## ♿ Accessibility Features

- **Keyboard Navigation**: Full keyboard accessibility
- **Screen Readers**: Semantic markup and ARIA labels
- **Focus Management**: Visible focus indicators
- **Color Contrast**: WCAG AA compliant contrast ratios
- **Skip Links**: Skip to main content functionality

## 🧪 Testing

### Manual Testing Checklist
- [ ] Navigation works on all screen sizes
- [ ] All buttons and links are functional
- [ ] Animations play smoothly
- [ ] Mobile menu toggles correctly
- [ ] Form interactions provide feedback
- [ ] Page loads quickly on slow connections

### Recommended Tools
- **Lighthouse**: Performance and accessibility audits
- **WAVE**: Web accessibility evaluation
- **BrowserStack**: Cross-browser testing
- **GTmetrix**: Performance analysis

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For questions or support:
- 📧 Email: support@ella-academy.com
- 🐛 Issues: [GitHub Issues](https://github.com/your-username/ELLA/issues)
- 📖 Documentation: This README file

## 🔮 Future Enhancements

- [ ] Course enrollment functionality
- [ ] Student portal integration
- [ ] Multi-language support
- [ ] Advanced animations with Framer Motion
- [ ] Blog/news section
- [ ] Live chat integration
- [ ] Video testimonials
- [ ] Interactive placement test

---

**Built with ❤️ for English language learners worldwide**

*"We guide you through the fog of grammar to clarity and confidence."*
