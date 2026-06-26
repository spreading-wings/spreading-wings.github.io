# Spreading Wings - Market Research Company Website

A premium, modern website for Spreading Wings market research company, featuring elegant design, smooth animations, and comprehensive service showcases.

## 📁 Project Structure

```
vinod_website/
│
├── css/
│   └── styles.css      # All CSS styles and responsive design rules
│
├── js/
│   └── script.js       # JavaScript for interactivity and animations
│
├── index.html          # Main HTML file with complete website structure
├── Logo.jpg              # 🎨 Company logo (your custom logo)
├── logo.svg              # 🎨 SVG logo template (reference only)
├── styles.css          # Alternative: CSS in root directory
├── script.js           # Alternative: JS in root directory
└── README.md           # Project documentation
```

**Note**: The website works with either folder structure:
- **Organized**: Use `css/styles.css` and `js/script.js` (recommended)
- **Simple**: Use `styles.css` and `script.js` in root directory

## 🎨 Adding Your Logo

The website is configured to use **Logo.jpg** for branding in the navigation and footer.

### How to Add Your Logo:

**Current Setup: Using Logo.jpg**
- The website now uses `Logo.jpg` (capital L)
- Simply place your logo file named `Logo.jpg` in the root directory
- JPG format is active (PNG and SVG also supported)

**Option 1: Use JPG Format (Current)**
- Prepare your logo as JPG (200x200px to 500x500px recommended)
- Name it exactly `Logo.jpg` (capital L)
- Place in the root directory
- Works great for photographic logos

**Option 2: Use PNG Format**
- Better for logos with transparency
- Name it `Logo.jpg` or update HTML to reference `logo.png`
- Transparent background recommended

**Option 3: Use SVG Format**
- Best for scalability and quality
- Update HTML references from `Logo.jpg` to `logo.svg`
- Perfect scaling at any size

**Logo Specifications:**
- **Format**: JPG (current), PNG, or SVG supported
- **File Name**: `Logo.jpg` (capital L - case-sensitive)
- **Navigation**: 55px height (auto-width)
- **Footer**: 70px height with enhanced brightness
- **Colors**: Works on white (nav) and dark (footer) backgrounds

## 🎨 Features

### Design Elements
- **Premium Color Scheme**: Navy blues with gold accents for a professional look
- **Modern Typography**: Inter font family for clean, readable text
- **Smooth Animations**: Fade-in effects and scroll-triggered animations
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices

### Sections
1. **Navigation Bar** - Fixed header with smooth scroll links
2. **Hero Section** - Eye-catching gradient background with animated grid pattern
3. **Statistics** - Showcase of company achievements and scale
4. **Services** - 6 core service offerings with hover effects
5. **Insights** - Latest articles and research perspectives
6. **Case Studies** - 4 detailed success stories with measurable results
7. **About Section** - Company values and differentiators
8. **Contact Form** - Professional inquiry form for lead generation
9. **Footer** - Company information, links, and social media

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required

### Installation
1. Simply open `index.html` in your web browser
2. All files should be in the same directory

### Local Development
```bash
# Navigate to project directory
cd vinod_website

# Open with default browser (Windows)
start index.html

# Or open with specific browser
chrome index.html
firefox index.html
```

## 🎯 Key Features

### Interactive Elements
- Smooth scroll navigation
- Hover effects on cards and buttons
- Form validation and submission handling
- Scroll-triggered animations using Intersection Observer
- Dynamic navbar styling on scroll

### Responsive Breakpoints
- Desktop: 1024px and above
- Tablet: 768px - 1023px
- Mobile: Below 768px

## 🎨 Color Palette

```css
Primary Color:    #1a365d (Navy Blue)
Secondary Color:  #2d7dd2 (Sky Blue)
Accent Color:     #f59e0b (Gold/Orange)
Text Dark:        #1f2937 (Charcoal)
Text Light:       #6b7280 (Gray)
Background Light: #f9fafb (Off White)
```

## 📝 Customization

### Updating Content
- Edit `index.html` to modify text content
- Update service descriptions, case studies, and insights
- Change company information in footer

### Styling Changes
- Edit `styles.css` for design modifications
- Modify CSS variables in `:root` for quick color changes
- Adjust spacing, fonts, and animations

### Adding Functionality
- Edit `script.js` to add new interactive features
- Integrate with backend APIs for form submissions
- Add analytics tracking

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with flexbox and grid
- **JavaScript (ES6+)** - Vanilla JS for interactivity
- **Google Fonts** - Inter font family

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🌟 Best Practices Implemented

✅ Semantic HTML5 elements
✅ Accessible form labels
✅ SEO-friendly meta tags
✅ Mobile-first responsive design
✅ Optimized CSS with custom properties
✅ Smooth scroll behavior
✅ Performance-optimized animations
✅ Clean, maintainable code structure

## 📧 Contact Form

The contact form currently displays an alert on submission. To integrate with a backend:

1. Add form action to a server endpoint
2. Implement server-side validation
3. Set up email notifications
4. Add database storage for leads

Example backend integration:
```javascript
// In script.js, replace the form handler with:
document.querySelector('.contact-form').addEventListener('submit', async function(e) {
    e.preventDefault();
    const formData = new FormData(this);
    
    try {
        const response = await fetch('/api/contact', {
            method: 'POST',
            body: formData
        });
        
        if (response.ok) {
            alert('Thank you! We will contact you soon.');
            this.reset();
        }
    } catch (error) {
        alert('Something went wrong. Please try again.');
    }
});
```

## 🎓 Future Enhancements

- [ ] Add real images for insights and case studies
- [ ] Integrate blog system
- [ ] Add client testimonials carousel
- [ ] Implement backend API for contact form
- [ ] Add Google Analytics tracking
- [ ] Create additional service detail pages
- [ ] Add loading animations
- [ ] Implement cookie consent banner
- [ ] Add multi-language support
- [ ] Create admin dashboard

## 📄 License

This project is created for Spreading Wings market research company.

## 👥 Credits

Design inspiration from [Kantar](https://www.kantar.com/)
Developed with modern web technologies

---

**Last Updated**: June 26, 2026
**Version**: 1.0.0
