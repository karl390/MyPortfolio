# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and mobile-first approach.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth animations and transitions
- 🧭 Interactive navigation with smooth scrolling
- 📝 Contact form with validation
- 🎯 SEO optimized
- 🚀 Fast loading and performance optimized

## Sections

1. **Hero Section** - Introduction with call-to-action buttons
2. **About Section** - Personal information and statistics
3. **Skills Section** - Technical skills and technologies
4. **Projects Section** - Portfolio of work with links
5. **Contact Section** - Contact form and information
6. **Footer** - Social media links and copyright

## Customization Guide

### 1. Personal Information

Edit the following in `index.html`:

```html
<!-- Update your name -->
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>

<!-- Update your title -->
<p class="hero-subtitle">Full Stack Developer & Designer</p>

<!-- Update your description -->
<p class="hero-description">
    I create beautiful, functional, and user-centered digital experiences.
    Passionate about clean code and innovative solutions.
</p>
```

### 2. About Section

Update the about text and statistics:

```html
<!-- Update your about text -->
<p>
    I'm a passionate developer with a love for creating innovative solutions 
    and beautiful user experiences. With expertise in modern web technologies, 
    I bring ideas to life through clean, efficient code and thoughtful design.
</p>

<!-- Update statistics -->
<div class="stat">
    <h3>3+</h3>
    <p>Years Experience</p>
</div>
```

### 3. Skills Section

Add or remove skills by editing the skills section:

```html
<div class="skill-item">
    <i class="fab fa-react"></i>
    <span>React</span>
</div>
```

Available Font Awesome icons for skills:
- `fab fa-html5` - HTML5
- `fab fa-css3-alt` - CSS3
- `fab fa-js` - JavaScript
- `fab fa-react` - React
- `fab fa-node-js` - Node.js
- `fab fa-python` - Python
- `fab fa-git-alt` - Git
- `fab fa-docker` - Docker
- `fab fa-aws` - AWS

### 4. Projects Section

Update your projects by editing the project cards:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">
            <i class="fas fa-laptop-code"></i>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description goes here...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="your-live-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live
            </a>
        </div>
    </div>
</div>
```

### 5. Contact Information

Update your contact details:

```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
<div class="contact-item">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your City, Country</span>
</div>
```

### 6. Social Media Links

Update the footer social links:

```html
<div class="footer-social">
    <a href="your-github" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="your-linkedin" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="your-twitter" class="social-link">
        <i class="fab fa-twitter"></i>
    </a>
    <a href="your-instagram" class="social-link">
        <i class="fab fa-instagram"></i>
    </a>
</div>
```

### 7. Colors and Styling

The main color scheme is defined in `styles.css`. You can customize:

- Primary Blue: `#2563eb`
- Accent Yellow: `#fbbf24`
- Dark Gray: `#1f2937`
- Light Gray: `#f8fafc`

## Adding Your Photo

To add your profile photo:

1. Replace the profile icon in the hero section:
```html
<div class="profile-image">
    <img src="path/to/your/photo.jpg" alt="Your Name" style="width: 100%; height: 100%; object-fit: cover; border-radius: 20px;">
</div>
```

2. Update the CSS for the profile image:
```css
.profile-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 20px;
}
```

## Deployment

### Option 1: GitHub Pages (Free)

1. Create a GitHub repository
2. Upload your files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### Option 2: Netlify (Free)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Your site will be deployed instantly

### Option 3: Vercel (Free)

1. Go to [vercel.com](https://vercel.com)
2. Connect your GitHub repository
3. Deploy automatically

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Tips

1. Optimize images before uploading
2. Use WebP format for better compression
3. Minify CSS and JavaScript for production
4. Enable gzip compression on your server

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you have any questions or need help customizing your portfolio, feel free to reach out!

---

**Happy coding! 🚀** 