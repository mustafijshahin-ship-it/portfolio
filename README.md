markdown
# 🌐 Personal Portfolio Website

A modern, accessible portfolio website built with semantic HTML5 and CSS3. Features perfect accessibility scores, responsive design, and a dark theme.

## ✨ Live Demo
🔗 **[View Live Portfolio](https://mustafijshahin-ship-it.github.io/portfolio/)**

## 📊 Performance Metrics (Lighthouse)

| Metric | Score | Status |
|--------|-------|--------|
| **Accessibility** | 100/100 | ✅ Perfect |
| **SEO** | 100/100 | ✅ Perfect |
| **Performance** | 84-87/100 | 🟢 Excellent |
| **Best Practices** | 78-81/100 | 🟢 Good |

## 🚀 Features

### ✅ **Accessibility First**
- WCAG AA compliant with 100/100 accessibility score
- Proper semantic HTML5 structure
- Keyboard navigation support
- Skip links for screen readers
- High contrast color scheme

### 🎨 **Modern Design**
- Dark theme with gradient accents
- Responsive layout (mobile, tablet, desktop)
- Interactive hover effects and transitions
- Custom CSS animations

### ⚡ **Performance Optimized**
- WebP images with JPEG fallbacks
- Minified CSS
- Lazy-loaded images
- Efficient caching strategy

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic markup, accessibility |
| **CSS3** | Styling, Flexbox, responsive design |
| **GitHub Pages** | Free hosting & deployment |
| **Lighthouse** | Performance auditing |

## 📁 Project Structure
portfolio/
├── index.html # Main homepage
├── about.html # About me page
├── main.css # All styles (minified)
├── README.md # This file
├── .gitignore # Git exclusion rules
├── Images/ # All project images
│ ├── me.jpg # Avatar (JPEG fallback)
│ ├── me.webp # Avatar (WebP optimized)
│ ├── beach.jpg # Beach image
│ ├── beach.webp # Beach image optimized
│ ├── sands.jpg # Landscape image
│ └── sands.webp # Landscape optimized
└── (Other assets)

text

## 🔧 Development Highlights

### **Image Optimization**
```html
<!-- Modern WebP with fallback for all browsers -->
<picture>
    <source srcset="Images/me.webp" type="image/webp">
    <img src="Images/me.jpg" alt="Md. Mustafijur Rahman" 
         width="300" height="300" loading="lazy" decoding="async">
</picture>
Accessibility Features
Semantic landmarks (<header>, <main>, <footer>)

ARIA labels for navigation

Focus indicators for keyboard users

Screen reader-only text where needed

Responsive Design
Mobile-first approach

Flexible layouts with CSS Flexbox

Media queries for breakpoints at 768px

📚 Learning Journey
This portfolio represents my journey through:

Harvard's CS50 course fundamentals

Semantic HTML5 markup practices

CSS layout techniques (Flexbox, positioning)

Web accessibility standards (WCAG)

Performance optimization strategies

🎯 What I Learned
Accessibility isn't optional - Built with WCAG AA standards from the start

Performance matters - Optimized images, minified CSS, efficient loading

Semantic HTML improves both SEO and accessibility

Mobile-first design creates better experiences for all users

🌟 Key Achievements
✅ Perfect 100/100 Accessibility score

✅ Perfect 100/100 SEO score

✅ Responsive across all devices

✅ Fast loading times (Performance 84-87/100)

✅ Clean, maintainable code structure

📬 Connect With Me
GitHub: @mustafijshahin-ship-it

Portfolio: Live Demo

CS50 Progress: Currently learning through Harvard's CS50 course

📄 License
This project is open source and available under the MIT License.

Built with semantic HTML, accessible CSS, and a focus on performance.
Last updated: January 2024