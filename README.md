# AI Tools Directory 🤖

> The ultimate directory of AI tools and resources for professionals and enthusiasts.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Netlify Status](https://api.netlify.com/api/v1/badges/your-badge-id/deploy-status)](https://app.netlify.com/sites/your-site/deploys)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Customization Guide](#customization-guide)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Resources & Support](#resources--support)

## Overview

AI Tools Directory is a responsive, modern directory website showcasing artificial intelligence tools and resources in a clean, three-column grid layout. Built with HTML5, CSS3, and JavaScript, it offers seamless categorization and filtering capabilities.

## Features

- 🎨 Responsive 3-column grid layout
- 🔍 Search functionality
- 🏷️ Category filtering
- 📱 Mobile-friendly design
- ⚡ Fast loading performance
- 🔄 Easy content updates
- 📊 SEO optimized

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- Git
- Text editor (VS Code recommended)

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ai-tools-directory.git

# Navigate to project directory
cd ai-tools-directory

# Install dependencies
npm install

# Start development server
npm run dev
```

## Directory Structure

```
ai-tools-directory/
├── assets/
│   ├── images/
│   ├── css/
│   └── js/
├── data/
│   └── tools.json
├── components/
├── pages/
├── index.html
└── README.md
```

## Customization Guide

### Adding Directory Items

1. Open `data/tools.json`
2. Add new item using the following format:

```json
{
  "id": "tool-name",
  "title": "Tool Name",
  "description": "Tool description",
  "category": "category-name",
  "url": "https://toolurl.com",
  "image": "tool-image.jpg"
}
```

### Modifying Categories

Edit the categories in `data/categories.js`:

```javascript
export const categories = [
  {
    id: "category-1",
    name: "Category Name",
    description: "Category description"
  }
];
```

### Updating Hero Section

Modify the hero section in `index.html`:

```html
<section class="hero">
  <h1>Your New Title</h1>
  <p>Your new description</p>
</section>
```

### Customizing Colors

Edit the CSS variables in `assets/css/variables.css`:

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --text-color: #your-color;
  --background-color: #your-color;
}
```

## Deployment

### Netlify Deployment

1. Push your code to GitHub
2. Login to Netlify
3. Click "New site from Git"
4. Select your repository
5. Configure build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
6. Click "Deploy site"

## Custom Domain Setup

1. Purchase domain from your preferred registrar
2. In Netlify:
   - Go to Site settings > Domain management
   - Click "Add custom domain"
   - Enter your domain name
3. Update DNS settings:
   - Add CNAME record pointing to your Netlify URL
   - Wait for DNS propagation (up to 48 hours)

## Troubleshooting

### Common Issues

**Images not loading:**
- Ensure image paths are correct
- Check file permissions
- Verify image format support

**Category filters not working:**
- Check category IDs match in HTML and JavaScript
- Verify event listeners are properly attached
- Console for JavaScript errors

## Resources & Support

- [Documentation Wiki](https://github.com/yourusername/ai-tools-directory/wiki)
- [Issue Tracker](https://github.com/yourusername/ai-tools-directory/issues)
- [Contributing Guidelines](CONTRIBUTING.md)

### Community
- [Discord Server](https://discord.gg/your-server)
- [Twitter](https://twitter.com/your-handle)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by [Your Name](https://yourwebsite.com)

For support, email support@aitools-directory.com