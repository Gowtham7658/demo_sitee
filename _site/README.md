# ONE Architecture Data Documentation

A modern, static documentation site built with Jekyll for enterprise architecture and design solutions.

## 📋 Overview

ONE Architecture Data Documentation is a comprehensive knowledge base designed for architects, technical leaders, and developers who need strategic materials to build enterprise solutions for RESCO/CFT initiatives.

The site leverages Jekyll to generate static HTML from Markdown, providing a fast, secure, and easily maintainable documentation platform optimized for SharePoint hosting and GitHub Pages.

## 🎯 Key Features

- **Modern Design** - Clean, professional UI with responsive layout
- **Fast Performance** - Static site generation with no server requirements
- **Easy Maintenance** - Content written in simple Markdown
- **Organized Structure** - Wiki-based documentation with sidebar navigation
- **Professional Branding** - Custom logo and branded header
- **Mobile Friendly** - Fully responsive design for all devices

## 📚 Documentation Sections

### 1. **Technical Architecture**
Comprehensive guidance on designing scalable, reliable, and maintainable enterprise systems.
- Architecture Patterns (Microservices, Layered, Event-Driven, Cloud-Native)
- Design Principles (Scalability, Reliability, Maintainability, Security, Performance)
- Best Practices for system design and implementation

### 2. **Technical Patterns**
Reusable solutions to common problems in software design and architecture.
- **Structural Patterns** - Adapter, Decorator, Facade, Proxy
- **Behavioral Patterns** - Observer, Strategy, Command, State
- **Creational Patterns** - Singleton, Factory, Builder, Prototype
- Pattern Selection Guide and implementation tips

### 3. **Getting Started**
Quick start guide to begin using the documentation and understand the architecture framework.
- Installation steps
- Building the site locally
- Deploying to GitHub Pages
- Contributing guidelines

### 4. **Introduction**
Overview of the entire project and the approach to technical documentation and knowledge sharing.

## 🚀 Quick Start

### Prerequisites
- Ruby 3.0 or higher
- Bundle gem (`gem install bundler`)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Gowthame123/my_jekyll.git
cd my_jekyll
```

2. Install dependencies:
```bash
bundle install
```

3. Run the local development server:
```bash
bundle exec jekyll serve
```

4. Open your browser and navigate to:
```
http://127.0.0.1:4000/my_jekyll/
```

## 📁 Project Structure

```
my_jekyll/
├── _config.yml              # Jekyll configuration
├── _includes/               # Reusable HTML components
│   ├── header.html         # Site header with logo and navigation
│   └── footer.html         # Site footer
├── _layouts/               # Page templates
│   ├── default.html        # Base layout for all pages
│   ├── wiki.html           # Layout for wiki pages with sidebar
│   ├── page.html           # Layout for static pages
│   └── post.html           # Layout for blog posts
├── _wiki/                  # Wiki documentation pages
│   ├── introduction.md     # Project introduction
│   ├── getting-started.md  # Getting started guide
│   ├── technical-architecture.md
│   └── technical-patterns.md
├── _scss/                  # SCSS source files
├── assets/                 # Compiled CSS and static assets
│   └── css/main.css       # Compiled stylesheet
├── images/                 # Images and logos
│   └── logo.png           # Site logo
├── index.markdown          # Homepage
└── README.md              # This file
```

## 🎨 Customization

### Update Site Title and Description
Edit `_config.yml`:
```yaml
title: ONE Architecture Data Documentation
description: Materials of architecture to design solutions for RESCO/CFT
```

### Change Logo
Replace `images/logo.png` with your own logo file (recommended: 80px width).

### Update Navigation Links
Edit `_includes/header.html` to modify the top navigation tabs:
```html
<a href="#" class="nav-link">Your Link</a>
```

### Add New Wiki Pages
Create a new markdown file in `_wiki/` directory:
```markdown
---
title: Your Page Title
date: 2025-11-14 10:00:00 +0530
description: Page description
---

## Your Content

Content here...
```

## 🎨 Styling

The site uses a modern color scheme:
- **Primary Blue**: #0078d4 (Microsoft blue)
- **Backgrounds**: #f8f8f8 (light gray)
- **Text**: #333333 (dark gray)
- **Borders**: #e0e0e0 (light border)

To customize colors, edit `assets/css/main.css`.

## 📦 Building for Production

Build the static site:
```bash
bundle exec jekyll build
```

This generates the site in the `_site/` directory ready for deployment.

## 🌐 Deployment

### GitHub Pages

1. Push to GitHub:
```bash
git add .
git commit -m "Your message"
git push origin main
```

2. The site will be automatically deployed to:
```
https://gowthame123.github.io/my_jekyll/
```

### Custom Server
Copy the contents of the `_site/` directory to your web server.

## 📝 Contributing

To contribute to the documentation:

1. Create a new branch:
```bash
git checkout -b feature/your-feature-name
```

2. Make your changes in Markdown

3. Test locally:
```bash
bundle exec jekyll serve
```

4. Commit and push:
```bash
git add .
git commit -m "Add your changes"
git push origin feature/your-feature-name
```

5. Create a Pull Request

## 🔧 Troubleshooting

### Port Already in Use
If port 4000 is already in use, specify a different port:
```bash
bundle exec jekyll serve --port 4001
```

### Build Errors
Clear the cache and rebuild:
```bash
rm -rf .jekyll-cache _site
bundle exec jekyll build
```

### Gem Issues
Update gems:
```bash
bundle update
```

## 📄 License

This project is open source and available under the MIT License.

## 👥 Contact

For questions or feedback about the documentation, please open an issue on GitHub.

## 🔗 Resources

- [Jekyll Documentation](https://jekyllrb.com/)
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

---

**Last Updated**: November 14, 2025  
**Version**: 1.0.0  
**Author**: ONE Architecture Team
