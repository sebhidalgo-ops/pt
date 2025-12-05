# Sebastian - AWS Cloud Engineer Portfolio

A modern, responsive portfolio website showcasing real-world AWS cloud engineering projects and technical expertise.

<img width="1899" height="1031" alt="image" src="https://github.com/user-attachments/assets/306d5642-32ae-4a2e-a849-c0febd2bb347" />


## 🚀 Live Demo

[View Live Site](#) <!-- Add your deployed URL here -->

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Pages Overview](#pages-overview)
- [Projects Showcase](#projects-showcase)
- [Customization](#customization)
- [Deployment](#deployment)
- [Contact](#contact)
- [License](#license)

## 🎯 About

This portfolio website showcases my journey as an intermediate AWS Cloud Engineer, featuring production-style projects that solve real business problems. The site demonstrates practical cloud engineering skills through cost optimization, automation, monitoring, and AI-powered solutions built on AWS infrastructure.

## ✨ Features

- **Responsive Design** - Fully mobile-friendly layout
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Multi-page Navigation** - Easy-to-navigate sections
- **Project Showcase** - Detailed overview of AWS cloud projects
- **Skills Matrix** - Comprehensive technical skills display
- **Contact Form** - Direct communication channel
- **Social Integration** - LinkedIn and GitHub links
- **Optimized Performance** - Fast loading times

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Custom styling with modern features
- **JavaScript** - Interactive elements
- **Font Awesome 6.5.0** - Icon library

### Design
- Clean, minimalist aesthetic
- Custom color scheme (#246bff primary)
- Responsive grid layouts
- Card-based components

## 📁 Project Structure

```
portfolio/
│
├── index.html          # Homepage with hero section
├── about.html          # About me page
├── skills.html         # Technical skills showcase
├── works.html          # Projects portfolio
├── contact.html        # Contact form and information
├── style.css           # Global styles
│
└── image/
    └── foto terno.jpg  # Profile image
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML/CSS

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/portfolio.git
```

2. Navigate to project directory
```bash
cd portfolio
```

3. Open in your browser
```bash
# Simply open index.html in your browser
# Or use a local server (recommended)
python -m http.server 8000
# Then visit: http://localhost:8000
```

## 📄 Pages Overview

### Home (`index.html`)
- Hero section with introduction
- Call-to-action button
- Social media links
- Professional tagline

### About (`about.html`)
- Professional background
- AWS engineering focus areas
- Career objectives
- Technical approach

### Skills (`skills.html`)
8 key skill categories:
- AWS Core Services
- Automation & Serverless
- Databases
- Cost Optimization
- AI on AWS
- Web Development
- DevOps Tools
- Soft Skills

### Works (`works.html`)
Featured projects:
1. **AWS Cost Tracking Dashboard** - CUR data analysis and visualization
2. **Automated Backup Pipeline** - S3-based backup solution
3. **Website Uptime Monitor** - Serverless monitoring system
4. **AI Customer Inquiry Manager** - Bedrock-powered classification
5. **AI Inventory Tracker** - Predictive inventory management

### Contact (`contact.html`)
- Contact form
- Direct email link
- Social media connections

## 🎨 Customization

### Update Personal Information

1. **Replace profile image:**
   - Add your photo to `/image/` folder
   - Update image path in `index.html`

2. **Update social links:**
```html
<!-- Find and replace in all HTML files -->
<a href="YOUR-LINKEDIN" target="_blank">
<a href="YOUR-GITHUB" target="_blank">
<a href="mailto:youremail@example.com">
```

3. **Modify colors:**
```css
/* In style.css, update primary color */
.highlight {
  color: #246bff; /* Change to your brand color */
}
```

### Add New Projects

Edit `works.html` and add a new card:
```html
<div class="work-card">
  <h3>Project Title</h3>
  <p>Project description...</p>
  <p><strong>Tech:</strong> Technologies used</p>
</div>
```

## 🌐 Deployment

### Deploy to GitHub Pages

1. Push to GitHub repository
2. Go to Settings → Pages
3. Select branch (main) and folder (root)
4. Save and visit your site at `https://yourusername.github.io/portfolio/`

### Deploy to AWS S3

```bash
# Create S3 bucket
aws s3 mb s3://your-portfolio-bucket

# Enable static website hosting
aws s3 website s3://your-portfolio-bucket --index-document index.html

# Upload files
aws s3 sync . s3://your-portfolio-bucket --exclude ".git/*"

# Set public read permissions
aws s3api put-bucket-policy --bucket your-portfolio-bucket --policy file://policy.json
```

### Deploy to Netlify

1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Or connect your GitHub repository
3. Deploy with one click

## 📬 Contact

- **Email:** youremail@example.com
- **LinkedIn:** [Your LinkedIn Profile](#)
- **GitHub:** [Your GitHub Profile](#)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](#).

## ⭐ Show Your Support

Give a ⭐️ if you like this project!

---

**Built with ❤️ by Sebastian** | AWS Cloud Engineer
