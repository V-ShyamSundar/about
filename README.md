# V. Shyam Sundar — Portfolio

[![Portfolio Status](https://img.shields.io/badge/portfolio-live-brightgreen)](https://v-shyamsundar.github.io/portfolio)
[![GitHub last commit](https://img.shields.io/github/last-commit/V-ShyamSundar/about)](https://github.com/V-ShyamSundar/about/commits/main)

> A modern, responsive portfolio website showcasing my journey as a Programmer Analyst at Cognizant, Databricks Certified Data Engineer, and Claude AI Architect.

<!-- ![Portfolio Preview](images/Section%201.jpg) -->

## 🌟 Live Demo

Visit the live portfolio: **[About](v-shyamsundar.github.io/about/)**

## 📋 About

This portfolio is a reflection of my professional journey, technical expertise, and passion for technology. Built with a focus on performance, accessibility, and visual appeal, it serves as a central hub for my professional presence.

### Key Features
- ✨ **Dynamic Experience Counter** — Automatically calculates and displays my experience duration from March 2025
- 🎨 **Single Global Background** — Optimized performance with just one instance of texture overlay
- 📱 **Fully Responsive** — Seamless experience across desktop, tablet, and mobile devices
- 🔄 **Lazy Loading Sections** — Smooth scroll-triggered animations for better performance
- 🖼️ **Interactive Gallery** — Showcasing teaching moments with hover effects
- 🔗 **Integrated Social Links** — GitHub, LinkedIn, and Discord connections

## 🛠️ Tech Stack

- **HTML5** — Semantic structure
- **CSS3** — Custom properties, flexbox, grid, animations, backdrop-filter
- **JavaScript** — Intersection Observer API, dynamic content updates
- **Custom Fonts** — YADK4LSvvyE-0 and YAFdJt8dAY0-0 for consistent branding

## 📁 Project Structure

```
portfolio/
├── index.html                 # Main portfolio file
├── images/                    # All image assets
│   ├── Background.svg         # Global texture overlay
│   ├── Section 1.jpg          # Hero/profile image
│   ├── Teaching 1.jpg         # Teaching gallery image 1
│   ├── Teaching 2.jpg         # Teaching gallery image 2
│   ├── Teaching 3.jpg         # Teaching gallery image 3
│   └── Teaching 4.jpg         # Teaching gallery image 4
└── fonts/                     # Custom font files
    ├── 1c0556dd4544e7d0bc192e095918ecfb.woff2  # YADK4LSvvyE-0
    ├── 226618464330c99b64fcaf1d7142c1e7.woff2  # YAFdJt8dAY0-0 (regular)
    └── e532966f486645f74efaf7432e1d01c2.woff2  # YAFdJt8dAY0-0 (bold)
```

## 🚀 Sections

### Home
- Introduction with dynamic experience counter
- Profile image with hover zoom effect
- Call-to-action button

### About Me
- Professional background and current role
- Core expertise tags (Databricks, AI Architecture, Python, SQL, Apache Spark, Claude AI, ETL Pipelines)
- Personal interests (Video Games, AI Architecture, Data Pipelines, Teaching & Mentorship)

### Work Experience
- **Cognizant** — Programmer Analyst Trainee (Current — dynamically updating)
- **NSIC** — Cybersecurity Intern (Feb 2024)
- **NSIC** — Raspberry Pi Intern (Apr 2023)

### Certifications
- **Databricks Data Engineering Certification** — Professional certification with verification link
- **Claude AI Architect Certification** — Advanced AI certification with verification link
- **GitHub Projects & Contributions** — Link to open-source repositories

### Teaching & Knowledge Sharing
- Inspirational quote about the joy of teaching
- Gallery of 4 teaching moments with hover captions
- Reflection on mentorship philosophy
- Custom object-position adjustment for optimal framing

### Get In Touch
- Social media links (GitHub, LinkedIn, Discord)
- Availability for collaborations and knowledge-sharing sessions

## 🔧 Dynamic Features

### Experience Calculator
The portfolio automatically calculates and displays:
- Total experience duration (years & months)
- Smart formatting (e.g., "1 yr 1 mo", "2+ years")
- Updates hero section, about section, and experience card
- Refreshes every hour for real-time accuracy

```javascript
// Joining date: March 1, 2025
const startDate = new Date(2025, 2, 1);
```

### Lazy Loading
Sections fade in as they enter the viewport:
- Hero section — immediate load with animation
- Other sections — load on scroll
- Images — progressive loading with fade effect

## 🎨 Customization

### Update Join Date
Edit the `calculateExperience()` function:
```javascript
const startDate = new Date(2025, 2, 1); // Year, Month-1, Day
```

### Modify Colors
Adjust CSS variables in `:root`:
```css
:root {
  --bg-dark: #000000;
  --gold: #FFB514;
}
```

### Adjust Gallery Image Crop
For specific gallery images, modify object-position:
```css
.gallery-item:first-child img {
  object-position: 75% center; /* Adjust percentage as needed */
}
```

### Add/Remove Sections
Each section follows the same pattern:
```html
<section id="section-name" class="section-grid lazy-section">
  <div class="container-center">
    <!-- Your content here -->
  </div>
</section>
```

## 📱 Responsive Design

- **Desktop** (>1024px) — Full experience with all animations
- **Tablet** (768px-1024px) — Adjusted spacing and font sizes
- **Mobile** (<768px) — Collapsed navigation, stacked layouts, optimized text sizes

## 🔗 External Links

- **GitHub**: [@V-ShyamSundar](https://github.com/V-ShyamSundar)
- **LinkedIn**: [V Shyam Sundar](https://www.linkedin.com/in/v-shyam-sundar/)
- **Discord**: [@shyamsundar](https://discord.com/users/320966827486478337)

## 📧 Contact

For any questions or collaboration opportunities, reach out via:
- **Email**: ssoct2003@gmail.com
- **LinkedIn**: [V Shyam Sundar](https://www.linkedin.com/in/v-shyam-sundar/)

<div align="center">
  <sub>Built with 💻 by V. Shyam Sundar | Programmer Analyst @ Cognizant</sub>
</div>
