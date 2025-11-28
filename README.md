# Ntshwane Jeremia Mphorane - Developer Portfolio

A modern, sleek developer portfolio website featuring a cyberpunk-inspired design with neon purple and cyan aesthetics, smooth animations, and an interactive typewriter effect.

## 🎨 Design Features

- **Color Scheme**: Purple (#7859c4), Cyan (#80c0fa), and Dark Purple (#370e49) on black background
- **Animated Grid Background**: Subtle moving grid pattern
- **Cursor Glow Effect**: Interactive cursor trail that follows mouse movement
- **Typewriter Effect**: Slogan types itself letter by letter on page load
- **Smooth Animations**: Hover effects, transitions, and scroll-based navigation
- **Fully Responsive**: Mobile-friendly design that adapts to all screen sizes

## 🚀 Features

### Sections
1. **Hero Section**: Name, title, animated slogan, and CTA buttons
2. **About Section**: Personal bio and technical skills grid
3. **Projects Section**: Showcase of 6 featured projects with tech stacks
4. **Contact Section**: Social media links and contact information

### Interactive Elements
- Smooth scroll navigation
- Active section highlighting in navbar
- Project cards with hover animations
- Rounded corners on all elements
- Glowing effects on buttons and links

## 📁 Project Structure
```
portfolio/
├── index.html          # Main portfolio file
├── cv.pdf             # Your resume (add this!)
├── images/            # Optional: project screenshots
│   ├── project1.png
│   └── project2.png
└── README.md          # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with animations, gradients, and transitions
- **Vanilla JavaScript**: Interactive features and animations
- **No frameworks**: Pure HTML/CSS/JS for maximum performance

## 📝 Customization Guide

### 1. Personal Information
Update these sections in `index.html`:
```html
<!-- Line ~700: Your Name -->
<h1>Ntshwane Jeremia Mphorane</h1>

<!-- Line ~702: Your Title -->
<div class="typing">Full Stack Developer</div>

<!-- JavaScript: Your Slogan -->
const sloganText = "Your custom slogan here";
```

### 2. Skills
Update the skill tags in the About section (lines ~750-800):
```html
<span class="skill-tag">Your Skill</span>
```

### 3. Projects
Update project information (lines ~820-950):
```html
<div class="project-card">
    <div class="project-number">PROJECT_01</div>
    <h3>Your Project Name</h3>
    <p>Project description</p>
    <div class="tech-stack">
        <span>Tech 1</span>
        <span>Tech 2</span>
    </div>
    <div class="project-links">
        <a href="your-github-link">GitHub</a>
        <a href="your-demo-link">Live Demo</a>
    </div>
</div>
```

### 4. Social Links
Update social media URLs (lines ~1000-1050):
```html
<a href="https://github.com/yourusername">
<a href="https://linkedin.com/in/yourusername">
<a href="mailto:your.email@example.com">
<a href="https://twitter.com/yourusername">
```

### 5. Color Scheme
Modify colors in CSS (lines 15-22):
```css
:root {
    --cyan: #80c0fa;
    --aqua: #7859c4;
    --dark-purple: #370e49;
}
```

### 6. Animation Speed
Adjust typewriter speed (line ~1060):
```javascript
setTimeout(typeWriter, 80); // Lower = faster (30-100ms recommended)
```

## 🌐 Deployment Options

### Option 1: GitHub Pages (Free)
1. Push code to GitHub repository
2. Go to Settings → Pages
3. Select main branch
4. Your site will be live at `[Jerere's Portfolio](https://main.d2k1aud08zsf7o.amplifyapp.com/)`

### Option 2: AWS Amplify (Free Tier)
1. Create AWS account
2. Go to AWS Amplify
3. Connect your GitHub repository
4. Auto-deploy on every push
5. Get free SSL certificate

### Option 3: Netlify (Free)
1. Sign up at netlify.com
2. Drag & drop your portfolio folder
3. Get instant deployment with free SSL

### Option 4: Vercel (Free)
1. Sign up at vercel.com
2. Import from GitHub
3. Auto-deploy with custom domain support

## 📋 Pre-Deployment Checklist

- [ ] Replace "Ntshwane Jeremia Mphorane" with your name
- [ ] Update slogan text
- [ ] Add your projects with real links
- [ ] Update all social media URLs
- [ ] Replace email with your actual email
- [ ] Add your `cv.pdf` file to root directory
- [ ] Update skills to match your expertise
- [ ] Test on mobile devices
- [ ] Check all links work
- [ ] Optimize images (if added)

## 🎯 Performance Tips

1. **Images**: Compress all images with TinyPNG before uploading
2. **CV**: Keep PDF under 2MB
3. **Loading**: Page loads instantly with no external dependencies
4. **SEO**: Add meta tags for better search engine visibility

## 📱 Browser Support

- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Mobile browsers: ✅ Fully responsive

## 🔧 Troubleshooting

**Typewriter effect not working?**
- Check JavaScript console for errors
- Ensure the slogan element ID matches: `id="slogan"`

**Cursor glow not showing?**
- This effect only works on desktop with mouse
- Mobile devices won't show cursor glow (intentional)

**Links not working?**
- Make sure URLs include `https://`
- Check for typos in href attributes

## 📄 License

This portfolio template is free to use and modify for personal projects.

## 🤝 Credits

Design inspiration from modern cyberpunk and developer portfolio trends.

## 📞 Contact

- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourusername)
- Email: your.email@example.com

---

**Built with HTML, CSS & JavaScript** | No frameworks, no bloat, just pure code.
