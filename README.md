# Kalyani Dupare - Portfolio Website

A modern, responsive portfolio website showcasing academic achievements, projects, skills, and career goals.

## 🌟 Features

- **Modern Design**: Clean, professional layout with beautiful gradients and animations
- **Responsive**: Fully responsive design that works on all devices
- **Interactive**: Smooth scrolling, hover effects, and animations
- **Comprehensive Sections**: All your academic and professional information organized beautifully
- **Fast Loading**: Optimized for performance with lazy loading and efficient code
- **Accessibility**: Built with accessibility best practices

## 📁 File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript functionality and animations
└── README.md           # This file
```

## 🚀 Getting Started

1. **Download the files**: Save all three files (`index.html`, `styles.css`, `script.js`) in the same folder
2. **Open the website**: Double-click on `index.html` to open it in your browser
3. **Customize**: Edit the content in `index.html` to match your information

## 🎨 Customization Guide

### Updating Personal Information

Edit the following sections in `index.html`:

#### Hero Section (Lines 35-60)
```html
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>
<p class="hero-subtitle">Your Title</p>
<p class="hero-description">
    Your introduction text
</p>
```

#### About Section (Lines 70-120)
- Update student ID, department, year, and college information
- Modify introduction and career objective text
- Add or remove languages

#### Contact Information (Lines 400-430)
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h4>Email</h4>
        <p>your.email@example.com</p>
    </div>
</div>
```

### Adding New Projects

To add a new project, copy this structure in the projects section:

```html
<div class="project-card">
    <div class="project-header">
        <h3>Project Name</h3>
        <span class="project-type academic">Type</span>
    </div>
    <p class="project-description">Project description</p>
    <div class="project-details">
        <div class="detail-item">
            <strong>Tools:</strong> Technology used
        </div>
        <div class="detail-item">
            <strong>Role:</strong> Your role
        </div>
        <div class="detail-item">
            <strong>Outcome:</strong> Results achieved
        </div>
        <div class="detail-item">
            <strong>SDG Goal:</strong> SDG number
        </div>
        <div class="detail-item">
            <strong>Status:</strong> <span class="status completed">Status</span>
        </div>
    </div>
</div>
```

### Project Types
- `academic` - Blue badge
- `personal` - Green badge  
- `startup` - Orange badge

### Status Types
- `completed` - Green badge
- `ongoing` - Orange badge

### Adding New Skills

In the skills section, add new skill tags:

```html
<span class="skill-tag">New Skill</span>
```

### Adding New Certifications

```html
<div class="cert-card">
    <div class="cert-header">
        <h3>Certification Name</h3>
        <span class="cert-status completed">Completed</span>
    </div>
    <div class="cert-details">
        <p><strong>Platform:</strong> Platform name</p>
        <p><strong>Completion Date:</strong> Date</p>
        <div class="cert-link">
            <i class="fas fa-certificate"></i>
            <span>Certificate Available</span>
        </div>
    </div>
</div>
```

## 🎨 Color Scheme

The website uses a modern color palette:

- **Primary**: Indigo (#6366f1)
- **Secondary**: Pink (#ec4899)
- **Accent**: Green (#10b981)
- **Text**: Dark gray (#1f2937)
- **Background**: Light gray (#f9fafb)

### Changing Colors

To change the color scheme, edit the CSS variables in `styles.css` (lines 8-20):

```css
:root {
    --primary-color: #6366f1;      /* Change this */
    --secondary-color: #ec4899;    /* Change this */
    --accent-color: #10b981;       /* Change this */
    /* ... other variables */
}
```

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones
- All screen sizes

## ⚡ Performance Features

- **Lazy Loading**: Images load only when needed
- **Smooth Animations**: Optimized animations for better performance
- **Minimal Dependencies**: Only uses Font Awesome icons and Google Fonts
- **Fast Loading**: Optimized CSS and JavaScript

## 🔧 Advanced Customization

### Adding New Sections

1. Create a new section in `index.html`:
```html
<section class="new-section">
    <div class="container">
        <h2 class="section-title">Section Title</h2>
        <!-- Your content here -->
    </div>
</section>
```

2. Add corresponding CSS in `styles.css`:
```css
.new-section {
    background: var(--bg-secondary);
    padding: 5rem 0;
}
```

### Adding Animations

The website includes several built-in animations:
- Fade-in effects when scrolling
- Hover effects on cards
- Typing animation for the hero title
- Counter animations for numbers

### JavaScript Features

- Mobile navigation toggle
- Smooth scrolling
- Scroll-to-top button
- Theme toggle (optional)
- Print functionality
- Loading animations

## 🌐 Deployment

### Option 1: GitHub Pages
1. Create a GitHub repository
2. Upload your files
3. Enable GitHub Pages in repository settings
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Netlify
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your folder
3. Get a free custom domain

### Option 3: Vercel
1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Deploy automatically

## 📞 Support

If you need help customizing your portfolio:

1. **Check the HTML structure** - Make sure all tags are properly closed
2. **Validate your CSS** - Use a CSS validator to check for errors
3. **Test responsiveness** - Use browser developer tools to test different screen sizes
4. **Check console** - Open browser developer tools to see any JavaScript errors

## 🎯 Tips for Success

1. **Keep it updated**: Regularly update your projects and achievements
2. **Use quality images**: If you add photos, use high-quality, professional images
3. **Test thoroughly**: Check your site on different devices and browsers
4. **Optimize content**: Keep descriptions concise but informative
5. **Add your resume**: Link to your actual resume PDF

## 📄 License

This portfolio template is free to use and modify for personal and educational purposes.

---

**Created with ❤️ for Kalyani Dupare**

*Good luck with your portfolio and career journey!*
