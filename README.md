# Data Analyst Portfolio

A modern, responsive portfolio website designed for data analysts to showcase their skills, projects, and experience.

## Features

- Clean and modern design
- Fully responsive layout
- Smooth scrolling navigation
- Animated skill cards
- Project showcase section
- Contact information
- Social media links

## Customization

### Personal Information

1. Open `index.html` and update the following:
   - Your name in the hero section
   - About section content
   - Contact information
   - Social media links

### Projects

1. In the projects section of `index.html`, duplicate the project card structure to add more projects:
```html
<div class="project-card">
    <div class="project-image">
        <img src="images/your-project-image.jpg" alt="Project Title">
    </div>
    <div class="project-info">
        <h3>Project Title</h3>
        <p>Project description goes here.</p>
        <div class="project-tags">
            <span>Tag 1</span>
            <span>Tag 2</span>
        </div>
    </div>
</div>
```

### Skills

1. In the skills section of `index.html`, modify the skill cards to match your expertise:
```html
<div class="skill-card">
    <i class="fas fa-icon-name"></i>
    <h3>Skill Category</h3>
    <p>Skill details</p>
</div>
```

### Styling

1. The main styles are in `css/style.css`
2. Colors can be modified by changing the CSS variables
3. Font sizes and spacing can be adjusted in the CSS file

## Adding Project Images

1. Create an `images` folder in the root directory
2. Add your project images to this folder
3. Update the image paths in the project cards

## Running the Portfolio

1. Simply open `index.html` in a web browser
2. For local development, you can use any local server

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Credits

- Font Awesome for icons
- Google Fonts for typography
- Unsplash for stock images (if used)

## License

This project is open source and available under the MIT License. 