# CALD HDR Engagement Forum Website

A modern, responsive website for the Culturally and Linguistically Diverse (CALD) Higher Degree by Research Engagement Forum at The University of Queensland.

## 📋 Project Overview

This website is built with:
- **HTML5** - Semantic markup
- **CSS3** - Modern, responsive design
- **JavaScript** - Interactive features and smooth scrolling

## 🎨 Design Features

- Modern, clean aesthetic inspired by UQ Tokyo Workshop design
- Fully responsive layout (mobile, tablet, desktop)
- Smooth scrolling navigation
- Interactive cards and sections
- QR code registration integration
- Google Form integration

## 📁 File Structure

```
cald-uq.github.io/
├── index.html          # Main website page
├── styles.css          # Styling and responsive design
├── script.js           # Interactive functionality
├── qr-code.png        # QR code image (to be added)
└── README.md          # This file
```

## 🚀 Getting Started

### Prerequisites
- Git
- GitHub account
- A QR code image pointing to the registration form

### Local Development

1. Clone or download the files to your local machine
2. Open `index.html` in your web browser to preview the site
3. Edit the HTML, CSS, and JavaScript as needed

### QR Code Setup

1. Generate a QR code for your Google Form registration link:
   https://docs.google.com/forms/d/1efc4Xc74nRmJgpsNSfdbroWt_7QIdQW5B2R50PG2AyM/edit?ts=6ab9f43e

2. You can use free QR code generators like:
   - https://qr-code-generator.com
   - https://www.qr-code-generator.de
   - Google Charts API

3. Save the QR code as `qr-code.png` in the project directory

4. The website will automatically display it in the registration section

## 📦 GitHub Pages Setup

Follow these steps to publish your website at `www.cald-uq.github.io`:

### Step 1: Create a New Repository

1. Go to GitHub and create a new repository named **`cald-uq.github.io`**
   - Make sure it's public
   - Don't initialize with README (you'll add your own)

### Step 2: Initialize Git Locally

In your CALD project directory:

```bash
git init
git add .
git commit -m "Initial commit: CALD HDR forum website"
```

### Step 3: Add Remote and Push to GitHub

```bash
git remote add origin https://github.com/YOUR-USERNAME/cald-uq.github.io.git
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **Deploy from a branch**
4. Select **main** branch and **root** folder
5. Click **Save**

Your site will be published at: **https://cald-uq.github.io**

### Step 5: Set Up Custom Domain (Optional)

If you want to use `www.cald-uq.github.io` as a custom domain:

1. In repository Settings → Pages
2. Under "Custom domain", enter `cald-uq.github.io`
3. Add a CNAME record with your domain registrar (if applicable)

## 🎯 Sections

### 1. **Navigation**
   - Sticky header with links to all sections
   - Mobile-responsive hamburger menu
   - Direct registration button

### 2. **Hero Section**
   - Eye-catching gradient background
   - Clear call-to-action button
   - Main message about the forum

### 3. **About Section**
   - Forum overview and mission
   - Key aims and objectives
   - Support for CALD HDR students

### 4. **Focus Areas (Programs)**
   - 6 interactive cards showcasing main activities
   - Emoji icons for visual appeal
   - Hover animations

### 5. **Events Section**
   - Placeholder for upcoming events
   - Ready for future event listings

### 6. **Registration Section**
   - QR code for quick mobile registration
   - Direct link to Google Form
   - Gradient background for visual distinction

### 7. **Contact Section**
   - Forum leadership information
   - Committee member details
   - Links to UQ resources

### 8. **Footer**
   - Quick links to sections
   - Resource links
   - Copyright information

## 🛠️ Customization

### Change Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #00539b;      /* UQ Blue */
    --secondary-color: #e74c3c;    /* Red accent */
    --accent-color: #3498db;       /* Light blue */
    /* ... more colors ... */
}
```

### Update Content

Edit `index.html` to:
- Change text content
- Update committee member names/details
- Modify program descriptions
- Add real event information
- Update contact information

### Add Events

In the `<!-- Events Section -->`, replace the placeholder with:

```html
<div class="event-card">
    <h3>Event Title</h3>
    <p><strong>Date:</strong> DD Month YYYY</p>
    <p><strong>Time:</strong> HH:MM - HH:MM</p>
    <p><strong>Location:</strong> Building/Room</p>
    <p>Event description and details...</p>
</div>
```

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🔗 Links

- **UQ Home**: https://www.uq.edu.au
- **Registration Form**: https://docs.google.com/forms/d/1efc4Xc74nRmJgpsNSfdbroWt_7QIdQW5B2R50PG2AyM/edit?ts=6ab9f43e
- **Career Development Framework**: https://cdf.graduate-school.uq.edu.au/home
- **Employability Hub**: https://employability.uq.edu.au

## 🎓 About the CALD Forum

The CALD HDR Engagement Forum supports culturally and linguistically diverse higher degree by research students at UQ by providing:

- Research skills workshops
- Symposia for research showcase
- Wellbeing check-ins
- Cultural connection events
- Cultural intelligence training
- Career coaching sessions

## 📧 Contact

For questions about the website or forum, contact the forum coordinators at UQ.

## 📄 License

This website is maintained by The University of Queensland.

---

**Last Updated**: October 2026
