# Data Scientist Portfolio

A modern, responsive, and attractive portfolio website designed specifically for data scientists. Features smooth animations, interactive elements, and a professional design that showcases your skills and projects effectively.

## 🚀 Features

- **Modern Design**: Clean, professional layout with gradient colors and smooth animations
- **Responsive**: Fully responsive design that works on all devices
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Animated skill bars
  - Floating cards with parallax effects
  - Hover animations on project cards
  - Counter animations for statistics
- **Contact Form**: Functional contact form with validation
- **Loading Screen**: Professional loading animation
- **Mobile-Friendly**: Hamburger menu for mobile devices

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization Guide

### 1. Personal Information

Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">
    <span class="gradient-text">Your Name</span>
    <br>Data Scientist
</h1>
<p class="hero-subtitle">
    Your personal tagline or description
</p>
```

#### About Section
```html
<p>
    Your personal description and background
</p>
```

#### Statistics
```html
<div class="stat">
    <h3>50+</h3>
    <p>Projects Completed</p>
</div>
```

### 2. Skills

Update the skills section in `index.html`:

```html
<div class="skill-item">
    <span>Python</span>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 95%"></div>
    </div>
</div>
```

Adjust the percentage in `style="width: 95%"` to reflect your skill level.

### 3. Projects

Replace the project cards with your own projects:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-chart-line"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Title</h3>
        <p>Project description</p>
        <div class="project-tech">
            <span>Python</span>
            <span>TensorFlow</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link">View Project</a>
            <a href="#" class="project-link">GitHub</a>
        </div>
    </div>
</div>
```

### 4. Contact Information

Update the contact section:

```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h3>Email</h3>
        <p>your.email@example.com</p>
    </div>
</div>
```

### 5. Colors and Styling

The main color scheme uses a purple gradient. To change colors, edit the CSS variables in `styles.css`:

```css
/* Primary gradient colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Alternative color schemes you can use: */
/* Blue gradient */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Green gradient */
background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%);

/* Orange gradient */
background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);

/* Dark theme */
background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
```

## 🚀 Deployment

### Option 1: GitHub Pages (Free)

1. Create a new repository on GitHub
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your portfolio will be available at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your portfolio folder
3. Get a custom URL instantly
4. Optionally connect your GitHub repository for automatic updates

### Option 3: Vercel (Free)

1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Deploy with one click
4. Get a custom domain

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🛠️ Technologies Used

- HTML5
- CSS3 (with Flexbox and Grid)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Inter)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them with the community!

## 📞 Support

If you need help customizing your portfolio or have questions, feel free to reach out!

---

**Happy coding! 🎉** 