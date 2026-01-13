# AI Lab - Portland State University

This is the official website for the AI Lab at Portland State University, hosted on GitHub Pages.

## Website Structure

The website includes the following sections:

- **Home**: Landing section with lab name and tagline
- **About**: Overview of the lab's mission and values
- **Research**: Showcase of research areas and topics
- **Goals**: Lab's mission and objectives
- **Team**: Lab members organized by role (Faculty, PhD, Master's, Undergraduates, Alumni)
- **Publications**: Recent and notable publications
- **News**: Updates, announcements, and achievements
- **Contact**: Contact information and location

## Setup & Deployment

### Local Development

1. Clone this repository:
   ```bash
   git clone https://github.com/AI-Lab-PSU/AI-Lab-PSU.github.io.git
   cd AI-Lab-PSU.github.io
   ```

2. Open `index.html` in a web browser, or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

### GitHub Pages Deployment

This repository is set up for GitHub Pages. The website will automatically deploy when you push to the `main` branch.

1. Ensure your repository is named `AI-Lab-PSU.github.io` (or your organization/username)
2. Go to Settings → Pages in your GitHub repository
3. Select the `main` branch as the source
4. Your site will be available at `https://ai-lab-psu.github.io` (or your custom domain)

## Customization

### Updating Content

1. **Lab Information**: Edit the content in `index.html`:
   - Update the hero section with your lab's tagline
   - Modify the About section with your lab's description
   - Add your research areas in the Research section
   - Update goals and mission statements

2. **Team Members**: 
   - Add member cards in the appropriate sections (Faculty, PhD, Master's, etc.)
   - Replace placeholder icons with actual photos (add to `assets/images/`)
   - Update member information, research interests, and links

3. **Publications**:
   - Add your publications in the Publications section
   - Include links to PDFs, arXiv, code repositories, etc.

4. **News & Updates**:
   - Keep the News section updated with recent events, awards, and achievements

5. **Contact Information**:
   - Update the contact section with your lab's location, email, and other details

### Styling

- Modify `styles.css` to change colors, fonts, spacing, and overall design
- Color scheme can be customized via CSS variables in `:root`
- The design is fully responsive and works on mobile, tablet, and desktop

### Adding Images

1. Add images to `assets/images/`
2. Update HTML to reference the images:
   ```html
   <img src="assets/images/your-image.jpg" alt="Description">
   ```

## File Structure

```
AI-Lab-PSU.github.io/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript for interactivity
├── assets/
│   └── images/         # Image assets
└── README.md           # This file
```

## Features

- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Smooth scrolling navigation
- ✅ Modern, clean UI
- ✅ Easy to customize and maintain
- ✅ SEO-friendly structure
- ✅ Accessible design
- ✅ Fast loading times

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

To contribute to the website:

1. Create a new branch for your changes
2. Make your modifications
3. Test locally
4. Submit a pull request

## License

This website template is provided for the AI Lab at Portland State University.

## Contact

For questions or issues with the website, please contact the lab administrators.
