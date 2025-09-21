# Personal Website

A clean, academic-style personal website built with HTML, CSS, and JavaScript, styled with Tufte CSS for an elegant, readable design.

## Features

- **Tufte CSS Styling**: Clean, academic typography inspired by Edward Tufte's design principles
- **Responsive Design**: Works on desktop and mobile devices
- **Static Site**: Pure HTML/CSS/JS - no build process required
- **GitHub Pages Ready**: Automatic deployment via GitHub Actions
- **Interactive Apps**: Section for hosting JavaScript applications

## Structure

```
personal-website/
├── index.html          # Homepage
├── about.html          # About page
├── projects.html       # Projects showcase
├── apps.html           # Interactive apps listing
├── contact.html        # Contact information
├── css/
│   ├── tufte.css       # Main Tufte CSS styling
│   └── latex.css       # Additional LaTeX-inspired styles
├── apps/
│   └── calculator.html # Example calculator app
└── .github/
    └── workflows/
        └── pages.yml    # GitHub Pages deployment
```

## Getting Started

1. **Personalize the content**: Update the placeholder text in all HTML files with your actual information
2. **Add your projects**: Edit `projects.html` to showcase your work
3. **Create apps**: Add your JavaScript applications to the `apps/` directory
4. **Update contact info**: Replace placeholder contact details in `contact.html`

## Deployment to GitHub Pages

1. Create a new repository on GitHub
2. Push this code to the repository
3. Go to repository Settings > Pages
4. Select "GitHub Actions" as the source
5. Your site will be available at `https://yourusername.github.io/repository-name`

## Adding New Apps

To add a new JavaScript app:

1. Create a new HTML file in the `apps/` directory
2. Include the Tufte CSS stylesheets
3. Add navigation links back to the main site
4. Update `apps.html` to link to your new app

## Customization

- **Colors**: Modify the color scheme in `tufte.css`
- **Typography**: Adjust font sizes and spacing
- **Layout**: Add new sections or modify the existing structure
- **Apps**: Build any JavaScript applications you want to showcase

## Technologies Used

- HTML5
- CSS3 (Tufte CSS framework)
- Vanilla JavaScript
- GitHub Pages
- GitHub Actions

## License

This project is open source and available under the [MIT License](LICENSE).