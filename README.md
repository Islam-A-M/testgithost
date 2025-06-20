# GitHub Pages Portfolio Site

A modern, responsive portfolio website hosted on GitHub Pages.

## Setup Instructions

1. **Enable GitHub Pages:**
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

2. **Your site will be available at:**
   ```
   https://yourusername.github.io/repository-name
   ```

## Customization

### Update Personal Information

Edit the following files to personalize your site:

#### `index.html`
- Change "Your Name" in the navigation logo
- Update the hero section title and description
- Add your actual projects in the projects section
- Update contact links with your real email, GitHub, and LinkedIn URLs
- Update the footer copyright

#### Contact Links
Replace these placeholders in `index.html`:
- `your.email@example.com` → Your actual email
- `https://github.com/yourusername` → Your GitHub profile
- `https://linkedin.com/in/yourprofile` → Your LinkedIn profile

### Adding Projects

In the projects section of `index.html`, replace the placeholder projects with your actual work:

```html
<div class="project-card">
    <h3>Your Project Name</h3>
    <p>Brief description of what this project does and technologies used.</p>
    <a href="https://github.com/yourusername/project-repo" class="project-link">View Project</a>
</div>
```

### Styling Customization

The `style.css` file contains all the styling. You can customize:
- **Colors:** Change the gradient colors in the CSS variables
- **Fonts:** Update the font-family in the body selector
- **Layout:** Modify spacing, sizing, and responsive breakpoints

## Features

- ✅ Responsive design (works on all devices)
- ✅ Smooth scrolling navigation
- ✅ Animated elements on scroll
- ✅ Modern gradient design
- ✅ Interactive hover effects
- ✅ Typing animation for hero text
- ✅ Fixed navigation with scroll effects

## File Structure

```
├── index.html      # Main HTML file
├── style.css       # Styling and animations
├── script.js       # Interactive JavaScript features
└── README.md       # This file
```

## Quick Start Checklist

- [ ] Update your name and title in `index.html`
- [ ] Add your real contact information
- [ ] Replace placeholder projects with your actual work
- [ ] Update the about section with your background
- [ ] Test the site locally by opening `index.html` in a browser
- [ ] Push changes to GitHub and enable GitHub Pages
- [ ] Visit your live site and make final adjustments

## Adding More Sections

You can easily add more sections by:

1. Adding HTML structure in `index.html`
2. Adding corresponding styles in `style.css`
3. Adding navigation links if needed

Example new section:
```html
<section id="skills" class="skills">
    <div class="container">
        <h2>My Skills</h2>
        <!-- Your content here -->
    </div>
</section>
```

## Support

If you need help customizing your site, check out:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [HTML/CSS Resources](https://developer.mozilla.org/en-US/docs/Web)

Happy coding! 🚀 