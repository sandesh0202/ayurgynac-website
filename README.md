# AyurGynac Hospital Website

A modern, responsive website for AyurGynac Streerog Chikitsalaya & Panchakarma Centre - an Ayurvedic healthcare center specializing in women's health and wellness.

## 🌿 About the Project

This website was designed for the grand opening ceremony of AyurGynac, incorporating the color palette and design elements from the original invitation card. The site serves as both an inauguration announcement and a comprehensive platform for the healthcare center.

## ✨ Features

### 🎨 Design Features
- **Authentic Color Palette**: Based on the original invitation card
  - Deep Green (#6B7F5A) - Primary color
  - Coral/Salmon Pink (#D4999B) - Secondary color
  - Cream Background (#F8F6F0) - Main background
  - Maroon/Deep Red (#8B2635) - Accent color

- **Logo Recreation**: Custom CSS-based logo matching the original circular design with woman silhouette and leaves

- **Minimalistic Design**: Clean, modern layout with proper spacing and typography

### 📱 Responsive Design
- **Mobile-First Approach**: Optimized for all screen sizes
- **Breakpoints**: 
  - Mobile: < 480px
  - Tablet: 481px - 768px
  - Desktop: > 768px
- **Touch-Friendly**: Optimized for mobile interactions

### 🚀 Performance Features
- **Service Worker**: Offline functionality and caching
- **Lazy Loading**: Optimized image loading
- **CSS Optimization**: Efficient selectors and minimal CSS
- **Font Optimization**: Web font loading optimization

### 🎯 Interactive Features
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Animated navigation between sections
- **Form Validation**: Client-side form validation with Indian phone number support
- **WhatsApp Integration**: Floating WhatsApp button for instant contact
- **Notification System**: User feedback for form submissions
- **Scroll Animations**: Elements animate into view on scroll

### ♿ Accessibility Features
- **Skip Links**: Skip to main content functionality
- **Keyboard Navigation**: Full keyboard accessibility
- **ARIA Labels**: Screen reader friendly
- **Focus Management**: Visible focus indicators
- **Color Contrast**: WCAG compliant color schemes

## 📁 File Structure

```
/
├── index.html          # Main HTML structure
├── styles.css          # Complete CSS with responsive design
├── script.js           # JavaScript for interactivity
├── sw.js              # Service Worker for performance
└── README.md          # This documentation
```

## 🛠️ Setup Instructions

### Option 1: Simple Setup
1. Download all files to a folder
2. Open `index.html` in a web browser
3. The website is ready to use!

### Option 2: Local Server (Recommended)
1. Install a local server (e.g., Live Server, Python's HTTP server)
2. Serve the files from the project directory
3. Access via `http://localhost:PORT`

### Option 3: Web Hosting
1. Upload all files to your web hosting provider
2. Ensure `index.html` is in the root directory
3. The website will be live at your domain

## 📄 Content Sections

### 🏠 Homepage Sections
1. **Header**: Navigation with logo and menu
2. **Hero Section**: Welcome message and inauguration banner
3. **About Section**: Information about AyurGynac services
4. **Services Section**: Detailed service offerings
5. **Inauguration Section**: Complete event details from invitation
6. **Contact Section**: Contact information and appointment form
7. **Footer**: Additional links and social media

### 📝 Inauguration Details
- **Date**: Friday, 5th September 2025 at 11:45 AM
- **Chief Guest**: वै.पू.सुदगुरू सुरेश महाराज रामदासी (सार्टेगांवकर)
- **Location**: लक्ष्मी कॉम्प्लेक्स, पहिला मजला, अंबिका चौकाजवळ, कैलाश रोड, बीड
- **Contact**: +91 7758806867

### 🏥 Services Offered
- Gynecological Care
- Fertility Treatment (Male & Female)
- Panchakarma Therapy
- Menopausal Support
- Preventive Care
- Herbal Medicine

## 🔧 Customization

### Colors
All colors are defined as CSS custom properties in `:root`:
```css
:root {
    --primary-green: #6B7F5A;
    --secondary-pink: #D4999B;
    --cream-background: #F8F6F0;
    --accent-maroon: #8B2635;
}
```

### Content Updates
- Edit `index.html` for content changes
- Update contact information in multiple sections
- Modify service descriptions as needed

### Styling Changes
- All styles are in `styles.css`
- Responsive breakpoints can be adjusted
- Typography can be customized via CSS custom properties

## 📱 Mobile Features

### Mobile Navigation
- Hamburger menu for small screens
- Slide-in navigation panel
- Touch-friendly menu items

### Mobile Optimization
- Touch targets are minimum 44px
- Readable font sizes on all devices
- Optimized button sizes for touch
- Swipe-friendly interactions

## 🌐 Browser Support

### Modern Browsers
- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 80+

### Features with Fallbacks
- CSS Grid (falls back to flexbox)
- CSS Custom Properties (fallback values provided)
- Service Worker (graceful degradation)

## 📊 Performance

### Lighthouse Scores (Expected)
- Performance: 95+
- Accessibility: 100
- Best Practices: 95+
- SEO: 100

### Optimization Features
- Minified CSS and JavaScript
- Optimized images
- Efficient caching strategy
- Lazy loading implementation

## 🚀 Deployment

### GitHub Pages
1. Create a new repository
2. Upload files
3. Enable GitHub Pages
4. Access via `username.github.io/repository-name`

### Netlify
1. Drag and drop the project folder to Netlify
2. Automatic deployment and HTTPS
3. Custom domain support available

### Vercel
1. Connect your GitHub repository
2. Automatic deployment on push
3. Serverless functions support

## 🔮 Future Enhancements

### Potential Additions
- Online appointment booking system
- Patient portal
- Blog section for health tips
- Multi-language support (Hindi/Marathi)
- Doctor profiles
- Testimonials section
- Gallery of facilities
- Online consultation booking

### Technical Improvements
- Progressive Web App (PWA) features
- Push notifications
- Advanced analytics
- SEO optimization
- Performance monitoring
- A/B testing capabilities

## 📞 Contact Information

**AyurGynac Streerog Chikitsalaya & Panchakarma Centre**
- **Address**: लक्ष्मी कॉम्प्लेक्स, पहिला मजला, अंबिका चौकाजवळ, कैलाश रोड, बीड
- **Phone**: +91 7758806867
- **WhatsApp**: Direct integration available on website

## 🙏 Acknowledgments

- Design inspired by the original inauguration invitation card
- Color palette extracted from traditional invitation design
- Typography chosen for bilingual readability (English/Hindi)
- Icons from Font Awesome
- Fonts from Google Fonts (Poppins, Playfair Display)

---

**Built with ❤️ for AyurGynac - Specializing in Women's Health & Ayurvedic Wellness**

*Website ready for inauguration ceremony and ongoing use! 🌿*
