# Bogato - Static HTML + Tailwind CSS Blog

A beautiful, responsive blog website built with pure HTML and Tailwind CSS, recreated from the original React-based Bogato project.

## 🎯 Project Overview

This project is a static HTML recreation of the original full-stack Bogato blog website. It maintains the same elegant design, responsive layout, and professional appearance while using only HTML and Tailwind CSS for maximum portability and simplicity.

## ✨ Features

- **📱 Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **🎨 Modern Design**: Clean, professional layout with warm orange (#f97316) primary color and navy accents
- **📖 Multiple Page Types**: Homepage, Featured Articles, Latest Articles, and Blog Details
- **🔍 Interactive Elements**: Mobile menu, hover effects, and smooth transitions
- **📝 Rich Typography**: Playfair Display for headings and Inter for body text
- **🖼️ Optimized Images**: High-quality book and literary imagery
- **🌐 Static & Fast**: No backend dependencies, loads instantly

## 📋 Pages Included

### 🏠 Homepage (index.html)
- Hero banner with call-to-action
- Categories sidebar with popular topics
- Featured articles section (3 highlighted articles)
- Latest articles grid (6 recent posts)
- Popular articles sidebar
- Newsletter signup
- Complete navigation and footer

### ⭐ Featured Articles (featured.html)
- Dedicated page for all featured content
- Filter and sort functionality (UI only)
- Grid layout with enhanced cards
- Pagination controls
- 9 featured articles with rich metadata

### 🕒 Latest Articles (latest.html)
- Chronological list of recent articles
- Large card format with detailed excerpts
- Interactive elements (like, bookmark, share)
- Load more functionality
- Newsletter signup section

### 📰 Blog Details (blog-details.html)
- Complete article layout with rich content
- Table of contents sidebar
- Related books recommendations
- Related articles suggestions
- Social sharing buttons
- Comments section with sample comments
- Author biography section
- Tags and metadata

## 🎨 Design System

### Color Palette
```css
Primary Orange: #f97316 (warm, inviting)
Navy Accents: #1e293b to #0f172a (professional, readable)
Gray Backgrounds: #f8fafc to #e2e8f0 (clean, modern)
```

### Typography
- **Headings**: Playfair Display (elegant serif)
- **Body**: Inter (clean sans-serif)
- **Size Scale**: Responsive from text-sm to text-6xl

### Layout
- **Mobile-First**: Responsive design starting from 320px
- **Breakpoints**: sm (640px), md (768px), lg (1024px), xl (1280px)
- **Max Width**: 7xl (1280px) with proper padding
- **Grid System**: CSS Grid and Flexbox for layouts

## 🚀 Getting Started

### Prerequisites
- Any modern web browser
- Local web server (optional, for development)

### Installation
1. Clone or download the project
2. Open `index.html` in your browser, or
3. Serve with a local web server:
   ```bash
   cd bogato
   python3 -m http.server 8080
   ```

### File Structure
```
bogato/
├── index.html              # Homepage
├── featured.html           # Featured articles page
├── latest.html            # Latest articles page
├── blog-details.html      # Article detail template
├── assets/
│   └── images/           # Optimized images
│       ├── hero-banner.jpg
│       ├── book-1.jpg
│       ├── book-2.jpg
│       └── ... (8 total)
└── README.md              # This file
```

## 🛠️ Technical Details

### Built With
- **HTML5**: Semantic markup with proper accessibility
- **Tailwind CSS**: Utility-first CSS framework via CDN
- **Lucide Icons**: Beautiful icon library via CDN
- **Google Fonts**: Playfair Display and Inter typography
- **Vanilla JavaScript**: Mobile menu and interactive elements

### CDN Dependencies
- Tailwind CSS: `https://cdn.tailwindcss.com`
- Lucide Icons: `https://unpkg.com/lucide@latest/dist/umd/lucide.js`
- Google Fonts: Playfair Display + Inter

### Browser Support
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 📱 Responsive Features

### Mobile (< 768px)
- Collapsible hamburger menu
- Single-column layouts
- Touch-friendly buttons
- Optimized image sizes

### Tablet (768px - 1024px)
- Two-column layouts
- Balanced content distribution
- Hybrid navigation

### Desktop (> 1024px)
- Multi-column layouts
- Sidebar navigation
- Hover interactions
- Full feature set

## 🎯 Key Features

### Interactive Elements
- Mobile menu with smooth animations
- Hover effects on cards and buttons
- Image zoom on hover
- Smooth transitions throughout

### Typography Hierarchy
- Clear heading structure (h1-h6)
- Consistent text sizing
- Proper line heights
- Optimized reading experience

### Content Structure
- Semantic HTML markup
- Proper heading hierarchy
- Accessible navigation
- SEO-friendly structure

## 🔧 Customization

### Colors
Modify the Tailwind config in each HTML file:
```javascript
colors: {
    primary: { /* Orange palette */ },
    navy: { /* Navy palette */ }
}
```

### Typography
Change font families in the config:
```javascript
fontFamily: {
    'serif': ['Your Serif Font', 'serif'],
    'sans': ['Your Sans Font', 'sans-serif'],
}
```

### Images
Replace images in `assets/images/` with your own:
- Recommended size: 640px width for consistency
- Format: JPG for photos, PNG for graphics
- Compression: Optimize for web use

## 📊 Performance

### Optimization Features
- Minimal CSS (via Tailwind utilities)
- Compressed images
- CDN-delivered assets
- No JavaScript frameworks
- Fast loading times

### Best Practices
- Semantic HTML structure
- Proper image alt texts
- Responsive images
- Clean, maintainable code

## 🌟 Highlights

- **Pure HTML + CSS**: No build process required
- **Tailwind CSS**: Utility-first styling approach
- **Mobile-First**: Responsive design from the ground up
- **Performance**: Lightning-fast loading
- **Accessibility**: Semantic HTML and proper navigation
- **Professional**: Production-quality design and code

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📞 Support

For questions or support, please contact the development team or open an issue in the repository.

---

**Built with ❤️ for book lovers and literature enthusiasts**

**Bogato - Where stories come to life**